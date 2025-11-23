FROM lasuite/impress-backend@sha256:f170c156e1867ec088248b2341f315c48312375a1ad6fa8ff64cc43941b9a937

LABEL org.opencontainers.image.title="LaSuite Docs Backend Image"
LABEL org.opencontainers.image.description="LaSuite Docs Backend Image preconfigured for FSBCG."
LABEL org.opencontainers.image.authors="Martin Bens <martin.bens@uni-bayreuth.de>"

LABEL org.opencontainers.image.source="https://github.com/fsbcg-ubt/lasuite-docs"
LABEL org.opencontainers.image.version="v3.10.0"
LABEL org.opencontainers.image.licenses="MIT"

LABEL org.opencontainers.image.base.name="registry.hub.docker.com/lasuite/impress-backend"
LABEL org.opencontainers.image.base.digest="sha256:f170c156e1867ec088248b2341f315c48312375a1ad6fa8ff64cc43941b9a937"

LABEL maintainer="Martin Bens <martin.bens@uni-bayreuth.de>"
LABEL lasuite_docs_version="v3.10.0"

# Django Configuration
ENV DJANGO_CONFIGURATION=Production
ENV DJANGO_SETTINGS_MODULE=impress.settings

# Logging Configuration
ENV LOGGING_LEVEL_HANDLERS_CONSOLE=ERROR
ENV LOGGING_LEVEL_LOGGERS_ROOT=INFO
ENV LOGGING_LEVEL_LOGGERS_APP=INFO

ENV PYTHONPATH="/app"
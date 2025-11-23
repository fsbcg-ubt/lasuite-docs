FROM lasuite/impress-frontend@sha256:c9dee7dc1ca578ce1aad919b38752b25ea89424b605159811546e3b94a15a7f4

LABEL org.opencontainers.image.title="LaSuite Docs Frontend Image"
LABEL org.opencontainers.image.description="LaSuite Docs Frontend Image preconfigured for FSBCG."
LABEL org.opencontainers.image.authors="Martin Bens <martin.bens@uni-bayreuth.de>"

LABEL org.opencontainers.image.source="https://github.com/fsbcg-ubt/lasuite-docs"
LABEL org.opencontainers.image.version="v3.10.0"
LABEL org.opencontainers.image.licenses="MIT"

LABEL org.opencontainers.image.base.name="registry.hub.docker.com/lasuite/impress-frontend"
LABEL org.opencontainers.image.base.digest="sha256:c9dee7dc1ca578ce1aad919b38752b25ea89424b605159811546e3b94a15a7f4"

LABEL maintainer="Martin Bens <martin.bens@uni-bayreuth.de>"
LABEL lasuite_docs_version="v3.10.0"

ADD docker/frontend/default.conf.template /etc/nginx/templates/docs.conf.template

ENTRYPOINT ["/docker-entrypoint.sh"]

CMD ["nginx", "-g", "daemon off;"]
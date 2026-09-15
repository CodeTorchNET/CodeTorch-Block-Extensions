FROM busybox:1.36

LABEL org.opencontainers.image.title="CodeTorch Block Extensions gallery"
LABEL org.opencontainers.image.description="Static build of the CodeTorch extension gallery, served by copying /build into a shared volume."
LABEL org.opencontainers.image.licenses="MIT"

ARG SOURCE_URL
ARG REVISION
LABEL org.opencontainers.image.source="${SOURCE_URL}"
LABEL org.opencontainers.image.revision="${REVISION}"

COPY build/ /build/

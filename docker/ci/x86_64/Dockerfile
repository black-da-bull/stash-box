
# must be built from /dist directory

FROM alpine:latest@sha256:f271e74b17ced29b915d351685fd4644785c6d1559dd1f2d4189a5e851ef753a as app
LABEL MAINTAINER="https://discord.gg/Uz29ny"

COPY stash-box-linux /usr/bin/stash-box

EXPOSE 9998
CMD ["stash-box", "--config_file", "/root/.stash-box/stash-box-config.yml"]

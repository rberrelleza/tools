FROM alpine:latest
RUN apk --no-cache --update add gettext
WORKDIR /work
ENV TAG latest
CMD envsubst '${TAG}' < /work/file

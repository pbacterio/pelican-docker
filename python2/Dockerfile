FROM python:3-onbuild

VOLUME /build/input
VOLUME /build/output

WORKDIR /build/input
ENTRYPOINT pelican --output /build/output

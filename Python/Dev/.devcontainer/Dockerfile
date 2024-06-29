FROM docker.io/library/python:3.11-dev-amd64 as final

# Even though not recommended (due to SBOM among other apko features), you could further extend any dev image as follows
USER root
RUN apk add poetry

USER nonroot

ENTRYPOINT [ "/usr/bin/python" ]

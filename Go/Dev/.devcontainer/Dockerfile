FROM docker.io/library/go:1.22-dev-amd64 as final

# Even though not recommended (due to SBOM among other apko features), you could further extend any dev image as follows
USER root
RUN apk add trivy

USER root

ENTRYPOINT [ "/usr/bin/go" ]

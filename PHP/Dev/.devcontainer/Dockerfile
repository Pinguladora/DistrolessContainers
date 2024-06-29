FROM docker.io/library/php:8.2-fpm-dev-amd64 as final

# Even though not recommended (due to SBOM among other apko features), you could further extend any dev image as follows
USER root
RUN composer require psr/log

USER php

ENTRYPOINT [ "/bin/php" ]

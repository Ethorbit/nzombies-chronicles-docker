FROM osixia/openldap:1.5.0
ARG UID
ARG GID
RUN usermod -u "$UID" openldap &&\
    groupmod -g "$GID" openldap

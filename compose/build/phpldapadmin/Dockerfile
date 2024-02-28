FROM osixia/phpldapadmin:0.9.0
ARG UID
ARG GID
RUN usermod -u "$UID" www-data &&\
    groupmod -g "$GID" www-data

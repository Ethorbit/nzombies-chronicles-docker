FROM osixia/openldap:1.5.0
ARG UID
ARG GID
#COPY ./entrypoint.sh /
RUN usermod -u "$UID" openldap &&\
    groupmod -g "$GID" openldap
#    apt update -y &&\
#    apt-get install -y envsubst yq
#VOLUME /etc/users
#ENTRYPOINT [ "/entrypoint.sh" ]

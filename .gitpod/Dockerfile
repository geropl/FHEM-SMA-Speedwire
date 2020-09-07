FROM gitpod/workspace-full

USER root

RUN apt-get install -yq \
        libio-socket-multicast-perl \
    && apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/*

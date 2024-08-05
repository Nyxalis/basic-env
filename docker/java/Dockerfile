FROM ghcr.io/nyxalis/base:base

USER root

# Install requirements
RUN DEBIAN_FRONTEND="noninteractive" apt install -y zip unzip

USER coder

# Install sdkman
RUN curl -s "https://get.sdkman.io" | bash
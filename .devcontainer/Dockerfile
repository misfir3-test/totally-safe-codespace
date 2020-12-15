FROM mcr.microsoft.com/vscode/devcontainers/universal:linux

RUN sudo apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && sudo apt-get -y install curl

ENTRYPOINT [ "/bin/bash" ]

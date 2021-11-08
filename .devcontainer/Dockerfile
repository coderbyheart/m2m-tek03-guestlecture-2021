FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:16

RUN wget https://github.com/jgm/pandoc/releases/download/2.16.1/pandoc-2.16.1-1-amd64.deb && \
    sudo dpkg -i pandoc-2.16.1-1-amd64.deb && \
    pandoc -v

RUN npm install -g npm@8

RUN sudo apt -y update && sudo apt -y install inotify-tools
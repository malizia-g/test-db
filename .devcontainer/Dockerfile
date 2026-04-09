FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

RUN apt-get update \
    && DEBIAN_FRONTEND=noninteractive apt-get install -y mariadb-server mariadb-client \
    && rm -rf /var/lib/apt/lists/*

FROM mcr.microsoft.com/devcontainers/java:0-11

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
       maven \
       ca-certificates && \
    apt-get clean && rm -rf /var/lib/apt/lists/*

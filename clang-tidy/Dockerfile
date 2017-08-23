FROM ubuntu:latest

RUN apt-get update && apt-get install -y --no-install-recommends \
  clang-tidy \
  git \
  ssh \
  ca-certificates \
 && rm -rf /var/lib/apt/lists/*

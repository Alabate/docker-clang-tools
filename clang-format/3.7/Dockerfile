FROM ubuntu:xenial

RUN apt-get update && apt-get install -y --no-install-recommends \
  clang-format-3.7 \
  git \
  ssh \
  ca-certificates \
 && rm -rf /var/lib/apt/lists/*

RUN ln -s /usr/bin/clang-format-3.7 /usr/bin/clang-format

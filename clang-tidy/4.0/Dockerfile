FROM ubuntu:xenial

RUN apt-get update && apt-get install -y --no-install-recommends \
  clang-tidy-4.0 \
  git \
  ssh \
  ca-certificates \
 && rm -rf /var/lib/apt/lists/*

 RUN ln -s /usr/bin/clang-tidy-4.0 /usr/bin/clang-format

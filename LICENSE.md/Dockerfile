# ==============================================================================
# Dockerfile
# ==============================================================================
FROM ruby:2.5-slim-stretch
ENV LANG C.UTF-8

RUN apt update && apt install -y --no-install-recommends nodejs libpq-dev && \
  apt clean && apt autoremove && \
  rm -rf /var/lib/apt/lists/*
  

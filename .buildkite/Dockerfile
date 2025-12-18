FROM buildkite/agent:3-ubuntu

USER root
RUN apt-get update && apt-get install -y --no-install-recommends \
    python3 \
    python3-pip \
    python3-venv \
    git 

USER buildkite
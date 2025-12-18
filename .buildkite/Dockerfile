FROM buildkite/agent:3

USER root
RUN apt-get update && apt-get install -y \
    python3 \
    python3-pip \
    python3.11-venv \
    git
USER buildkite
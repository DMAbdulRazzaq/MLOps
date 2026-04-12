FROM python:3.11-slim-bookworm

RUN apt-get update && \
    apt-get install -y git make curl jq docker.io && \
    rm -rf /var/lib/apt/lists/*

RUN apt-get update && apt-get install -y python3 python3-venv python3-pip

# for build steps only
WORKDIR /workspace 
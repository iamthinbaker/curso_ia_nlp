FROM python:3.11-bookworm

# System deps: build tools
RUN apt-get update && apt-get install -y --no-install-recommends \
    build-essential \
    python3-dev \
    curl \
    && rm -rf /var/lib/apt/lists/*

# Install Claude Code (native installer)
RUN curl -fsSL https://claude.ai/install.sh | sh

WORKDIR /workspace

# Install pybind11 first (fasttext build dep)
RUN pip install --no-cache-dir pybind11

# Install project + optional build deps (jupyter-book)
COPY pyproject.toml .
RUN pip install --no-cache-dir ".[build]"

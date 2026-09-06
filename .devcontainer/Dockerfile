FROM mcr.microsoft.com/devcontainers/base:bookworm
RUN echo "wl-proof fixture layer $(date -u +%FT%TZ)" > /etc/wl-proof-built && apt-get update && apt-get install -y --no-install-recommends jq && rm -rf /var/lib/apt/lists/*

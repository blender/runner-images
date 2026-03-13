FROM ghcr.io/catthehacker/ubuntu:act-latest

ENV DEBIAN_FRONTEND=noninteractive

# Install Blender / bpy runtime dependencies
RUN apt-get update && apt-get install -y --no-install-recommends \
    libx11-6 \
    libxi6 \
    libxkbcommon0 \
    libxfixes3 \
    libxrender1 \
    libxxf86vm1 \
    libxrandr2 \
    libxext6 \
    libxcb1 \
    libxcb-util1 \
    libgl1 \
    libegl1 \
    libdbus-1-3 \
    libsm6 \
    libice6 \
 && rm -rf /var/lib/apt/lists/*

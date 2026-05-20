# server-scripts

## Docker install on Debian

1. Install curl: apt update && apt install -y curl
2. run docker script: curl -fsSL https://raw.githubusercontent.com/cameronhanton/server-scripts/refs/heads/main/debian-docker-install.sh | bash

OR
apt update && apt install -y curl && curl -fsSL https://raw.githubusercontent.com/cameronhanton/server-scripts/refs/heads/main/debian-docker-install.sh | bash

## Add github to server

ssh-keygen -t ed25519 -C "identification description"

cat ~/.ssh/id_ed25519.pub

Add to keys in github repo settings

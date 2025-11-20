n8nio/base:22

apk add --no-cache --update openssh sudo shadow bash
 echo node ALL=\(root\) NOPASSWD:ALL > /etc/sudoers.d/node && chmod 0440 /etc/sudoers.d/node
mkdir /workspaces && chown node:node /workspace npm install -g pnpm


run mkdir -p ~/.pnpm-store && pnpm config set store-dir ~/.pnpm-store --global

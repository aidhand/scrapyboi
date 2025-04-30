FROM mcr.microsoft.com/devcontainers/typescript-node

USER node

# Install package managers via npm
RUN npm install -g corepack@latest npm@latest pnpm@latest bun@latest
RUN npm install -g prettier typescript eslint

FROM mcr.microsoft.com/vscode/devcontainers/base:alpine-3.17

RUN apk update && \
    apk add --no-cache openssl grep git gcompat npm && \
    apk upgrade

# install pnpm
RUN npm install -g pnpm



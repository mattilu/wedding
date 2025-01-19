FROM mcr.microsoft.com/devcontainers/javascript-node:1.1-22-bookworm

RUN npm install -g @angular/cli

EXPOSE 4201

CMD ["ng", "serve", "--host", "0.0.0.0", "--port", "4201", "--watch"]

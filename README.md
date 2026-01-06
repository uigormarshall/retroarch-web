# retroarch-web

RetroArch rodando no navegador usando Docker e Docker Compose.

Este repositório foi criado como **material de apoio** para vídeos e estudos sobre Docker, homelab e auto-hospedagem.

---

## 🎮 O que é isso?

Aqui rodamos o **RetroArch Web (Emscripten)** como uma aplicação web estática, servida por um container Docker.

Em termos simples:
- O RetroArch já vem pronto (arquivos `.js`, `.wasm`, `.data`)
- O Docker apenas fornece o ambiente
- O Docker Compose organiza tudo

---

## 📦 O que você vai encontrar aqui

- `docker-compose.yml`
- (opcional) `Dockerfile`
- Estrutura básica para servir o RetroArch Web
- Pasta para cores (`.wasm`)

---

## 🚀 Como subir o projeto

### Pré-requisitos
- Docker
- Docker Compose

### Subir os containers
```bash
docker compose up -d

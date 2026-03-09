# Projeto DevOps com Docker

Aplicação web simples containerizada utilizando Docker e NGINX.

Este projeto foi desenvolvido como parte do meu aprendizado em DevOps, com foco em containerização e execução de aplicações web utilizando Docker.

---

## Tecnologias utilizadas

- Docker
- NGINX
- HTML
- CSS
- GitHub Codespaces

---

## Estrutura do projeto

docker-web-app
│
├── Dockerfile
├── index.html
├── style.css
└── README.md

---

## Como executar o projeto

### 1 - Construir a imagem Docker

docker build -t site-devops .

### 2 - Executar o container

docker run -p 8080:80 site-devops

### 3 - Acessar no navegador

http://localhost:8080

---

## Objetivo do projeto

Praticar conceitos fundamentais de DevOps:

- Containerização de aplicações
- Criação de imagens Docker
- Execução de containers
- Exposição de portas
- Deploy em ambiente cloud (GitHub Codespaces)

---

## Autor
Rayane Santana

Projeto desenvolvido para estudo de DevOps e Cloud Computing.
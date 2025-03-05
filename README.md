# Aula Docker

Este repositório contém exemplos práticos para aprender Docker.

## Como usar

 1. Clone o repositório:
   ```bash
   git clone git@github.com:gusascorrea/aula_docker.git
   cd aula_docker

# 2. Construa a imagem Docker

docker build -t minha-imagem .

# 3. Execute o container
docker run -d -p 8501:8501 --name meu-container minha-imagem

# Para remover o container
# Redis Counter
[![CI](https://github.com/slvgabriel/devops-python-api/actions/workflows/ci.yml/badge.svg)](https://github.com/slvgabriel/devops-python-api/actions/workflows/ci.yml)

A aplicação consiste em uma API Python (Flask) que se conecta a um banco em memória (Redis) para manter um contador de visitas persistente. O contador é atualizado à cada acesso.

## Stacks

* **Python (Flask)**
* **Redis**
* **Docker & Docker Compose**
* **GitHub Actions**

## Como Rodar

Pré-requisitos: Ter o [Docker](https://www.docker.com/) instalado.

1. **Clone o repositório:**

   `git clone https://github.com/slvgabriel/devops-python-api/`

2. **Suba os containers:**
   
   `docker-compose up --build`
   
3. Acesse a aplicação:
  
   `http://localhost:5000`  

4. Para parar a execução: Pressione Ctrl+C no terminal ou rode:
   
   `docker-compose down`
     

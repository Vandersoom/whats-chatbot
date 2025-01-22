# ChatBot com Inteligência Artifical para WhatsApp

Este README fornece informações essenciais sobre como configurar e executar o projeto em seu ambiente local.


## Links Importantes para Download

Sera Nescessario Cria contas para Utilização das Kyes de serviços

- https://waha.devlike.pro/

- https://huggingface.co/

- https://console.groq.com/playground

- https://docs.docker.com/engine/install/

## Requisitos

Certifique-se de que você tenha os seguintes requisitos instalados em seu sistema:

- Python (versão recomendada: 3.10 ou superior)
- Docker e docker compose
- Outras dependências listadas no arquivo `requirements.txt`


## Instalação das Dependências

Com o ambiente virtual ativado, instale as dependências do projeto usando o comando:
```bash
pip install -r requirements.txt
```


## Rodar o projeto

Após instalar as dependências, inicialize os serviços com docker-compose:
```bash
docker-compose up --build
```

# Configuração Docker Compose do Zabbix

Este repositório contém uma configuração Docker Compose para implantar contêineres do Zabbix, MySQL, Grafana e Zabbix Agent.

## Pré-requisitos

- Docker e Docker Compose estão instalados no seu sistema.

## Uso

1. Clone este repositório:

   git clone https://github.com/seunomeusuario/zabbix-docker-compose.git
   cd zabbix-docker-compose

Crie um arquivo .env no diretório do projeto e defina as variáveis de ambiente necessárias:

MYSQL_ROOT_PASSWORD
MYSQL_DATABASE
MYSQL_USER
MYSQL_PASSWORD

Inicie os serviços:
docker-compose up -d

Acesse os serviços:

Zabbix Frontend: http://localhost
Grafana: http://localhost:3000

Para parar os serviços:

docker-compose down

Configuração

O arquivo .env contém variáveis de ambiente que configuram o banco de dados MySQL para o Zabbix. Ajuste essas variáveis conforme necessário.


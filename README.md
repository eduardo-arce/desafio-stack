# Desafio Stack

Esse projeto reune todos os serviços necessários para o funcionamento do Desafio.

## Dependências

* docker
* docker-compose
* git bash

## Organização dos diretórios Stack, Api e Web

Desafio/

├── desafio-api/

├── desafio-db/

├── desafio-web/

Salvar os diretórios do projeto nesse formato, 
para o bom funcionamento do docker compose no desafio-stack.

## Suba o ambiente

```sh
./start.sh
```

## Gerar Tabelas na Banco

Veja isso em: [https://github.com/eduardo-arce/desafio-api](https://github.com/eduardo-arce/desafio-api)

## Acesse

Espere o ambiente subir e acesse:

Web: [http://localhost:4000](http://localhost:4000)

Api: [http://localhost:8000/swagger](http://localhost:8000/swagger)

## Login na Aplicação

Usuário: admin

Senha: admin

### Exclua tudo

Atenção: o procedimento abaixo removerá as imagens, volumes e containers.

```sh
./clean-all.sh
```

### Acompanhe os logs

```sh
./logs.sh
```

## Credenciais do Desafio DB

```
Driver: PostgreSQL
Host: localhost
Username: desafioindtuser
Password: desafioindtpassword
Database: desafioindt
Porta: 5432
```

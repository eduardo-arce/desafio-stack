# Desafio Stack

Esse projeto reune todos os serviços necessários para o funcionamento do Desafio.

## Dependências

* docker
* docker-compose
* git bash

## Suba o ambiente

```sh
./start.sh
```

## Acesse

Espere o ambiente subir e acesse:

Web: [http://localhost:4000](http://localhost:4000)

Api: [http://localhost:8000/swagger](http://localhost:8000/swagger)

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

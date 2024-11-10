# Stencil Stack

Esse projeto reune todos os serviços necessários para o funcionamento do Stencil.

Pode ser utilizado para deploy em um servidor.

Esta aplicação requer no minimo um processador de 2.5 ghz, 8GB de ram e 100gb de disco.

## Dependências

* docker
* docker-compose
* git bash

## Suba o ambiente local

Passe o ambiente desejado como paramêtro:

```sh
./start.sh local
```

## Acesse

Espere o ambiente subir e acesse:
[http://localhost:4000/](http://localhost:4000/)

### Exclua tudo

Atenção: o procedimento abaixo removerá as imagens, volumes e containers.

```sh
./clean-all.sh local
```

## For tester

Para subir o ambiente completo, basta executar o comando abaixo:

* Git Bash

```sh
./start.sh qa
```

## Usando o ambiente de produção

```sh
./start.sh prod
```

## Credenciais do Stencil DB

```
Driver: oracle
Host: localhost
Username: stencil
Password: stencilpassword
Database: XE
Porta: 1521
```

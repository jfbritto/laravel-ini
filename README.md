
# Laravel inicial para novos projetos
### Passo a passo
Clone o Repositório

Crie o Arquivo .env
```sh
cd projeto-laravel/
cp .env.example .env
```

Atualizar o nome do banco de dados no arquivo .env
```dosini

DB_DATABASE=nome_que_desejar_db

```

Suba os containers do projeto
```sh
docker-compose up -d
```

Acessar o container
```sh
docker-compose exec php bash
```


Instalar as dependências do projeto
```sh
composer update
```


Gerar a key do projeto Laravel
```sh
php artisan key:generate
```


Acessar o projeto
[http://localhost:8989](http://localhost:8989)

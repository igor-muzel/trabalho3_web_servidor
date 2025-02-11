## Requisitos 

* PHP 8.2 ou superior 
* MySlq
* Composer 

## Como rodar o projeto
Duplicar o arquivo ".env.example" e renomear para ".env".<br>
Alterar o arquivo .env as credenciais do banco de dados<br>

Instalar as dependencias do PHP
```
composer install
```

Gerar a chave no arquivo .env
```
php artisan key:generate
```

## Sequencia para criar o projeto
Criar o projeto com laravel 
```

composer create-project laravel/laravel .
```

Alterar o arquivo .env as credenciais do banco de dados<br>

Criar o arquivo de rotas para a API
```

php artisan install:api
```
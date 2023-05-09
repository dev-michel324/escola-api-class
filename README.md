# escola-api-class

## Descrição
O projeto é um serviço disponibilizado por API, utilizando o framework **Laravel** que irá disponibilizar recursos para que seja
feito o gerenciamento de uma escola.
As rotas disponibilizadas são:

* / -> retorna json
* /hello -> retorna uma string

## Dependências 
* [Laravel (latest)](https://laravel.com/)

## Como executar
Para subir a aplicação localmente, rode o comando abaixo substituindo **<porta>** pela porta de sua escolha,
como a **8000**

```
php artisan serve --port=<porta>
```

Para subir a aplicação na porta padrão, utilize:
```
php artisan serve
```
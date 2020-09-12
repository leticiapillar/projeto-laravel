### Projeto Prático Laravel com Docker

- [Imagem Docker Hub](https://hub.docker.com/r/leticiapillar/projeto-laravel)

- Como excutar:
```bash
> docker run -d --name laravel -p 8000:8000 leticiapillar/projeto-laravel
> docker exec -it laravel bash
> bash-5.0# php artisan serve --host=0.0.0.0
```
Acesse: http://localhost:8000/
### Содержимое Dockerfile:

```FROM nginx

COPY ./html /usr/share/nginx/html
```

1. Монтируем образ:
> docker build -t название_образа

2. Запускаем контейнер:
> docker run -d -p порт:80 название_образа

 
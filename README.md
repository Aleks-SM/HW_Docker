### Задание №1

#### Сборка контейнера
```docker build -t my_nginx:v1 -f nginx_dockerfile .```

#### Запуск контейнера
```docker run -it -p 8000:80 my_nginx:v1```

#### проверка в браузере
[Click](http://localhost:8000/)

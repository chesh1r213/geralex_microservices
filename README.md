# geralex_microservices
geralex microservices repository

ДЗ по docker-4

 - Научлись собирать образы приложения reddit с помощью docker-compose
 - Задать имя образа используя container_name, данная настройка вынесена так же в переменную .env


ДЗ по docker-3

 - Загружено приложение reddit-microservices;
 - Реализовано через Dockerfile сборка и разворачивание трех приложений "comment" "post-py" "ui";
 - Дополнительно оптимизирована сборка приложения post-py (обновлены версии компонентов и отключен лог так как мешало запуску, требуется привлечение разработчика для обновления кода) тем самым убраны при сканировании в 0 уязвимости приложения;
 - Оптимизировано использование базовых образов тем самым уменьшены размеры докер образов в десятки раз;
 - Дополнительно запускаем mongodb с подключением локального volme для хранения сообщений;

ДЗ по docker-2

В рамках данного ДЗ:
- Установили docker, docker-compose, docker machine
- Создали свой образ
- Создали docker host
- Зарегистрировались на Docker Hub с последующей загрузкой образа в публичное хранилище для последующего использования в работе без необходимости новой сборки

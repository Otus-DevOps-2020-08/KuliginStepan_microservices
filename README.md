# KuliginStepan_microservices
KuliginStepan microservices repository

---
1. Добавил Dockerfile для приложения
2. Создал аккаунт в docker hub и запушил туда созданный образ приложения
---
1. Собрал образы для микросервисов
2. Создать выделенную сеть
3. Добавил volume для MongoDB
---
1. Проверил различные виды сетей (none, bridge, host)
2. Доработал docker-compose файл
3. Создал .env файл со всеми переменными среды

docker compose по умолчанию делает префикс по названию директории, префикс можно задать так `docker-compose -p NAME up -d`

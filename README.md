# pet-docker_nginx_flask_postgres_gunicorn


### Данный проект не претендует на "как нужно делать" и создан для того, что-б продемонстрировать совместную работу docker, nginx, flask, postgres, gunicorn, 
протестировать эти модули отдельно и в связке, а также миграции используя alembic.

Проект можно запусnить в нескольких вариантах используя docker-compous или docker.
- отдельно запустить контейнер с базой данных или приложение
- запустить все в одном запустив контейнер в котором собирутся docker, nginx, flask, postgres, gunicorn

Для создания и заполнения БД необходимо использовать CLI.py либо раскоментировать строчку `@app.before_first_request` в app.py, либо используя любой другой способ в том числе консоль БД.   

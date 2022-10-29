![This is an image](https://github.com/Casp1an/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)

yamdb_workflow

Адрес сайта http://51.250.26.178/api/v1/
Документация http://51.250.26.178/redoc/

Как запустить

Склонируйте репозиторий - git clone
Откройте терминал и установите виртуальное окружение - py -m venv venv
Активируйте виртуальное окружение - source venv/Scripts/activate
Перейдите в папку с зависимостями и установите их - pip install -r requirements.txt
Создайте новый workflow b cкопируйте полностью содержимое файла yamdb_workflow.yml в репозиторий на github
Войдите на свой удаленный сервер в облаке.
Остановите службу nginx: sudo systemctl stop nginx 
Установите docker: sudo apt install docker.io 
Установите docker-compose, с этим вам поможет официальная документация.
Скопируйте файлы docker-compose.yaml и nginx/default.conf из проекта на сервер в home/<ваш_username>/docker-compose.yaml и home/<ваш_username>/nginx/default.conf соответственно.
Добавьте в Secrets GitHub Actions переменные окружения для работы базы данных
Запуште проект git push

Автор

Casp1an - https://github.com/Casp1an

# jenkins-pipiline
конфиги в виде бэкапа, который сделан через плагин thinBackup (папку с бэкапами поместить в /srv внутри контейнера)
Для запуска job в контейнер нужно доустановить zip и ansible, ставятся через скрипт install_requirmints.sh
Для запуска контейнера docker-compose up -d
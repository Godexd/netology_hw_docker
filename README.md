# Docker


Создание образа:

    user@user:~$ docker image build -t my-flask .


Переменная окружения БД

    user@user:~$ export post_dns='examle'


Запустить контейнер:

    user@user:~$ docker container run my-flask:lates
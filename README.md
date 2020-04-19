# Module E8
Сборка frontend-а и backend-а для домашнего задания от SkillFactory по модулю E8

Сам проект являет собой Fullstack роботой.
Фронтенд и бек енд разделены на разные репозитории.


## Запуск
Сначала ножно скопировать этот репозиторий.

После нужно скопировать репозитории с фронтом и бэком
в соответствующие папки frontend и backend

Ссылка на репозиторий с Фронтом: https://github.com/m-v-kalashnikov/Module_E8_frontend.git

Ссылка на репозиторий с Бэком: https://github.com/m-v-kalashnikov/Module_E8_backend.git

Структура поекта на данном этапе должна быть следующей:

(ВАЖНО!!!  названия папок backend и frontend должны быть именно такими а не теми которыми они скопируются с репозитория.)
~~~
├── backend
│   └── app.py
│   └── consumer.py
│   └── ...
├── frontend
│   └── public
│   └── src
│   └── Dockerfile
│   └── ...
└── docker-compose.yaml
└── README.md
└── LICENSE
└── .gitignore
└── ...
~~~

После переходите в папку в которой находится docker-compose.yaml и запускаете команду:
~~~
docker-compose up --build
~~~

Следующим шагом будет запуск фронта(временная мера так как скоро поменяю что запуск будет происходить через docker-compose.yaml).
заходим в README.md в папке з фронтом и выполняем указаные в нем действия.

## P.S.

Сейчас реализация муторная... в дальнейшем планируется:

- сделать рефакторинг бэка и порозталкивать по папкам и модулям, а не в одном файле.
- добавить NGINX.
- сделать запуск фронта и бэка через docker-compose.yaml.
- рефакторнуть фронт и убрать баги.

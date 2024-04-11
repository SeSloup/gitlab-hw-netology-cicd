# Домашнее задание к занятию "Что такое DevOps. СI/СD" - `Сологуб Евгений`

Задание 1
Что нужно сделать:

Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
Установите на машину с jenkins golang.
Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.
![alt text](https://github.com/SeSloup/gitlab-hw-netology-cicd/blob/main/screens/1-0.png)
![alt text](https://github.com/SeSloup/gitlab-hw-netology-cicd/blob/main/screens/1-1.png)
![alt text](https://github.com/SeSloup/gitlab-hw-netology-cicd/blob/main/screens/1-2.png)
![alt text](https://github.com/SeSloup/gitlab-hw-netology-cicd/blob/main/screens/1-3.png)

Задание 2
Что нужно сделать:

Создайте новый проект pipeline.
Перепишите сборку из задания 1 на declarative в виде кода.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

![alt text](https://github.com/SeSloup/gitlab-hw-netology-cicd/blob/main/screens/2-1.png)
![alt text](https://github.com/SeSloup/gitlab-hw-netology-cicd/blob/main/screens/2-2.png)

Задание 3
Что нужно сделать:

Установите на машину Nexus.
Создайте raw-hosted репозиторий.
Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
Загрузите файл в репозиторий с помощью jenkins.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

![alt text](https://github.com/SeSloup/gitlab-hw-netology-cicd/blob/main/screens/3-1.png)
![alt text](https://github.com/SeSloup/gitlab-hw-netology-cicd/blob/main/screens/3-2.png)
![alt text](https://github.com/SeSloup/gitlab-hw-netology-cicd/blob/main/screens/3-3.png)


   


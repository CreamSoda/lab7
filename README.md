Лабораторная работа 7. Вариант 12: Сайт афиша (кинотеатры, сеансы, фильмы). 
=================================

Постановка задачи
-----------------

Нужно реализовать веб-приложение на тему в соответствии с вариантом задания (Сайт афиша). Варианты совпадают с ЛР №2. Технологии, которые нужно использовать: 

- фреймворк Ruby On Rails
- ХД mongodb или couchdb

Деплой приложения
-------

1. Загрузить проект из репозитория git:

  ```
  git clone https://github.com/akonit/lab_7.git
  ```
2. Перейти в директорию проекта:

  ```
  cd lab_7
  ```
3. Выполнить следующую команду:

  ```
  bundle install
  ```
4. Создать базу данных для приложения:

  ```shell
  mongo < db/create_db
  ```
5. Поднять сервер:

  ```
  rails server
  ```
6. Перейти по следующему адресу:

  [http://localhost:3000](http://localhost:3000)
7. Действия по редактированию данных доступны только администратору. Логин - **admin**, пароль - **admin**. Поиск по фильмам осуществляется на вкладке фильмов, поиск по кинотеатрам - на вкладке кинотеатров, по сеансам - на вкладке сеансов.
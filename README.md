# Дипломный проект по профессии «Fullstack-разработчик на Python»
## Облачное хранилище My Cloud
 [Задание к диплому...](https://github.com/netology-code/fpy-diplom/blob/main/README.md)
## Содержание проекта
 [Backend...](https://github.com/Serg1811/FPYDiploma_backend.git)
 [Frontend...](https://github.com/Serg1811/FPYDiploma_frontend.git)
***
 [Ссылка на сервер backend...](https://89.111.174.181:8000)
 ***


 p.s.: 
 backend: выполнен полностью.
 С развёртыванием на сервер возникли проблемы. Сначало долго промучился с обновлением python до версии 3.12, и venv. потом эту проблему решил но возникли другие. При команде "gunicorn config.wsgi -b 0.0.0.0:8000" возникла ошибка: пишет не обнаружен модуль django. Дальше соответственно ответ на "sudo systemctl status gunicorn"  - "Active: failed"
Эту проблему пока не получилось решить.
frontend: реализован пока частично.
Выполнена регистрация, аутенфикация и меню User. Осталось выполнить меню Admin и доделать визуализацию.

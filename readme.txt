Проект для докер десктоп

Для сборки проекта зайти в его папку cd project и выполнить: docker-compose up --build -d

Выполнить: docker ps должно быть запущено 2 образа: nginx:latest  и project-backend

Для проверки в другом терминале выполнить curl http://localhost

Для остановки и запуска использовать команды: docker-compose up и docker-compose down



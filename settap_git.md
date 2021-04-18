[к содержанию](./readme.md)
 

## Настройка GIT

1. Для того, чтобы настроить GIT - нужно настроить имя пользователя и email для идентификации. Эти настройки хранятся в конфигурационном файле.
 
2. Чтобы настроить имя пользователя и пароль для всех проектов, нужно прописать следующие команды:
 
``git config --global user.name ”Ivan Ivanov”``
``git config --global user.email ivan.ivanov@gmail.com``
 

3. Если есть необходимость для конкретного проекта поменять автора (для личного проекта, например), можно убрать --global, и так получится:
 

``git config user.name ”Ivan Ivanov”
 
 ``git config user.email ivan.ivanov@gmail.com``



Для работы инсталим java 8 oracle.
В настройках проекта на circli необходимо указать
SSH Permissions
-- private_key
Environment Variables
-- SSH_HOST	ip удаленного сервера
-- SSH_USER	имя пользователя на удаленном сервере, ему же нужн подкинуть public_key для доступа по ssh

Nginx проксирует запросы с 8080 на 9000(порт приложения)

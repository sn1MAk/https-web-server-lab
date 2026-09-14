#SSL

У цій роботі SSL/TSL використовується для налаштування HTTPS через Nginx.

Приватний ключ 'server.key' та сертифікат 'server.crt' не додані до репозиторію з міркувань безпеки.


Для створення ключа та self-signed сертифікату були використані команди:
```bash 

sudo openssl genrsa -out /etc/nginx/ssl/server.key 2048

sudo openssl req -new -x509 \
-key /etc/nginx/ssl/server.key \
-out /etc/nginx/ssl/server.crt \
-days 30

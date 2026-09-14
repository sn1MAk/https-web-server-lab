# HTTPS Web Server Lab

Лабораторна робота: розгортання веб-сервера nginx, налаштування HTTPS за допомогою OPENSSL та публікація сторінки через ngrok.

## Мета роботи

- встановити та налаштувати Nginx;
- створити веб-сторінку;
- створити приватний ключ та SSL-сертифікат за допомогою OpenSSL;
- налаштувати HTTPS у Nginx;
- перевірити роботу веб-сервера в локальній мережі;
- забезпечити публічний доступ до локального сервера через ngrok;
- оформити результати лабораторної роботи та розмістити матеріали на GitHub.

## Використані технології

- Windows
- WSL2
- Ubuntu
- Nginx
- OpenSSL
- PowerShell
- ngrok
- Git
- GitHub

## Структура проєкту

```text
https-web-server-lab/
├── website/
│   └── index.html
├── nginx/
│   └── https-lab.conf
├── ssl/
│   └── README.md
├── screenshots/
├── report/
├── .gitignore
└── README.md

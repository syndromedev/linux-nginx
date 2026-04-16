# Nginx setup on Linux

## Что делал
Разворачивал и настраивал веб-сервер nginx на Linux.

## Установка
sudo apt install nginx

## Проверка статуса
systemctl status nginx

## Проверка порта
ss -tulnp | grep :80

## Проверка доступности
curl localhost

## Работа с логами
journalctl -u nginx

## Что понял
— как запускать и проверять сервисы  
— как искать ошибки через логи  
— как проверять порты и доступность сервиса  

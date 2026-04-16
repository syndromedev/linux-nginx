# Nginx setup on Linux

Установил nginx:
sudo apt install nginx

Проверил статус:
systemctl status nginx

Проверил порт:
ss -tulnp | grep :80

Проверил доступ:
curl localhost

Смотрел логи:
journalctl -u nginx

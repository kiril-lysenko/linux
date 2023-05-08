### Установка на Ubuntu xrdp и Xfce
Обновить пакеты apt:
````
sudo apt update
````
Открыть  TCP-порт 3389
````
sudo ufw allow 3389
````
Установить xrdp:
````
sudo apt install xrdp
````
Установить пакет xorgxrdp:
````
sudo apt install xorgxrdp
````
Активировать xrdp:
````
sudo systemctl enable xrdp
````
Проверить статус xrdp: Статус должен быть active:
````
Установить графическое окружение рабочего стола Xfce:
````
sudo apt install xfce4
````
Запустить xrdp командой
````
sudo systemctl start xrdp
````

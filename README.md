Universidad Nacional Autónoma de México

Facultad de Ingeniería

Domingo 20 de Febrero de 2022

BOT TELEGRAM - RASPBERRY PI 👨🏻‍💻🤖

- Creación de un bot de telegram utilizando una tarjeta raspberry pi 4 model b de 2GB de memoria RAM
- La implementación se realizará con Python

Objetivo: 
- Manejo y monitoreo remoto de Raspberry Pi y sus puertos GPIO
mediante la programación y aplicación de Bots de Telegram


Antes de iniciar:
- Instalación en Raspberry
    - sudo apt-get update && sudo apt-get upgrade -y
    - sudo apt-get install python-setuptools
    - sudo apt-get install python-pip
    - sudo pip install pyTelegramBotAPI
    - sudo apt-get install sysstat
    - sudo chown -R pi:pi /home/pi/pyTelegramApi
    - cd /home/pi/pyTelegramBotApi
    - sudo python setup.py install

- Instalación en Dispositivo Inteligente
    - Instalar Telegram
    - Buscar @BotFather. 
    - Escribir el comando /newbot.
    - Ingresar el alias o nombre mostrado que será asignado al bot.
    - Ingresar un nombre de usuario para el bot.
    - Guardar el token generado.
    - Buscar el bot creado por el nombre de usuario.
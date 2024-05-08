SESION 3

CEPMOTRIL1/cepmotril2023

raspberry pi 5

raspberrypi.org


-->learn    cursos

-->teach     recursos para profesores

github.com/javacasm

eth0 192.168.4.244
wlan 192.168.5.106
berryjapa
usuario/usuario

ssh usuario@berryjapa


instalar snap

HOMEASSISTANT desde snap store

vscode

http://www.arduinoblocks.com/

pip3 install esptool --break-system-packages    --->> formatea el ESP32 conectado por USB a RAspberry pi
Con Thonny instalamos el sistema operativo microPython en ESP32
thonny-run-configure interpreter-interpreter-micropythonesp32-install

tinkercad
microbit

ESP32
	-- patillas PWM (intensidades 10 bits)
	-- patillas ADC

fritzing -> diseño de circuitos

https://micropython.org/


Conexión remota desde fuera de tu casa: darse de alta con cuenta en raspberry
NUEVO:RPI Connect
joseant_perez@hotmail.com/cursomotril

sudo apt update
sudo apt upgrade
sudo apt install rpi-connect

accedes desde un navegador: www.raspberrypi.com/connect
y en la raspberry se hace sigin

CONFIGURAR EL ESP32 PARA CONECTAR A WIFI
Thonny->tools->manage packages->
mm_wlan
microdot

github.com/monkmakes/mm_wlan
examples->hello.py

comentar línea 16 de mm_wlan.py

HOME ASSISTANT se conecta al web que hemos creado en ESP32

hay que instalar pasarelas para cada marca de dispositivos y meter usuarios y contraseñas de cada app propia de cada marca

http://localhost:8123

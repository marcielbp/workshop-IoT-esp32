# workshop-IoT-esp32

Neste seminário serão apresentadas dicas e experiências para começar a desenvolver soluções IoT usando sistemas embarcados. Como exemplo de aplicação, desenvolveremos uma aplicação IoT completa usando o sistema embarcado de baixo custo ESP32, a plataforma online Thingspeak e o ambiente Google Drive.

## 1. O que é necessário?
Dispositivo compatível com firmware [Micropython](www.micropython.org), exemplos:
* [ESP32](http://www.micropython.org/download/esp32/);
* [ESP8266](http://www.micropython.org/download/esp8266/);
> Utilize o [esptool](https://github.com/espressif/esptool) para gravar o firmware na placa.

## 2. Como acessar a placa?
Utilize no terminal o comando [`picocom`](https://linux.die.net/man/8/picocom), análogo ao programa [`Putty`](https://www.putty.org/) no Windows. É necessário especificar a porta USB para conexão. Talvez seja necessário dar acesso à porta `ttyUSBx` [modificando permissões de dialout](https://askubuntu.com/questions/133235/how-do-i-allow-non-root-access-to-ttyusb0).

# TALLER 0

### Google Chrome

Se realizó la instalación a través del terminal, utilizando los siguientes comandos:
```
sudo nano /etc/apt/sources.list
deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main
wget https://dl.google.com/linux/linux_signing_key.pub
sudo apt-key add linux_signing_key.pub
sudo apt update
sudo apt install google-chrome-stable
```
Capturas de pantalla:

![alt text](chrome01.png)
![alt text](chrome02.png)
![alt text](chrome03.png)
![alt text](chrome04.png)

### Google Lighthouse
Lighthouse es una herramienta automatizada de código abierto diseñada para mejorar la calidad de tus apps web. Puedes ejecutarla como una extensión de Chrome o desde la línea de comandos. Le proporcionas a Lighthouse una URL que quieres auditar, Lighthouse ejecuta una serie de pruebas contra la página, y luego genera un informe sobre el rendimiento de la página. A partir de aquí, puedes usar las pruebas desaprobadas como indicadores de lo que puedes hacer para mejorar tu app.

__Nota__: Lighthouse actualmente tiene un gran enfoque sobre las funciones de las Progressive Web Apps, como Add to homescreen y soporte sin conexión. Sin embargo, el objetivo general del proyecto es ofrecer una auditoría de extremo a extremo de todos los aspectos de la calidad de la app web.

Fuente: https://developers.google.com/web/tools/lighthouse/?hl=es

Capturas de pantalla - Instalación:

![alt text](lighthouse01.png)
![alt text](lighthouse02.png)

Capturas de pantalla - Ejecución:

![alt text](lighthouse_test01.png)
![alt text](lighthouse_test02.png)
![alt text](lighthouse_test03.png)
![alt text](lighthouse_test04.png)
![alt text](lighthouse_test05.png)

### Web Server for Chrome
Capturas de pantalla - Instalación:

![alt text](webserver_chrome01.png)
![alt text](webserver_chrome02.png)

Capturas de pantalla - Ejecución:

![alt text](webserver_chrome03.png)

Lista de programas que cumplen con la misma funcionalidad:
 - Apache HTTP Server
 - Nginx
 - SimpleHTTPServer (python)

### IDE preferido
Se realizó la instalación de ATOM a través del terminal, utilizando los siguientes comandos:
```
sudo add-apt-repository ppa:webupd8team/atom
sudo apt update
sudo apt install atom
```

Capturas de pantalla - Instalación:

![alt text](atom01.png)
![alt text](atom02.png)
![alt text](atom03.png)

### Git
Capturas de pantalla - Instalación:

![alt text](git01.png)

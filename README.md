# SG90_raspberryPi
Come utilizzare un servomotore SG90 su Raspberry Pi

Il pinout del servo motore è il seguente:

![alt text](https://i0.wp.com/www.moreware.org/wp/wp-content/uploads/2022/02/fa19a830e604aaa2ac71ea4005534440.jpg?w=631&ssl=1)

Materiali da utilizzare:
* Raspberry Pi
* Servo motore SG90

Il diagramma di collegamento è il seguente (per il mio servomotore), attenzione guardate il datasheet del vostro servo motore, quasi sicuramente dovete tenere a mente quello riportato qui sopra:

![alt text](https://i0.wp.com/www.moreware.org/wp/wp-content/uploads/2022/02/GPIOWiringDiagram.png?w=584&ssl=1)

# Cosa fare prima

Digita nel terminale prima di eseguire lo script python il seguente comando

`sudo pigpiod`

Per maggiori info leggi questa [guida](https://gpiozero.readthedocs.io/en/stable/api_output.html) ufficiale riguardante questo problemi.

# [Codice](https://github.com/SimoneMoreWare/SG90_raspberryPi/blob/main/sg90.py)

# Video

https://www.youtube.com/watch?v=4nLq3LlqXfA


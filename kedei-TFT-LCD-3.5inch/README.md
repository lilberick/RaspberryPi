# Display Kedei TFT LCD 3.5 inch <!--(http://kedei.net/)-->

![](.img/kedei-atras.png)

![](.img/kedei-frente.png)


1. Descargar el **driver kedei** <!--(http://kedei.net/download.html)-->  
    Ejecutar estos comandos en la terminal de cualquier sistema operativo Gnu/Linux.

	```sh
    $ git clone git@github.com:lilberick/RaspberryPi.git
    $ mv RaspberryPi/kedei-TFT-LCD-3.5inch/LCD .
    $ cat LCD/LCD_show_v6_1_3.tar.gz-a* > LCD_show_v6_1_3.tar.gz
    $ tar xf LCD_show_v6_1_3.tar.gz
    $ rm -rf LCD RaspberryPi LCD_show_v6_1_3.tar.gz
    $ cd LCD_show_v6_1_3
	```

2. Modos de uso

	* Para usar la pantalla kedei (No se podrá usar RCA ni HDMI)

		```sh
		$ ./LDC35_V
		```

		![](.img/PrendiendoKedei.gif)

	* Para volver a la normalidad (No se podrá usar la pantalla kedei)

		```sh
		$ ./LCD_hdmi
		```

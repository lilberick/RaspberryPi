# [Display Kedei TFT LCD 3.5 inch](http://kedei.net/)

![](.img/kedei-atras.png)

![](.img/kedei-frente.png)


1. Descargar el [driver kedei](http://kedei.net/download.html)

	![](.img/DescargarDriver.png)

	```sh
	$ tar xf LCD*.tar.gz
	$ cd LCD_show_v6_1_3
	$ ./LCD35_v
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

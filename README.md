# Brazo-Robotico
Proyecto Final "Brazo Robotico"

Arduino, es una poderosa plataforma de hardware libre, ideal para poyectos de electrónica que van desde el encendido de un LED hasta un complejo sistema de domótica para controlar una casa entera. Java, uno de los lenguajes de programación más extendidos del mundo se puede utilizar con Arduino. Por lo tanto en esta practica nuestra meta es la siguiente:

Desarrollar paso a paso un proyecto para controlar y programar un Brazo Robot, simulando las funciones básicas de un robot industrial.

El robot debe tener dos funciones básicas:
Programar: Registrar las posiciones de los brazos en tres dimensiones (cada registro es un "paso", un programa consiste en una serie de pasos).
Ejecutar: Realice en secuencia las posiciones registradas en el "Programa". El robot ejecutará el programa hasta que se use el comando "ABORTAR".

Características principales:

El proyecto se usa para controlar robots con  4 DOF ("Grados de libertad").
El robot se debe controlar en modo "REMOTO" (a través de una programa en java por medio del puerto serial).
La información para el usuario se podrá proporcionar a través de LEDS de colores, una pantalla LCD de 2 líneas y/ó sonido (un zumbador).
Debe de contener un botón de paro de emergencia (Físico).
Si existe un fallo y/o corte de energía, después de restablecerse la corriente el robot debe de continuar el programa (aunque este no se encuentre conectado a la aplicación).
Los brazos robóticos se pueden clasificar de acuerdo con el número de "articulaciones" o "Grados de libertad" (DOF) que tienen.
            -La "Base", o "Cintura", por lo general puede girar el brazo 180o o 360o, dependiendo del   tipo de Servo utilizado (aquí                  este proyecto, se debe utilizar un motor a pasos para girar 360o)
            -El "Hombro" es el responsable de "levantar o bajar" el brazo verticalmente
            -El "codo" hará que el brazo "avance o retroceda".
            -La "Garra" o "Pinza" funciona abriendo o cerrándose para "agarrar cosas".
            
**DESARROLLO**

+ Abra para ver el esquema de los servos

<a href="https://1drv.ms/u/s!Aizy46b43Ozzgk5rTU4EjNBM010O"><img src="https://1drv.ms/u/s!Aizy46b43Ozzgk5rTU4EjNBM010O" /></a>


+ Abra para ver el esquema  del motor a pasos

            
**RESULTADOS**

+ Abra para ver los resultados del brazo 
<a href="https://1drv.ms/u/s!Aizy46b43Ozzgk9h0-hKleCeObHm"><img src="https://1drv.ms/u/s!Aizy46b43Ozzgk9h0-hKleCeObHm" /></a>


<a href="https://1drv.ms/u/s!Aizy46b43OzzglBhDNGaP31aLTTd"><img src="https://1drv.ms/u/s!Aizy46b43OzzglBhDNGaP31aLTTd" /></a>


<a href="https://1drv.ms/u/s!Aizy46b43OzzglIyA2om43Twf11B"><img src="https://1drv.ms/u/s!Aizy46b43OzzglIyA2om43Twf11B" /></a>


+Abra para ver la interface en java


<a href="https://1drv.ms/u/s!Aizy46b43OzzglOP4ArGYtSwO10k"><img src="https://1drv.ms/u/s!Aizy46b43OzzglOP4ArGYtSwO10k" /></a>




**---------------------------- SOFTWARE LIBRE ----------------------------**


En la actualidad software libre es consecuencia del método de la ética ya que por elección manifiesta de su autor puede ser copiado, 
estudiado, modificado, utilizado libremente con cualquier fin y redistribuido con o sin cambios o mejoras. En esta practica se
utilizaron los siguientes:

1. Ubuntu (Sistema Operativo)

<a href="https://1drv.ms/u/s!Aizy46b43OzzghxX44Er1X3MZlBv"><img src="https://1drv.ms/u/s!Aizy46b43OzzghxX44Er1X3MZlBv" /></a>


2. NotePad ++ 

<a href="https://1drv.ms/u/s!Aizy46b43OzzgiB5g6eUlGQMT6f-"><img src="https://1drv.ms/u/s!Aizy46b43OzzgiB5g6eUlGQMT6f-" /></a>


3. LibreOffice (Suite ofimática)





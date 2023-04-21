# ***Documentación Dojos*** 1


## Integrantes 
- Martin Luque
- Nazareno Gonzalez
- Martin Luque
- Agustin Mondani
- Facundo Miño 

## Proyecto: DOJO.
![Tinkercad](./Imagenes/Imagen.png)

## Consigna
El gobierno de la cuidad quiere actualizar los semáforos que tiene instalados. La empresa
“ScaraRobotics” gano la licitación y ahora les toca a los desarrolladores de la empresa generar
un proyecto low cost que cumpla con las especificaciones que el gobierno de la cuidad nos
impone, a saber las especificaciones son las siguientes.

1- El semáforo tiene que tener 2 leds de cada color como minimo, en caso de que uno se
rompa, lo ideal serian 3.

2- Tiene que implementar los tiempos correctos como se detallan a continuación.

3- El verde dura 45 segundos.

4- El amarillo dura 5 segundos.

5- Rojo dura 30 segundos.

6- Tiene que tener señalización para personas no videntes como se detalla a
continuación.

7- Durante el verde: No sonar

8- Durante el amarillo: Tiene que sonar 1 vez cada 2 segundos en un tono suave.

9- Durante el rojo: Tiene que sonar 1 vez por segundo en un tono fuerte.


## Codigo pricnipal
Esta funcion se encarga de encender el sonido y apagarlo el tiempo deseado

SONIDO son #define que utilizamos para agregar el buzzer, asociandolo a pines de la placa arduino.

~~~ C (lenguaje en el que esta escrito)
void Sonar(int tiempo, int num, int potencia){
    for (int i = 0;i<num;i++){
	tone(SONIDO,potencia);
	delay(500);
    noTone(SONIDO);
	delay(tiempo);
  }
}
~~~

## :robot: Link al proyecto
- [Link Tinkercad](https://www.tinkercad.com/things/3UB47iIs1Iu-funky-borwo-lahdi/editel?sharecode=VVW9Wf8ew58oqMX5lVovzLTdFrnXEZk0e0ResUwPpYg)
- [Link GDB](https://onlinegdb.com/sXxg-CL2o)

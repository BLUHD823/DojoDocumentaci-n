# Ejemplo Documentación Dojos


## Integrantes 
- Martin Luque
- Nazareno Gonzalez
- Martin Luque
- Agustin Mondani
- Facundo Miño 


## Proyecto: Contador binario.
![Tinkercad](./img/ContadorBinario.png)


## Descripción
En este parrafo deberan describir que funcion cumple su proyecto. Que solucion esta ofreciendo.

## Codigo pricnipal
Esta codigo se encarga de encender y apagar los leds, y el sonido

LED_ROJO, LED_ROJO, LED_AMARILLO, LED_AMARILLO2, LED_VERDE, LED_VERDE2, SONIDO son #define que utilizamos para agregar los leds y el buzzer, asociandolo a pines de la placa arduino.

~~~ C (lenguaje en el que esta escrito)
void loop()
{
  digitalWrite(LED_ROJO, HIGH);
  digitalWrite(LED_ROJO2, HIGH);
  for (int i = 0;i<30;i++){
	tone(SONIDO,2000);
	delay(500);
    noTone(SONIDO);
	delay(500);
  }
  digitalWrite(LED_ROJO, LOW);
  digitalWrite(LED_ROJO2, LOW);

  digitalWrite(LED_AMARILLO, HIGH);
  digitalWrite(LED_AMARILLO2, HIGH);
    for (int i = 0;i<2;i++){
	tone(SONIDO,5000);
	delay(500);
    noTone(SONIDO);
	delay(1500);
  }
  digitalWrite(LED_AMARILLO, LOW);
  digitalWrite(LED_AMARILLO2, LOW);

  digitalWrite(LED_VERDE, HIGH);
  digitalWrite(LED_VERDE2, HIGH);
  delay(45000);
  digitalWrite(LED_VERDE, LOW);
  digitalWrite(LED_VERDE2, LOW);
	
  digitalWrite(LED_AMARILLO, HIGH);
  digitalWrite(LED_AMARILLO2, HIGH);
  delay(5000);
  digitalWrite(LED_AMARILLO, LOW);
  digitalWrite(LED_AMARILLO2, LOW);

}

~~~

## :robot: Link al proyecto
- [Link Tinkercad](https://www.tinkercad.com/things/3UB47iIs1Iu-funky-borwo-lahdi/editel?sharecode=VVW9Wf8ew58oqMX5lVovzLTdFrnXEZk0e0ResUwPpYg)

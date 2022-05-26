# Practica-1 LED BLINK

Aquesta pràctica m'ha servit bàsicament per iniciar-me amb l'ESP32 i el Platformio i per a realitzar el meu primer codi involucrant el material esmentat a continuació.

# Material

- ESP32
- Led
- Protoboard


# Funcionament

Com es pot comprovar al vídeo adjuntat el funcionament és senzill.
El led (assignat al pin 13) s'encen i s'apaga cada 2000ms (2 segons), això ho podem veure directament al codi ja que hem implementat un delay del valor esmentat. A part, cada vegada que el led canvia d'estat (ON/OFF) ens ho diu per pantalla, això ho hem fet gràcies al Serial.println(ON/OFF) que trobem abans dels delays.

```c++
#include <Arduino.h>
int led = 13;

void setup() {                  
  pinMode(led, OUTPUT);     
}

void loop() {
  digitalWrite(led, HIGH);   // turn the LED on (HIGH is the voltage level)
  Serial.println("ON");
  delay(2000);               // wait for a second
  digitalWrite(led, LOW);    // turn the LED off by making the voltage LOW
  Serial.println("OFF");
  delay(2000);               // wait for a second
}

```


Tot això, com ja he comentat es pot observar al vídeo de la pràctica adjuntat.

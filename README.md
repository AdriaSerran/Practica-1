# Practica-1 LED BLINK

Aquesta pràctica m'ha servit bàsicament per iniciar-me amb l'ESP32 i el Platformio i per a realitzar el meu primer codi involucrant el material esmentat juntament amb un LED.

· Codi

#include <Arduino.h>
int led = 13;

void setup() {                  
  pinMode(led, OUTPUT);     
}

void loop() {
  digitalWrite(led, HIGH);   
  Serial.println("ON");
  delay(1000);               
  digitalWrite(led, LOW);    
  Serial.println("OFF");
  delay(2000);               
}

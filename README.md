# Blinking-Eyes
A simple attempt to blink two LEDs at the same time
using Arduino UNO

void setup()
{
     pinMode(1,OUTPUT);
     pinMode(3,OUTPUT);
     pinMode(5,OUTPUT);
     pinMode(7,OUTPUT);
     pinMode(9,OUTPUT);
}
void loop()
{
     digitalWrite(1,HIGH);
     digitalWrite(3,HIGH);
     delay(1000);
     digitalWrite(1,LOW);
     digitalWrite(3,LOW);
     delay(1000);
     digitalWrite(1,HIGH);
     digitalWrite(5,HIGH);
     delay(1000);
     digitalWrite(1,LOW);
     digitalWrite(5,LOW);
     delay(1000);
     digitalWrite(1,HIGH);
     digitalWrite(7,HIGH);
     delay(1000);
     digitalWrite(1,LOW);
     digitalWrite(7,LOW);
     delay(1000);
     digitalWrite(1,HIGH);
     digitalWrite(9,HIGH);
     delay(1000);
     digitalWrite(1,LOW);
     digitalWrite(9,LOW);
     delay(1000);
}

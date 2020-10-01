# P-LED
Codigo sobre encender un led por un segundo

const int ledPIN = 9;
 
void setup() {
  Serial.begin(9600);    
  pinMode(ledPIN , OUTPUT);  
}
void loop(){
  digitalWrite(ledPIN , HIGH); 
  delay(1000);                   
  digitalWrite(ledPIN , LOW);   
  delay(1000);                   
}

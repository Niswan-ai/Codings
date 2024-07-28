# Codings
nt motorPin = 12;  // declare variable for motor pin

void setup() { // code that only runs once
  pinMode(motorPin, OUTPUT);  // set motor pin as output
}

void loop() {  // code that loops forever
  digitalWrite(motorPin, HIGH);  // turn motor on
  delay(1000); // Wait for 1000 milliseconds
  digitalWrite(motorPin, LOW);  // turn motor off
  delay(1000); // Wait for 1000 milliseconds
}

void setup() {
  // Set pins 2 to 10 as OUTPUT
  for (int i = 2; i <= 10; i++) {
    pinMode(i, OUTPUT);
  }
}

void loop() {
  // Forward direction: from pin 2 to 10
  for (int i = 2; i <= 10; i++) {
    digitalWrite(i, HIGH);
    delay(50);
    digitalWrite(i, LOW);
  }

  // Backward direction: from pin 9 to 3
  for (int i = 9; i >= 3; i--) {
    digitalWrite(i, HIGH);
    delay(50);
    digitalWrite(i, LOW);
  }
}

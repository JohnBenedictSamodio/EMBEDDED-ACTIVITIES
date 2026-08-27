void setup() {
  // put your setup code here, to run once:

}
// Pin assignments
const int BUTTON_PIN = 18;
const int LED_PIN = 23;

void setup() {
  // Configure the button as an input with internal pull-up
  pinMode(BUTTON_PIN, INPUT_PULLUP);

  // Configure the LED as an output
  pinMode(LED_PIN, OUTPUT);

  // Start with the LED OFF
  digitalWrite(LED_PIN, LOW);
}

void loop() {
  // Read the button
  int buttonState = digitalRead(BUTTON_PIN);

  // Button pressed = LOW
  if (buttonState == LOW) {
    digitalWrite(LED_PIN, HIGH);
  }
  // Button released = HIGH
  else {
    digitalWrite(LED_PIN, LOW);
  }
}
void loop() {
  // put your main code here, to run repeatedly:

}

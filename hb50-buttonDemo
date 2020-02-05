void setup()
{
  Serial.begin(115200);
  delay(1000); // give time to bring up the serial monitor
  Serial.print("\nHackerBox FIFTY Button Test\n");
  pinMode(0, INPUT_PULLUP);
  pinMode(16, INPUT_PULLUP);
  pinMode(17, INPUT_PULLUP);
  pinMode(25, INPUT_PULLUP);
  pinMode(26, INPUT_PULLUP);
}

void loop() 
{
  if (digitalRead(0)==LOW)
    Serial.println("Button IO0");
  if (digitalRead(16)==LOW)
    Serial.println("Button A");
  if (digitalRead(17)==LOW)
    Serial.println("Button B");
  if (digitalRead(25)==LOW)
    Serial.println("Button C");
  if (digitalRead(26)==LOW)
    Serial.println("Button D");
  delay(200);  //debounce delay
}

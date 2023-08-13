#define PIN_RED    23 // GPIO23
#define PIN_GREEN  22 // GPIO22
#define PIN_BLUE   21 // GPIO21



void setup() {
  pinMode(PIN_RED,   OUTPUT);
  pinMode(PIN_GREEN, OUTPUT);
  pinMode(PIN_BLUE,  OUTPUT);


}

void loop() {

setColor(128, 0, 0);

delay(200);

setColor(250, 0, 0);

delay(200);

setColor(255, 102, 0);

delay(200);

setColor(255, 255, 0);

delay(200);

setColor(153, 255, 51);

delay(200);

setColor(0, 255, 0);

delay(200);

setColor(0, 255, 255);

delay(200);

setColor(0, 51, 204);

delay(200);

setColor(153, 51, 255);

delay(200);

setColor(255, 51, 204);

delay(200);

}

void setColor(int R, int G, int B) {
  analogWrite(PIN_RED,   R);
  analogWrite(PIN_GREEN, G);
  analogWrite(PIN_BLUE,  B);
}



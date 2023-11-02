#include "SoftwareSerial.h"
#include "DFRobotDFPlayerMini.h"

SoftwareSerial mySoftwareSerial(3, 2);
DFRobotDFPlayerMini myDFPlayer;


void setup() {
  mySoftwareSerial.begin(9600);
  Serial.begin(9600);
  myDFPlayer.begin(mySoftwareSerial);
  myDFPlayer.volume(60);
}

void loop() {
  
  myDFPlayer.play(1);
  myDFPlayer.read();
  delay(3000);
}

## DAY-10(20-05-2023)

(1) ASSIGNMENT

  * DESIGN A LIGHT CONTROLLES STREET LIGHT

[DESIGN A LIGHT CONTROLLES STREET LIGHT TINKER THIS](https://www.tinkercad.com/things/2UDt1eWRvR8)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-20%2012-38-59.png)

PROGRAM
```

// Pin 13 has an LED connected on most Arduino boards.
// give it a name:
int readPhoto;
// the setup routine runs once when you press reset:
void setup() {
  // initialize the digital pin as an output.
  pinMode(13, OUTPUT);
  pinMode(2, OUTPUT);
  
  pinMode(A0, INPUT);
}

// the loop routine runs over and over again forever:
void loop() {
  digitalWrite(13, HIGH);   // turn the LED on (HIGH is the voltage level)
  readPhoto = analogRead(A0);
  
  if (readPhoto < 200) {
  digitalWrite(2, HIGH);
  }
  else{
      digitalWrite(2, LOW);
  }
  
  delay(1);               // wait for a second
  digitalWrite(13, LOW);    // turn the LED off by making the voltage LOW
  //delay(1000);               // wait for a second
}

```

(2) CHAIN

[CHAIN TINKER THIS](https://www.tinkercad.com/things/0oMsMFBWdRj)

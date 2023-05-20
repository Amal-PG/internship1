# 10 DAYS INTERNSHIP (08-05-2023 TO 20-05-2023)

## DAY-1(08-05-2023)

(1) CREATED A GITHUB ACCOUNT

(2) BASIC SYNTAX

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-11%2011-54-30.png)

## DAY-2(09-05-2023)

(1) Blinking a led

[BLINKING A LED TINKER THIS](https://www.tinkercad.com/things/ihqp5M6lnrP)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-09%2013-03-31.png)

(2) Blinking a led using switch

[BLINKING A LED USING SWITCH TINKER THIS](https://www.tinkercad.com/things/b6SKf5j9XoS)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-09%2012-38-53.png)

## DAY 3(11-05-2023)

(1) BLINKING A LED USING AND GATE

[BLINKING A LED USING AND GATE TINKER THIS](https://www.tinkercad.com/things/cRljKIQu8De)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-11%2010-54-36.png)

(2) BLINKING A LED USING ARDUINO

[BLINKING A LED USING ARDUINO TINKER THIS](https://www.tinkercad.com/things/hmC8XKxwG8u)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-11%2011-11-28.png)

PROGRAM
```
// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```

(3) BLINKING TWO LEDS SIMULTAENOUSLY

[BLINKING TWO LEDS SIMULTAENOUSLY TINKER THIS](https://www.tinkercad.com/things/fDNctMWlytC)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-11%2012-51-51.png)

PROGRAM
```
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(13,LOW);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  delay(150); // Wait for 1000 millisecond(s)
  digitalWrite(12,LOW);
  delay(150); // Wait for 1000 millisecond(s)
}
```
(4) LED CHASER

[LED CHASER TINKER THIS](https://www.tinkercad.com/things/6hom0eosdLN)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-11%2015-13-19.png)

PROGRAM
```
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-20%2011-25-50.png
  pinMode(12, OUTPUT);
  pinMode(8, OUTPUT);
  pinMode(7, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(13,LOW);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(12,LOW);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(8, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(8,LOW);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(7, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(7,LOW);https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-18%2011-47-38.png
  delay(100); // Wait for 1000 millisecond(s)
}

```

## DAY-4(12-05-2023)

(1) BLOCKLY

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/blockly%20logic.png)

## DAY-5(15-05-2023)

(1) DRONE

  * INTRODUCTION OF DRONE
  * FEATURES AND PARTS OF DRONE
  * TECHNICAL SPECIFICATION OF ALTITUDE,PROPELER,THRUST,DIAMENTION AND WEIGHT MANAGEMENT   
  
  
(2) WORKING OF ANALOG POTENTIOMETER

[WORKING OF ANALOG POTENTIOMETER TINKER THIS](https://www.tinkercad.com/things/1Gc45ge1orA)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-15%2014-37-43.png)

PROGRAM
```
const int potPin = A0;

void setup() {
  Serial.begin(9600);
}
void loop() {
  int potValue = analogRead(potPin);
  
  Serial.println(potValue);
  delay(100);
}

```

(3) WORKING OF 7 SEGMENT USING ARDUINO

[WORKING OF 7 SEGMENT USING ARDUINO TINKER THIS](https://www.tinkercad.com/things/hsg7qT6yixU)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-16%2009-30-36.png)

PROGRAM

```
// C++ code
//
void setup()
{
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(6, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(8, OUTPUT);
}

void loop()
{
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(8,LOW);
  delay(500);
  digitalWrite(2, LOW);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8,LOW);
  delay(500);
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, LOW);
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, LOW);
  digitalWrite(8, HIGH);
  delay(500);
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, HIGH);
  delay(500);
  digitalWrite(2, LOW);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(500);
  digitalWrite(2, HIGH);
  digitalWrite(3, LOW);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(500);
  digitalWrite(2, HIGH);
  digitalWrite(3, LOW);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(500);
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  delay(500);
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(500);
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(500);
}
```

## DAY-6(16-05-2023)

(1) 3D DESIGNING

[3D DESIGNING TINKER THIS](https://www.tinkercad.com/things/kN0FJZe2jah)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-18%2011-12-56.png)

(2) 3D DESIGN OF A CAR

[3D DESIGN OF A CAR TIKER THIS](https://www.tinkercad.com/things/lcj5wojCtPc)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-18%2011-18-46.png)

## DAY-7(17-05-2023)

(1) VISITED ELECTRICAL LAB & ELECTRONICS LAB

(2) INTRODUCED THE YASKWA ARM ROBOT


## DAY-8(18-05-2023)

(1) ADJUSTING THE SPEED OF THE 7 SEGMENT DISPLAY BY VARING THE POT

[ADJUSTING THE SPEED OF THE 7 SEGMENT DISPLAY BY VARING THE POT TINKER THIS](https://www.tinkercad.com/things/dU7LGxmTGVX)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-18%2011-47-38.png)

PROGRAM

```
// C++ code
//
const int potpin=A0;


void setup()
  
{
  Serial.begin(9600);
  pinMode(13, OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(7,OUTPUT);
}

void loop()
{
  int potValue =analogRead(potpin);
  Serial.println(potValue);
  digitalWrite(13, LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,HIGH);
  delay(potValue); // Wait for 1000 millisecond(s
  digitalWrite(11,LOW);
  digitalWrite(12,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,LOW);
  digitalWrite(10,LOW);
  digitalWrite(8,HIGH);
  digitalWrite(11,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  delay(potValue);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(10,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(12,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(12,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(potValue);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  delay(potValue);
  
   // Wait for 1000 millisecond(s)
}
```

(2) BLINKING A RGB LED

[BLINKING A RGB LED TIKER THIS](https://www.tinkercad.com/things/1r5figIf824)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-20%2011-25-50.png)

PROGRAM

```


// C++ code
//
int ledPinG=8;
int ledPinB=9;
int ledPinR=11;
void setup()
{
  
}

void loop()
{
  
  analogWrite(ledPinB, random(0,255));
  analogWrite(ledPinR, random(0,255));
  analogWrite(ledPinG, random(0,255));            
  delay(1000);
}

```
(3) 3D TRUCK

[3D TRUCK TINKER THIS]https://www.tinkercad.com/things/iesby4ectHd()

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-20%2013-34-18.png)

## DAY-9(19-05-2023)

(1) DESIGNED A PUSHBUTTON LED

[DESIGNED A PUSHBUTTON LED TINKER THIS](https://www.tinkercad.com/things/aW3vBahITyi)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-20%2013-17-14.png)

PROGRAM
```
// C++ code
/// constants won't change. They're used here to set pin numbers:
const int buttonPin = 2;     // the number of the pushbutton pin
const int ledPin =  13;      // the number of the LED pin

// variables will change:
int buttonState = 0;         // variable for reading the pushbutton status

void setup() {
  // initialize the LED pin as an output:
  pinMode(ledPin, OUTPUT);
  // initialize the pushbutton pin as an input:
  pinMode(buttonPin, INPUT);
}

void loop() {
  // read the state of the pushbutton value:
  buttonState = digitalRead(buttonPin);

  // check if the pushbutton is pressed. If it is, the buttonState is HIGH:
  if (buttonState == HIGH) {
    // turn LED on:
    digitalWrite(ledPin, HIGH);
  } else {
    // turn LED off:
    digitalWrite(ledPin, LOW);
  }
}

```

(2) DESIGNED A TRAFFIC SIGNAL LIGHT

[DESIGNED A TRAFFIC SIGNAL LIGHT TINKER THIS](https://www.tinkercad.com/things/8EaKQj5uqs9)

![NO IMAGE(https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-20%2013-09-31.png)

PROGRAM
```
// C++ code
//
// constants won't change. They're used here to set pin numbers:
const int buttonPinR = 2;     // the number of the pushbutton pin
const int ledPinR =  11;      // the number of the LED pin
const int buttonPinO = 3;     // the number of the pushbutton pin
const int ledPinO =  12; 
const int buttonPinG = 4;     // the number of the pushbutton pin
const int ledPinG =  13;  
// variables will change:
int buttonStateR = 0;         // variable for reading the pushbutton status
int buttonStateO = 0;
int buttonStateG = 0;

void setup() {
  // initialize the LED pin as an output:
  pinMode(ledPinR, OUTPUT);
  // initialize the pushbutton pin as an input:
  pinMode(buttonPinR, INPUT);
   pinMode(ledPinO, OUTPUT);
  // initialize the pushbutton pin as an input:
  pinMode(buttonPinO, INPUT);
   pinMode(ledPinG, OUTPUT);
  // initialize the pushbutton pin as an input:
  pinMode(buttonPinG, INPUT);
}

void loop() {
  buttonStateR = digitalRead(buttonPinR);
  buttonStateO = digitalRead(buttonPinO);
  buttonStateG = digitalRead(buttonPinG);
  // read the state of the pushbutton value

  // check if the pushbutton is pressed. If it is, the buttonState is HIGH:
  if (buttonStateR == HIGH) {
    // turn LED on:
    digitalWrite(ledPinR, HIGH);
    digitalWrite(ledPinO, LOW);
    digitalWrite(ledPinG, LOW);
    }
  else if (buttonStateO == HIGH) {
    digitalWrite(ledPinR, LOW);
    digitalWrite(ledPinO, HIGH);
    digitalWrite(ledPinG, LOW);https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-20%2013-09-31.png
    }
  
  else if (buttonStateG == HIGH) {
    digitalWrite(ledPinR, LOW);
    digitalWrite(ledPinO, LOW);
    digitalWrite(ledPinG, HIGH);
    }
  else
  {
    digitalWrite(ledPinR, LOW);
    digitalWrite(ledPinO, LOW);
    digitalWrite(ledPinG, LOW);
    }
    
    
  }   
  
  ```
  
  (3) LCD DISPLAY
  
  [LCD DISPLAY TINKER THIS](https://www.tinkercad.com/things/6SWrCSA1QNl)
  
  ![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-20%2013-27-36.png)
  
  PROGRAM
  ```
  // C++ code
//
// include the library code:
#include <LiquidCrystal.h>

// initialize the library by associating any needed LCD interface pin
// with the arduino pin number it is connected to
const int rs = 12, en = 11, d4 = 5, d5 = 4, d6 = 3, d7 = 2;
LiquidCrystal lcd(rs, en, d4, d5, d6, d7);

void setup() {
  // set up the LCD's number of columns and rows:
  lcd.begin(16, 2);
  // Print a message to the LCD.
  lcd.setCursor(5, 0);
  lcd.print("GPTC");
}

void loop() {
  // set the cursor to column 0, line 1
  // (note: line 1 is the second row, since counting begins with 0):
  lcd.setCursor(2, 1);
  // print the number of seconds since reset:
  lcd.print("KUNNAMKULAM");
}

```

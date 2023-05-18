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
  pinMode(13, OUTPUT);
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
  digitalWrite(7,LOW);
  delay(100); // Wait for 1000 millisecond(s)
}

```

## DAY-4(12-05-2023)

(1) BLOCKLY

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/blockly%20logic.png)

(2) 

## DAY-5(15-05-2023)

(1) DRONE


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

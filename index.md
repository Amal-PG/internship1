# 10 days internship (08-05-2023 TO 20-05-2023)

## DAY-1(08-05-2023)

(1) CREATED A GITHUB ACCOUNT

(2) BASIC SYNTAX

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-11%2011-54-30.png)

## DAY-2(09-05-2023)

(1) Blinking an led

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-09%2013-03-31.png)

(2) Blinking an led using switch

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-09%2012-38-53.png)

## DAY 3(11-05-2023)

(1) BLINKING AN LED USING AND GATE

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-11%2010-54-36.png)

(2) BLINKING AN LED USING ARDUINO

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-11%2011-11-28.png)

PROGRAM-1
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

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-11%2012-51-51.png)

PROGRAM-2

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
(4) BLINKING 4 LEDS SIMULTAENOUSLY

[LED CHASER](https://www.tinkercad.com/things/6hom0eosdLN)

![NO IMAGE](https://github.com/Amal-PG/internship1/blob/main/Screenshot%20from%202023-05-11%2015-13-19.png)

PROGRAM-3
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



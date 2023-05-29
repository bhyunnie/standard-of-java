# 📚 변수
### 목차
+ 변수란
+ 출력문


## 출력문
```java
  System.out.print("Hello");
  System.out.print("world");
  // Hello world
```

```java
  System.out.println("Hello");
  System.out.println("world");
  // Hello
  // world
```

## 변수의 선언과 저장
🔥 변수 (variable) 란 하나의 값을 저장할 수 있는 저장공간
```java
  변수타입 변수이름; // 변수 선언의 기본형
  // e.g )
  int x; // 정수를 담는 x 변수를 선언
  x = 5; // 변수에 값을 저장
  x = 3; // 변수에 새로운 값을 저장 기존의 5는 사라지고 3으로 덮어 씌워진다.
``` 

## 변수의 타입
|분류|변수의 타입|설명|
|------|---|---|
|숫자|int|정수를 저장|
|숫자|long|20억 이상의 정수를 저장|
|숫자|float|오차 없이 7자리 까지의 실수를 저장|
|숫자|double|15자리 까지의 실수를 저장|
|문자|char|문자를 저장하는 타입|
|문자|string|여러 문자를 저장하기 위한 타입|

## 상수와 리터럴
🔥 상수 (constant) 란 하나의 값을 저장할 수 있는 저장공간. 단, 처음 값 대입 이후 다른 값으로의 변경이 안된다.
```java
  final int MENTAL_AGE;
  MENTAL_AGE = 10;
```

🔥 리터럴 (literal) 이란 그 자체로 값을 의미하는 것
```java
  int age = 10;
  final int MENTAL_AGE = 10;
  // age : 변수
  // 10 : 리터럴
  // MENTAL_AGE : 상수
```

### 리터럴의 타입
|종류|리터럴|접미사|
|------|---|---|
|논리형|false,true|없음|
|정수형|123, 2b123, 777, 0xFF, 100L |L|
|실수형|3.14, 3.0e5, 1.4f, 0x1.0p-1|f, d|
|문자형|'A', '1', '\n'|없음|
|문자열|'ABC', '123', 'A', 'true'|없음|

10, 8, 16 진수 표기가 간단하다.
```java
  int octNumber = 011; // 8진수 , 10진수 9
  int hexNumber = 0x11; // 16진수 , 10진수 17
```

JDK 1.7부터 구분자 지원
```java
  int big = 100_000_000;
  long bigLong = 100_000_000_000_000L;
```

float 형은 리터럴에 표시해야하지만 double은 안해도된다.
```java
  float pi = 3.14f;
  dobule pi2 = 3.14d;
  // double pi2 = 3.14; //요것도 가능
```

Char형과 String형의 차이
```java
  char charEg = 'A'; // chat charEg = 'Ahn' 불가능
  char charEg2 = ''; // Error! 반드시 하나의 문자 필요
  String StringEg = 'Ahn'; // O
  String StringEg2 = ''; // O
  String StringEg3 = new String("Ahn"); // String 타입은 하나의 클래스여서 이렇게도 선언은 가능
```
54p 부터 ~ 




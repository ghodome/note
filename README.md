# 수업 내용 필기 //markdown

이 곳에는 수업 내용 필기를 위한 마크다운(Markdown)을 작성하는 방법을 살펴보겠다.

## 랜덤(Random)

랜덤은 뭐가 나올지 예측이 불가능한 값을 말한다.
랜덤을 만드는 방법은 여러 가지가 있다.  
1. Random이라는 도구를 생성하여 사용 - Random r = new Random(a)+b;
2. Math.random() 명령을 사용
3. SecureRandom 도구를 생성하여 사용

//코드를 입력하는 경우가 생긴다.  
여기서는 Random 도구를 생성한다.

//코드블럭 표시
```java
Random r = new Random();
```

이 도구를 사용하기 위해서는 import가 필요하다  
```java
import java.util.Random;
```

import의 경우는 직접 작성하지 않고 *****단축키*****인 `ctrl + shift + o` 를 누른다.

## 랜덤 정수 추첨  
생성한 도구를 이용해서 랜덤한 정수를 추첨할 수 있다.  
단, 생성을 위해서는 범위를 정해야 한다.  
  
- 사람은 범위를 이야기할 때 `a`부터 `b`까지 라고 한다.
- 자바는 범위를 이야기할 때 `a`부터 `b`개 라고 한다.

주요 랜덤 값들의 범위는 다음과 같이 표현될 수 있다.

| 항목 | 범위 |
| :---: | :--- |
| 주사위 | `1`부터 `6`개 |
| 로또 | `1`부터 `45`개 |
| 두자리 정수 | `10`부터 `90`개 |

난수 생성의 원리가 궁금하다면 [위키백과](https://ko.wikipedia.org/wiki/%EB%82%9C%EC%88%98) 여기로  

![카지노](https://www.ramadajeju.co.kr/RamadaPlazaJeju_common/images/homepage/facilities/CASINO03.jpg)

오늘도 이렇게 공부 끝?

![젠장 또 이렇게](./2223.gif)


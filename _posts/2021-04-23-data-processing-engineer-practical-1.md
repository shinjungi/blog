---
title: 2020년 정보처리기사 실기 1회차 기출문제
author: jungi
date: 2021-04-23 13:25:00 +0900
categories: [develop, license]
tags: [license, 정보처리기사]
---

## 2020년 정보처리기사 실기 1회차 기출문제

<br />

(1) 살충제 패러독스의 개념에 관해서 설명하시오.

<p class="post-contents-value">
  동일한 테스트 케이스로 동일한 테스트를 반복하면 더 이상 결함이 발견되지 않으므로 테스트 케이스를 지속적으로 개선해야 한다.
</p>

<br />

(2) 데이터 마이닝의 개념에 대해 서술하시오.

<p class="post-contents-value">
  많은 데이터 가운데 숨겨져 있는 유용한 상관관계를 발견하여, 미래에 실행 가능한 정보를 추출해 내고 의사 결정에 이용하는 과정을 말한다.
</p>

<br />

(3) 프로토콜의 기본요소 3가지를 쓰시오.

<p class="post-contents-value">
  구문(Syntax), 의미(Semantic), 타이밍(Timing)
</p>

> 구문(Syntax): 데이터를 어떻게 구성할지에 대한 형식, 구체적인 코딩 방법, 신호 레벨 등에 대한 형식을 규정.  
> 의미(Semantic): 데이터에 대하여 어떻게 제어할 것인지에 대한 처리 방법과 에러 처리에 대한 방법을 포함.  
> 타이밍(Timing): 데이터를 주고받을 속도에 대한 조절과 여러 데이터가 동시에 통신을 해야할 경우, 순서관리 기법 포함.

<br />

(4) 다음이 설명하는 용어는 무엇인지 쓰시오.

W3C(World Wide Web Consortium)에서 개발되었고, 웹 브라우저 간 호환이 되지 않는 문제와 SGML(Standard Generalized Markup Language)의 복잡함을 해결하기 위해 개발된 다목적 마크업 언어이다.

<p class="post-contents-value">
  XML
</p>

<br />

(5) 속성-값(Attribute-Value Pair)으로 이루어진 데이터 오브젝트를 전달하기 위해 사용하는 개방형 표준 포맷 이다. Ajax(Asynchronous JavaScript and XML)에서 많이 사용되고 XML(eXtensible Markup Language) 을 대체하는 주요 데이터 포맷이다. 언어 독립형 데이터 포맷으로 다양한 데이터 프로그래밍 언어에서 사용 하고 있는 기술은 무엇인가?

<p class="post-contents-value">
  JSON
</p>

<br />

(6) 스케줄링 방식에서 HRN(Highest Response ratio Next) 우선순위 계산식을 쓰시오.

<p class="post-contents-value">
  (대기 시간 + 서비스 시간) / 서비스 시간
</p>

> HRN은 대기 중인 프로세스 중 우선 순위가 가장 높을 것을 선택하는 기법이다.  
> HRN의 우선 순위는 (대기 시간 + 서비스 시간) / 서비스 시간

<br />

(7) 트랜잭션의 특성 중 일관성, 지속성 외 2개의 특성을 쓰시오.

|  속성  | 설명                                                                                    |
| :----: | :-------------------------------------------------------------------------------------- |
| ( 1 )  | 트랜잭션은 연산들을 전부 실행하든지 전혀 실행하지 않아야한다. 일부만 실행해서는 안된다. |
| 일관성 | 트랜잭션이 성공적으로 실행되면 데이터베이스 상태는 모순되지 않고 일관된 상태가 된다.    |
| ( 2 )  | 트랜잭션 실행 도중의 연산 결과는 다른 트랜잭션에서 접근할 수 없다.                      |
| 지속성 | 트랜잭션이 성공했을 경우 영구적으로 반영되어야 한다.                                    |

<div class="post-contents-value">
  <ol> 
    <li>
      원자성
    </li>
    <li>
      독립성
    </li>
  </Ol>
</div>

<br />

(8) 공격자가 패킷의 출발지 주소나 포트를 임의로 변경해 출발지와 목적지 주소를 동일하게 함으로써 공격 대상 컴퓨터의 실행속도를 느리게 하거나 동작을 마비시켜 서비스 거부 상태에 빠지도록 하는 공격 방법은 무엇인가?

<p class="post-contents-value">
  Land Attack(랜드 어택)
</p>

<br />

(9) RFC 1321로 지정되어 있으며, 주로 프로그램이나 파일이 원본 그대로인지를 확인하는 무결성 검사 등에 사용된다. 1991년 로널드 라이베스트(Ronald Rivest)가 예전에 쓰이던 MD4를 대체하기 위해 고안된 128비트 암호화 해시 함수는 무엇인가?

<p class="post-contents-value">
  MD5
</p>

<br />

(10) 다음이 설명하는 제품 패키지 릴리스 노트의 작성 항목은 무엇인가?

문서 이름(릴리스 노트 이름), 제품 이름, 버전 번호, 릴리즈 날짜, 참고 날짜, 노트 버전 등의 정보

<p class="post-contents-value">
  헤더(머리말)
</p>

<br />

(11) LoC(Line of Code)가 30,000라인이고, 개발자가 5명 이며, 개발자가 월평균 300라인을 개발한다. 이때 프로젝트 개발 기간과 계산식을 쓰시오.

<div class="post-contents-value">
  <ul> 
    <li>
      프로젝트 개발 기간: 20개월
    </li>
    <li>
      계산식: (30,000라인 ÷ 300라인) ÷ 5명 = 20개월
    </li>
  </ul>
</div>

<br />

(12) 다음은 공통 모듈 구현의 개념에 대한 설명이다. 괄호 ( )안에알맞은용어를쓰시오.

- 소프트웨어 개발에 있어 기능을 분할하고 추상화하여 성능을 향상시키고 유지보수를 효과적으로 하기 위한 공통 컴포넌트 구현 기법이다.
- 인터페이스 모듈, 데이터베이스 접근 모듈 등 필요한 공통 모듈을 구현한다.
- 모듈간의( 1 )는줄이고,( 2 )는 높은 공통 모듈 구현을 권장하고 있다.

<div class="post-contents-value">
  <ol> 
    <li>
      결합도
    </li>
    <li>
      응집도
    </li>
  </ol>
</div>

<br />

(13) OSI 계층 중 비트를 전송하는 계층은 무엇인가?

<p class="post-contents-value">
  물리 계층
</p>

<br />

(14) 비 정규화(De-Normalization)의 개념을 쓰시오.

<p class="post-contents-value">
  시스템의 성능 향상, 개발 및 운영의 편의성 등을 위해 정규화된 데이터 모델을 통합, 중복, 분리하는 과정으로 의도적으로 정규화 원칙을 위배하는 행위
</p>

<br />

(15) 애플리케이션의 성능을 측정하기 위한 지표는 무엇인가?

| 속성        | 설명                                                                                       |
| ----------- | ------------------------------------------------------------------------------------------ |
| ( 1 )       | 일정 시간 내에 애플리케이션이 처리하는 일의 양                                             |
| ( 2 )       | 애플리케이션에 요청을 전달한 시간부터 응답이 도착할 때까지 걸린 시간                       |
| ( 3 )       | 애플리케이션에 작업을 의뢰한 시간부터 처리가 완료될 때까지 걸린 시간                       |
| 자원 사용률 | 애플리케이션이 의뢰한 작업을 처리하는 동안의 CPU 사용량, 메모리 사용량, 네트워크 사용량 등 |

<div class="post-contents-value">
  <ol> 
    <li>
      처리량(Throughput)
    </li>
    <li>
      응답시간(Response Time)
    </li>
    <li>
      경과시간(Turnaround Time)
    </li>
  </ol>
</div>

<br />

(16) 다음은 모듈의 관계를 나타낸 다이어그램이다. fan-in 개수가 2 이상인 모듈 명칭을 쓰시오.

<img src="https://blog.kakaocdn.net/dn/bIrjh9/btqF8vfSgtL/RcI0N96z6D4HKXLmKDYj5k/img.png" />

<p class="post-contents-value">
  F, J
</p>

> 모듈에서 화살표가 들어오는 경우를 Fan-in, 반대로 나가는 경우를 Fan-out이라고 한다.

<br />

(17) 학생 테이블에 전기과 학생이 50명, 전산과 학생이 100명, 전자과 학생이 50명 있다고 할 때, 다음 SQL문의 실행 결과로 표시되는 튜플의 수를 쓰시오. (단, DEPT 필드는 학과를 의미)

```sql
1. SELECT DEPT FROM STUDENT;
2. SELECT DISTINCT DEPT FROM STUDENT
3. SELECT COUNT(DISTINCT DEPT) FROM STUDENT WHERE DEPT="컴퓨터과"
```

<div class="post-contents-value">
  <ol> 
    <li>
      200
    </li>
    <li>
      3
    </li>
    <li>
      1
    </li>
  </ol>
</div>

<br />

(18) 다음은 C언어 소스 코드이다. 출력 결과를 쓰시오.

```c
#include <stdio.h>
void align(int a[]){
  int temp;
  for (int i = 0; i < 4; i++) for (int j=0; j < 4 - i; j++)
  if (a[j] > a[j+1]){
    temp = a[j];
    a[j] = a[j+1];
    a[j+1] = temp;
  }
}

main(){
  int a[] = { 85, 75, 50, 100, 95 };
  align(a);
  for ( int i = 0; i < 5; i++ ) printf("%d", a[i]);
}
```

<p class="post-contents-value">
  50, 75, 85, 95, 100
</p>

<br />

(19) 다음은 C언어 소스 코드이다. 출력 결과를 쓰시오.

```c
#include <stdui.h>
main(){
  int c = 1;
  switch (3){
    case 1: c += 3;
    case 2: c++;
    case 3: c = 0;
    case 4: c += 3;
    case 5: c -= 10;
    default: c--;
  }
  printf("%d",c);
}
```

<p class="post-contents-value">
  -8
</p>

<br />

(20) 다음 자바 소스 코드이다. 출력 결과를 쓰시오.

```java
public class Test {
  static int[] arr(){
    int a[] = new int[4];
    int b = a.length;
    for(int i = 0; i < 4; i++)
      a[i] = il
      return a;
  }
}

public static void main(String[] args){
  int a[] = arr();
  for(int i = 0; i < a.length; i++)
    System.out.print(a[i] + " ");
}
```

<p class="post-contents-value">
  0 1 2 3
</p>

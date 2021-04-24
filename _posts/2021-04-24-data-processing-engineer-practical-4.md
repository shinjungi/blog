---
title: 2020년 정보처리기사 실기 4회차 기출문제
author: jungi
date: 2021-04-24 14:30:00 +0900
categories: [develop, license]
tags: [license, 정보처리기사]
---

## 2020년 정보처리기사 실기 4회차 기출문제

<br />

(1) 스니핑 정의에 대해 서술하시오.

<p class="post-contents-value">
  네트워크의 중간에서 남의 패킷 정보를 도청하는 해킹 유형의 하나로 수동적 공격 기법에 해당한다.
</p>

<br />

(2) IPv4의 확장형, 대안으로 나온 것으로 128비트 16비트씩 :으로 구분되는 것은?

<p class="post-contents-value">
  IPv6
</p>

<br />

(3) 디자인 패턴에는 생성, 구조, (이것) 이 있다. (이것)은 ?

<p class="post-contents-value">
  행위(Behavioral)
</p>

<br />

(4) 패키지 내부의 사각형이 다른 패키지 내부의 사각형을 import하는 구조 / UML 다이어그램에서 <<import>> order 점선 화살표

<p class="post-contents-value">
  패키지 다이어그램(Package diagram)
</p>

<br />

(5) 데이터베이스 회복(Recovery)기법 중 rollback시 redo, undo가 모두 실행되는 트랜잭션 처리법으로 트랜잭션 수행 중에 갱신 결과를 DB에 즉시 반영한다. 데이터를 변경하면 로그 파일로 저장되며 모든 내용 수정 시 즉시 데이터베이스에 반영된다.

<p class="post-contents-value">
  즉시 갱신 기법
</p>

<br />

(6) 다음 빈 칸에 알맞은 답을 쓰시오

```java
public class Test {
  public static void main(String[] args) {
    int a[] = new int[8];
    int i = 0, n = 10;
    while ( ① ) {
      a[i++] = ②;
      n /= 2;
    }
    for (i=7; i>=0; i--)
      System.out.printf("%d", a[i]);
  }
}
```

<div class="post-contents-value">
  <ul>
    <li>
      n > 0
    </li>
    <li>
      n % 2
    </li>
  </ul>
</div>

<br />

(7) 3행 5열 배열 출력 시 배열 크기 지정하는 문제 (int [][])

```java
public class GisaFirst {
  public static void main(String[] args) {
    int[][] array = new int[①][②];
    int n = 1;
    for (int i=0; i < 3; i++) {
      for (int j=0; j < 5; j++) {
        array[i][j] = j*3 + (i+1);
        System.out.print(array[i][j] + "");
      }
      System.out.printIn();
    }
  }
}
```

<div class="post-contents-value">
  <ul>
    <li>
      3
    </li>
    <li>
      5
    </li>
  </ul>
</div>

<br />

(8) 컴퓨터 네트워킹에서 쓰이는 용어로, IP패킷의 TCP/UDP 포트 숫자와 소스 및 목적지의 IP 주소 등을 재기록 하면서 라우터를 통해 네트워크 트래픽을 주고 받는 기술로 네트워크 주소 변환이라고 한다. 이것은 ?

<p class="post-contents-value">
  NAT
</p>

<br />

(9) 다음의 출력 결과를 쓰시오

```python
lol = [[1,2,3,], [4,5],[6,7,8,9]];
print(lol[0])
print(lol[2][1])
for sub in lol;
for item in sub;
print(item, end="")
print()
```

<div class="post-contents-value">
  <ul>
    <li>
      [1,2,3]
    </li>
    <li>
      7
    </li>
    <li>
      1 2 3
    </li>
    <li>
      4 5 
    </li>
    <li>
      6 7 8 9 
    </li>
  </ul>
</div>

<br />

(10) 온라인 금융 거래 정보를 블록으로 연결하여 P2P 네트워크 분산 환경에서 중앙 관리 서버가 아닌 참여가(peer)들의 개인 디지털 장비에 분산 저장시켜 공동으로 관리하는 방식은 무엇인가?

<p class="post-contents-value">
  블록체인
</p>

<br />

(11) 분산 환경에서 빅 데이터를 저장하고, 처리할 수 있는 자바 기반의 오픈 소스 프레임 워크로, 더그 커팅과 마이크 캐퍼렐라가 개발했으며 구글 맵 리듀스를 대체한다. 이것은 ?

<p class="post-contents-value">
  하둡
</p>

<br />

(12) 데이터베이스 이상 현상 종류 3가지를 쓰시오.

<p class="post-contents-value">
  삽입, 갱신, 삭제
</p>

<br />

(13) 프로세스 상태를 쓰시오. ( 프로세스 상태 전이도 )

<img src="https://woovictory.github.io/img/state_of_process_os.png" />

<p class="post-contents-value">
  준비, 실행, 대기
</p>

<br />
(14) 특정 몇 몇 입력 값들에 대해서만 원하는 결과를 제공해주는 오라클로 전 범위 테스트가 불가한 경우 사용한다. 경계값, 구반 별 예상 값 결과 작성 때 사용한다.

<p class="post-contents-value">
  샘플링 오라클
</p>

<br />

(15) ~60 구간, 60~70구간, 70~80구간, 80~90구간, 90~100 구간 표에서 각 구간마다 하나씩 테스트 데이터가 주어짐

<p class="post-contents-value">
  동치 분할 테스트 (동등 분할 테스트)
</p>

<br />

(16) SQL: where 쓰지말 것, group by 쓸 것, 집계함수 사용할 것, AS(alias)사용할 것, 세미콜론(;)생략 가능,인용 필요시 '사용

\* 결과 테이플

| 학과   | 학과별 튜플수 |
| ------ | ------------- |
| 전기   | 1             |
| 컴퓨터 | 2             |
| 전자   | 2             |

<div class="post-contents-value">
  SELECT 학과, COUNT(학과) AS '학과별튜플수' FROM 학생 GROUP BY 학과;
</div>

<br />

(17) 1960년대 말에 미국 AT&T벨(Bell) 연구소에서 개발한 운영체제로 거의 C언어로 구현한다. 구조적 파일 시스템, 시스템의 파일이 하나의 트리 구조를 가지는 이것은 ?

<p class="post-contents-value">
  유닉스
</p>

<br />

(18) 다음 소스 코드의 실행결과를 쓰시오.

```c
char *p = ""KOREA"";
printf(""%s\n"",p);
printf(""%s\n"",p+3);
printf(""%c\n"",*p);
printf(""%c\n"",*(p+3));
printf(""%c\n"",*p+2);
```

<div class="post-contents-value">
  <ol>
    <li>
      KOREA
    </li>
    <li>
      EA
    </li>
    <li>
      K
    </li>
    <li>
      E
    </li>
    <li>
      M
    </li>
  </ol>
</div>

<br />

(19) 다음 소스 코드의 실행 결과를 쓰시오.

```java
class Parent {
  int compute(int num) {
    if(num <= 1) return num;
    return compute(num-1) + compute(num-2);
  }
}

class Child extends Parent {
  int compute(int num){
    if( num <= 1) return num;
    return compute(num-1) + compute(num-3);
  }
}

class Test {
  public static void main (String[] args){
    Parent obj = new Child();
    System.out.print(obj.compute(4));
  }
}
```

<p class="post-contents-value">
  1
</p>

<br />

(20) 보안 요소 중 가용성에 대해서 약술하시오.

<p class="post-contents-value">
  권한을 가진 사용자나 애플리케이션이 원하는 서비스를 지속적으로 사용 할 수 있도록 보장하는 특성이다.
</p>

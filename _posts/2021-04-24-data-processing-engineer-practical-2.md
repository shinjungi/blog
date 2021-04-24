---
title: 2020년 정보처리기사 실기 2회차 기출문제
author: jungi
date: 2021-04-24 09:32:00 +0900
categories: [develop, license]
tags: [license, 정보처리기사]
---

## 2020년 정보처리기사 실기 2회차 기출문제

<br />

(1) 한국 아이티 보안 관제실에서 근무한다. 정보 시스템 운영 중 서버가 다운 되거나 자연 재해, 시스템 장애 등의 이유로 대고객 서비스가 불가능한 경우가 종종 발생한다. 이와 같은 상황에서의 "비상사태 또는 업무중단 시점부터 업무가 복구되어 다시 정상가동 될 때까지의 시간"을 의미하는 용어를 쓰시오.

<p class="post-contents-value">
  목표 복구 시간(RTO - Recovery Time Objective)
</p>

<br />

(2) 다음은 Python으로 작성된 코드이다, 코드의 실행 결과를 적으시오.

```python
asia={"한국","중국","일본"}
asia.add("베트남")
asia.add("중국")
asia.remove("일본")
asia.update(["홍콩","한국","태국"])
print(asia)
```

<p class="post-contents-value">
  {"한국", "중국", "베트남", "태국}
</p>

<br />

(3) 자바스크립트를 사용한 비동기 통신기술이자, 클라이언트와 서버간의 XML 데이터를 주고받는 기술로, 브라우저가 가지고 있는 XML HTTPRequest 객체를 이용해서 전체 페이지를 새로 고치지 않고도 페이지의 일부만을 위한 데이터를 로드하는 기법은?

<p class="post-contents-value">
  AJAX(Asynchronous Javascript And XML)
</p>

<br />

(4) 고객의 요구 변화에 유연하고도 신속하게 대응하는 개발 방법론으로, 이와 반대되는 개념이 전통적 개발 방법론으로, 이와 반대되는 개념이 전통적 개발 방법론이라할 "워터폴(Water fall)"방식이다. 최근 이용어는 소프트웨어 개발에 국한 되지 않고 조직과 사업 등 기업경영 전반으로 사용범위가 확산되고 있는 개발 방법론은 무엇인가?

<p class="post-contents-value">
  애자일 방법론
</p>

<br />

(5) 다음 Java언어로 구현한 프로그램을 분석하여 빈칸에 들어갈 것을 적으시오.

```java
<출력 결과>
Child

class Parent {
  public void draw(){
    system.out.printIn("Parent")
  }

  class Child extends Parent {
    public void draw() {
      system.out.printIn("Child")
    }
  }

  public class Test {
    public static void main(String[] args){
      Parent a = ( ) child();
      a.draw();
    }
  }
}
```

<p class="post-contents-value">
  new
</p>

<br />

(6) 다음 조건처리에 유의하여 SQL문을 작성하시오.

```
1) 학생 테이블에서 3학년, 4학년에 해당하는 학번과 이름을 검색하시오.
2) 조건식에는 IN함수를 사용하시오 (이때 학년의 데이터 타입은 INT)
```

<p class="post-contents-value">
  SELECT 학번, 이름 FROM 학생 WHERE 학년 IN (3,4);
</p>

<br />

(7) 데이터 제어어인 DCL의 종류로는 COMMIT, ROLLBACK, GRANT등이 있다. 이 중 ROLLBACK에 대해 서술하시오.

<p class="post-contents-value">
  트랜잭션의 실패로 작업을 취소하고, 이전 상태로 되돌리는 데이터 제어어
</p>

<br />

(8) IP계층에서 무결성과 인증을 보장하는 인증헤더와 기밀성을 보장하는 암호화를 이용한 IP보안 프로토콜로, 현재 전세계에서 사용되는 인터넷 상거래시 요구되는 개인 정보와 크레디트 카드 정보의 보안 유지에 가장 많이 사용되고 있는 프로토콜은 무엇인가?

<p class="post-contents-value">
  IPsec
</p>

<br />

(9) ( )란 프로그램을 실행하지 않고 분석하는 방법으로, 소스 코드에 대한 코딩 표준, 코딩 스타일, 코드 복잡도 및 남은 결함 등을 발견하기 위해 사용되는 테스트 자동화 도구가 있다. ( )안에 들어갈 용어는 무엇인가?

<p class="post-contents-value">
  정적 분석 도구
</p>

<br />

(10) 객체의 상태가 바뀌면 그 객체에 의존하는 다른 객체들한테 알림이 가고 자동으로 내용이 갱신되는 방식으로 일대다(one-to-many) 의존성을 가지는 디자인 패턴으로, 느슨하게 결합(Loose coupling)하는 디자인 패턴, 일대 다의 관계로서 일부 객체가 변경되면 다른 부분이 이를 인지하여 변화하는 패턴은 무엇인가? ( 영문 Full-name으로 기술하시오)

<p class="post-contents-value">
  Observer
</p>

<br />

(11) 휴대 전화를 비롯한 휴대용 장치를 위한 운영 체제와 미들웨어, 사용자 인터페이스 그리고 표준 응용 프로그램(웹 브라우저, 이메일 클라이언트, 단문 메시지 서비스SMS, MMS등)을 포함하고 있는 소프트웨어 스택이자 리눅스 모바일 운영 체제이다. 개발자들이 자바와 코틀린 언어로 응용 프로그램을 작성할 수 있게 하였으며, 컴파일된 바이트코드를 구동할 수 있는 런타임 라이브러리를 제공한다.

<p class="post-contents-value">
  안드로이드
</p>

<br />

(12) SQL 인덱스 작성 - student 테이블의 name 속성에 idx_name 이름의 인덱스를 생성하는 문장을 작성하시오.

<p class="post-contents-value">
  CREATE INDEX idx_name ON student(name);
</p>

<br />

(13) 일반적으로 널리 알려진 HTTP, HTTPS, SMTP등을 통해 XML기반의 메시지를 컴퓨터 네트워크 상에서 교환하는 프로토콜로, envelop/header/body로 이루어진 구조를 가져 인터넷 애플리케이션 계층에 있는 프로토콜을 전송 계층의 프로토콜로 사용할 수 있게 만드는 프로토콜은?

<p class="post-contents-value">
  SOAP
</p>

> 웹 서비스 방식에서 파일 전송은 HTTP 기반의 SOAP를 사용하여 송수신한다.  
> SOAP대신 RESTful 프로토콜로 대체할 수 있다.

<br />

(14) 보안 공격 중 SQL Injection에 대해서 서술하시오.

<p class="post-contents-value">
  웹 응용 프로그램에 강제로 SQL 구문을 삽입하여 내부 데이터베이스 서버의 데이터를 유출 및 변조하고 관리자 인증을 우회하는 공격기법
</p>

<br />

(15) ( )안에 들어갈 용어를 쓰시오.

| 직관성 |누구나 쉽게 이해하고 쉽게 사용할 수 있어야 한다|
| ( ) | 정확하고 완벽하게 사용자에게 목표가 달성될 수 있도록 제작|
| 학습성 | 초보와 숙련자 모두가 쉽게 배우고 사용할 수 있도록 제작|
| 유연성 | 사용자의 인터랙션을 최대한 포용하고, 실수를 방지할 수 있도록 제작|

<p class="post-contents-value">
  유효성
</p>

<br />

(16) 유닉스/리눅스 환경에서 사용자에게는 읽기/쓰기/실행, 그룹에게는 읽기/실행, 기타에는 실행 권한을 a.txt에 부여하는 명령어를 8진법을 사용해서 한 줄로 쓰시오.

```
사용자에게 읽기 쓰기 실행 권한 부여
그룹에게 읽기, 실행 권한 부여
그 외에게 실행 권한 부여
```

<p class="post-contents-value">
  chmod 751 a.txt
</p>

<br />

(17) 아래 설명에 해당하는 용어를 적으시오. (영어 Full-name으로 작성하시오)

웹상에 존재하는 데이터를 개별 URL로 식별하고, 각 URI에 링크정보를 부여함으로써 상호 연결된 웹을 지향하는 모형이다.  
링크 기능이 강조된 시멘틱 웨의 모형에 속한다고 볼 수 있으며 팀버너스 리의 W3C를 중심으로 발전하고 있다.  
이것은 4가지 원칙을 만족한느 데이터 모형이다.

1. URI의 사용: 웹 문서의 위치를 나타내는 URI중심의 식별체계를 지향한다. 즉, 개별 문서에 존재하는 개별 객체에 각각 URI를 부여하는 것이다.
2. HTTP URI의 사용: URI중에서도 HTTP 프로토콜을 통해 접근할 수 있는 URI를 제안하고 있다. 이는 Linked Data에 대한 접근성을 강화하려는 목적이다.
3. RDF의 사용: RDF와 같이 트리플 모형으로 구조화된 데이터를 사용해야 한다. 웹의 데이터를 정형화된 구조로 나타내고, 연계하기 위해서이다.
4. 링크 정보의 부여: 보다 발전된 시멘틱 웹을 위해 링크 정보를 부여하는 것이 매우 중요하다.
   Linked data와 Open data를 결합한 용어이다.

<p class="post-contents-value">
  Linked Open Data
</p>

<br />

(18) 아래 보기를 보고, 빈칸에 맞는 단어를 적으시오

```
보기 : 개념적 설계, 논리적 설계, 물리적 설계
요구사항 분석 -> ( ) -> ( ) -> ( ) -> 구현
```

<p class="post-contents-value">
  요구사항 분석 -> ( 개념적 설계 ) -> ( 논리적 설계 ) -> ( 물리적 설계 ) -> 구현
</p>

<br />

(19) 다음 Java언어로 구현한 프로그램을 분석하여 그 실행 결과를 쓰시오.

```java
class A {
  int a;
  a(int a){
    this.a = a;
  }
  void display(){
    system.out.printIn("a="+a);
  }
}

class B extends A {
  B(int a){
    super(a);
    super.display();
  }
}

main(){
  B obj = new B(10);
}
```

<p class="post-contents-value">
  a=10
</p>

<br />

(20) 다음 빈칸에 들어갈 용어를 적으시오

```
소프트웨어 ( )는 변경제어, 개발 전반 산출물에 대하여 관리한다. 관리 도구로 Git, SvN등이 있다.
```

<p class="post-contents-value">
  형상 관리
</p>

<br />

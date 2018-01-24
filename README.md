### Java로 hello world를 출력하는 main 메소드를 작성하시오.

> 정답률 30%

- main 메소드를 작성할 줄 아는 것은 이 분야에 발을 담그는 것에 대한 최소한의 예의(?)라고 생각해서 출제
- 약간의 오타는 감안할 수 있으나 public static void main은 절대로 틀리면 안 됨

------

### alz로 압축을 하거나, hwp로 문서를 작성하여 외국에 전송하면 안 되는 이유를 설명하시오.

> 정답률 90%

- 외국에서 사용하지 않는다 혹은 표준이 아니라는 등의 답변을 쓰면 정답으로 인정

------

### for문을 사용하여 1에서 10까지의 합을 구하는 프로그램을 작성하시오. (main 메소드 불필요)

> 정답률 60%

- 기초적인 문법을 숙지하고 있는지 평가
- 대부분 부호를 잘못 써서 틀림 (1에서 10까지 더하라면 0<=10 또는 0<11로 써야 함)
- 변수 선언을 하지 않아도 정답으로 인정함

------

### 다음은 javadoc의 String.replaceAll 메소드에 대한 설명이다. 우리말로 해석하시오.

> 정답률 15%

Replaces each substring of this string that matches the given regular expression with the given replacement.

- 영어로 된 문서를 보고 이해할 수 있는지 평가
- 정규표현식의 번역을 몰라서 regular expression으로 그대로 둬도 정답으로 인정

------

### 리눅스를 설치해보신 적이 있습니까? 설치해 본 제품명을 기술하시오. 또한 어떠한 용도로 사용해 보았는지 기술하시오.

> 정답률 40%

- 종류와 버전을 불문하고 리눅스를 설치해본 경험이 있다고 하면 정답으로 인정
- OS 경험도 점수로 인정하는 편이 좋다고 생각했음

------

### 다음 빈칸을 채우시오.

(-----------------------) is a programming paradigm that uses "objects" – data structures consisting of data fields and methods together with their interactions – to design applications and computer programs. Programming techniques may include features such as data abstraction, encapsulation, modularity, polymorphism, and inheritance. Many modern programming languages now support (-----------------------)

> 정답률 20%

- 한글로 "객체지향프로그래밍" 또는 OOP로 쓰면 정답으로 인정
- 두 항목에 다른 대답을 쓰는 경우도 있었는데 그 경우 부분 점수를 인정

------

### 다음 주어진 div의 클래스를 정의하시오.

##### - 너비가 250px이고 높이가 300px이며, 배경색이 검은색인 hello 클래스

```
<div class="hello">안녕하세요</div>
<style type="text/css">
.hello {



}
</style>
```

> 정답률 25%

- 기초적인 CSS 문법을 알고 있는지 평가
- background나 background-color 모두 정답

------

### 세션과 쿠키의 차이점에 대해 간략히 설명하시오.

> 정답률 30%

- 서버와 클라이언트 차이에 대해 서술하면 정답으로 인정
- 라이프 사이클에 대한 설명이 있다면 금상첨화
- 세션이 보안적으로 안전하다는 데에는 이견이 있으나, 여기서는 그렇게 기술해도 정답으로 인정

------

### 다음 소스코드를 읽고 무엇을 하는 프로그램인지 서술하시오.

```
char[] arr = someString.toCharArray(); // 해당 문자열로부터 캐릭터 배열을 선언한다
StringBuffer sb = new StringBuffer();
int size = 0;
for(char c : arr) {
    size += (c > 255) ? 2 : 1; // 조건에 따라 2 또는 1을 증가시킨다
    sb.append(c);
    if(size >= 80) {
        break;
    }
}
return sb.toString();
```

> 정답률 10%

- char의 타입을 이해하고 있는지 평가
- 남이 짠 소스 코드를 읽을 수 있는지를 평가 (코드 리딩)
- 이 소스는 온전한 소스가 아니나 일부러 간략하게 만들었음

------

### 다음 javascript 소스코드가 어떻게 동작할지 서술하시오.

```
function f() {
    for ( var i = 0; i < 3; i++ ) {
        setTimeout( function() {
            alert( i );
        }, 1000);
    }
}
f(); // f를 실행한다
```

> 정답률 0%

- timer나 클로저를 이해하고 있는지 평가
- 이 문제는 일종의 덤임(신입 레벨에서 맞출 수 있는 사람이 있으리라고 기대하지 않음)
- 기대하지 않았다고 해도 이 문제를 대하는 태도와 답변에서 지원자의 많은 부분을 엿볼 수 있었음

------

### 다음 조건을 만족하는 SQL 질의문을 작성하시오.

사원번호(emp.seq), 이름(emp.name), 부서명(dept.name) 컬럼이 매핑되며, **모든 사원**이 전부 출력되어야 함

```
emp 테이블
------------------
seq | name | dept_seq
1 | 홍길동 | 2
2 | 죠나단 | 1
3 | 죠스타 | null

dept 테이블
------------------
seq | name
1 | 개발부
2 | 운영부

```

> 정답률 10%

- left outer join 문법을 이해하고 있는지 평가

### API란 ?

응용 프로그램에서 사용할 수 있도록, 운영체제나 프로그래밍 언어가 제공하는 기능을 제어할 수 있게 만든 인터페이스를 뜻한다.

----

### 쿠키와 세션

쿠키는 자기 자신이 가지고 있고

- 키워드, 검색어 등등

세션은 서버에 넣어주는 것

- 세션은 해쉬 구조
- 중요한 것들을 넣어서 보관함 ex) 개인정보

#### 좀더 자세하게 알아보자 !

먼저 쿠키와 세션은 HTTP 프로콜의 약점을 커버하기 위해서 존재함.

HTTP 프로토콜은 Connectionless하고 Stateless하다라고 이야기함.

무슨 이야기냐?

- Connectionless: 클라이언트가 request를 서버에 보내면, 서버는 클라이언트에게 response를 하면 서로 접속을 끊는 특성.


- Stateless: 접속을 끝는 순간 클라이언트와 서버의 통신은 끝나고 상태 정보는 유지하지 않는 특성

이 두가지 특성이 장점이자 약점이 된다 !

장점은 통신을 유지하고 있으면 드는 모든 리소스 낭비를 줄일 수 있지만 !

But 통신을 할때마다 계속 내가 누구라는 인증을 해야함 ! 

그래서 ! 우리는 쿠키와 세션을 이용해서 해결함 !

#### 1. 쿠키

- 클라이언트에 저장되는 키와 값이 들어있는 작은 데이터 파일
- 쿠키는 이름, 값, 만료 날짜(쿠키 저장기간), 경로 정보가 들어있다.
- 쿠키는 일정 시간동안 데이터를 저장할 수 있어서 로그인 상태를 유지함.
- 쿠키는 클라이언트의 상태 정보를 본인 하드 디스크에 저장하였다가 필요할 때 참조, 재사용함.

#### 1. 2) 쿠키의 사용 예

- 방문 사이트에서 아이디와 비밀번호를 저장하시겠습니까? 라고 나타나는 것은 쿠키로 저장하겠냐 라는 뜻
- 팝업이 나타날때 "오늘 이 창을 보지 않음"을 누르면 오늘 그 창이 뜨지 않는 것.

#### 1.3) 쿠키의 제약조건

- 클라이언트에 총 300개까지 쿠키를 저장할 수 있음 !
- 하나의 도메인 당 20개의 값만 가질 수 있음 !
- 하나의 쿠키 값은 4MB까지 저장 가능 !

### 2. 세션

- 세션은 클라이언트와 웹 서버간 네트워크 연결이 지속 유지되고 있는 상태
- 즉, 사용자가 브라우저를 열어 서버에 접속한 뒤 접속을 종료할 때 시점까지를 말함.
- HTTP 프로토콜은 비접속형 프로토콜이므로, 매 접속시마다 새로운 네트워크 연결이 이루어지는데, 세션이 연결유지를 가능하게 해줌.
- 클라이언트가 웹서버에 Request를 보내면, 해당 서버의 엔진이 클라이언트에게 유일한 ID를 부여, 이 ID를 세션이라고 부름
- 세션 ID는 임시로 저장하여 페이지 이동 시 이용하거나, 클라이언트가 재 접속 했을 때 클라이언트를 유일하게 구분하는 수단.

#### 2.2) 세션의 장점

- 각 클라이언트에게 고유 ID를 부여함 (정확한 구분)
- 세션 ID로 클라이언트를 구분해서 클라이언트의 요구에 맞는 서비스를 제공
- 서버에서 클라이언트롤 발급해준 세션 ID를 쿠키를 사용해서 저장
- 클라이언트는 다시 접속시, 이 쿠키를 이용해서 세션 ID값을 서버에 전달함.

#### 2.3) 세션의 단점

- 서버에 저장되는 세션때문에 서버에 처리를 요구하는 부하와 저장 공간을 필요함.

#### 2.4) 사용 예

- 로그인과 같이 보안상 중요한 작업은 세션을 통해서 작동함. 

#### 쿠키와 세션의 차이점

기본적으로 쿠키와 세션은 비슷한 역할을 함, 동작원리 또한 비슷, 왜냐하면 세션도 결국 쿠키로 저장해서 사용하기 때문이다.

그러나 큰 차이점은 저장되는 위치. 쿠키는 클라이언트에 저장되어서 보내는 역할을하고, 세션은 서버에 저장되어서 클라이언트에게 알려줘서 사용함. 

쿠키는 서버의 자원을 전혀 사용하지 않으며 클라이언트 단에서 저장을 해서 사용. 

세션은 서버에 저장되어서 그 고유한 ID를 가지고 있음. 그래서 서버의 자원을 사용

쿠키와 세션은 서버의 자원을 사용할 수 있음. 쿠키와 세션의 만료되는 기간도 다름.

쿠키는 클라이언트에 저장되어서 서버에 요청시 빠른 속도를 보냄. 세션은 서버에 정보가 있기때문에 서버의 처리가 필요해서 쿠키보다 느린 속도.

#### 보안성이 낮은 Cookie 대신 Session을 사용하면 되는데 안하는 이유?

A. 모든 정보를 **Session에 저장하면 Server의 메모리를 과도하게 사용하게 되어 Server에 무리**가 감

---

### 네트워크 전송 Get, Post 비교

GET, POST 방식의 request는 서버로 본인이 가지고 있는 data를 전달하기 위해 사용.

#### GET 방식

- 클라이언트로 입력한 query의 이름과 값이 결합되어 스트링 형태로 서버에 전달.
- <FROM>TAG의 METHOD 속성의 값으로 GET을 입력함
- DB에 추가로 정보를 처리하지않고, 저장된 Data를 단순 요청하는 정도로 사용
- Dependancy: POST<GET
- URL에 그대로 query의 이름과 값이 같이 연결되어 표현

#### POST방식

- 클라이언트와 서버 간에 인코딩하여 서버로 전송
- 헤더를 통해 요청이 전송되는 방식
- <FORM>TAG의 METHOD 속성의 값으로 POST를 입력
- 한번 요청시 데이터양은 제한 없음
- DB에 추가로 서버에서 갱신 작업을 할때, 서버에서 정보가 가공되어 응답하는 경우에 사용
- Dependancy : Post>Get
- 클라이언트에서 데이터를 이코딩 -> 서버측에서 디코딩해서 사용
- Query는 body안에 들어가 있어서 보안에 조금 유리함.

---

### 2. ORM(객체 관계 매핑) 이란 ? (Object-Relational Mappings)

**(ruby에서 대표적인건 datamapper)**

ORM이라는 것을 단순하게 표현해보자면 객체와 관계와의 설정? 정도일까? 그럼 여기서 말하는 객체라는 것은 우리가 흔히 말하는 OOP(Object-Oriented Programming)의 그 객체를 이야기 하는 것 이라면, 과연 관계라는 것이 의미하는 것은 무엇일까? 뭐 지극히 기초적인 이야기지만 우리(개발자)가 흔히 사용하고 있는 관계형 데이터베이스를 의미한다.

#### 결론 ! 코드를 통해서 데이터베이스를 조작하는 것 ! SQL을 사용하지 않고 !

####장점 [#](http://www.incodom.kr/ORM#h_ad297d8f97c26a598b96a9fde03f7b73)

- 객체 지향적인 코드로 인해 더 직관적이고 비즈니스 로직에 더 집중할 수 있게 도와준다.
  - 선언문, 할당, 종료 같은 부수적인 코드가 없거나 급격히 줄어든다.
  - 각종 객체에 대한 코드를 별도로 작성하기 때문에 코드의 가독성을 올려준다.
  - SQL의 절차적이고 순차적인 접근이 아닌 객체 지향적인 접근으로 인해 생산성이 증가한다.
- 재사용 및 유지보수의 편리성이 증가한다.
  - ORM은 독립적으로 작성되어있고, 해당 객체들을 재활용 할 수 있다.
  - 때문에 모델에서 가공된 데이터를 컨트롤러에 의해 뷰와 합쳐지는 형태로 디자인 패턴을 견고하게 다지는데 유리하다.
  - 매핑정보가 명확하여, ERD를 보는 것에 대한 의존도를 낮출 수 있다.
- DBMS에 대한 종속성이 줄어든다.
  - 대부분 ORM 솔루션은 DB에 종속적이지 않다.
  - 종속적이지 않다는것은 구현 방법 뿐만아니라 많은 솔루션에서 자료형 타입까지 유효하다.
  - 프로그래머는 Object에 집중함으로 극단적으로 DBMS를 교체하는 거대한 작업에도 비교적 적은 리스크와 시간이 소요된다.
  - 또한 자바에서 가공할경우 equals, hashCode의 오버라이드 같은 자바의 기능을 이용할 수 있고, 간결하고 빠른 가공이 가능하다.

####단점 [#](http://www.incodom.kr/ORM#h_db739aa439489091d2ff2f1ca5c004ec)

- 완벽한 ORM 으로만 서비스를 구현하기가 어렵다.
  - 사용하기는 편하지만 설계는 매우 신중하게 해야한다.
  - 프로젝트의 복잡성이 커질경우 난이도 또한 올라갈 수 있다.
  - 잘못 구현된 경우에 속도 저하 및 심각할 경우 일관성이 무너지는 문제점이 생길 수 있다.
  - 일부 자주 사용되는 대형 쿼리는 속도를 위해 SP를 쓰는등 별도의 튜닝이 필요한 경우가 있다.
  - DBMS의 고유 기능을 이용하기 어렵다. (하지만 이건 단점으로만 볼 수 없다 : 특정 DBMS의 고유기능을 이용하면 이식성이 저하된다.)
- 프로시저가 많은 시스템에선 ORM의 객체 지향적인 장점을 활용하기 어렵다.
  - 이미 프로시저가 많은 시스템에선 다시 객체로 바꿔야하며, 그 과정에서 생산성 저하나 리스크가 많이 발생할 수 있다.

---

###  심볼과 String의 차이

즉, 심볼도 객체이며, 문자열도 객체입니다. 그러나 symbol은 변경이 불가능(immutable)한 객체입니다. 다시말해, 심볼은 한번 값이 assign 되고 나면 값을 변경하는 것이 불가능합니다. 그렇다고 해서 객체자체가 Java의 final 선언된 변수와 같이 덮어쓸 수도 없다는 의미는 아닙니다. Immutable 이란, 객체가 가지고 있는 값을 변경(change)할 수는 없지만 덮어쓰기(overwrite)할 수는 있다는 의미입니다.

문자열은 변경이 가능(mutable) 하기 때문에, 루비 인터프리터는 실제 해당 문자열이 어떤 값을 가지고 있는지 실행시점까지 알 수 가 없습니다. 이것은 다시말해, 우리가 보기에는 동일한 문자열도 서로 다른 메모리 공간을 차지하고 있어야 한다는 의미입니다.

### 결론

루비에서 대부분의 경우 심볼을 문자열을 사용하는 경우보다 메모리 효율성이나 성능 측면에서 유리합니다. 이러한 이유로 hash의 키 등으로 문자열을 사용하는 것보다 심볼을 사용하는 것이 좋습니다.

대부분의 루비 개발자들은 해시의 키로 심볼을 사용하는 것이 익숙하지만, 왜 그렇게 해야하는지, 문자열 대신 심볼을 사용하는 것이 어떤한 면에서 유리한지는 한번 기억해 두는 것이 좋습니다.

---

### Socket이란 ?

- TCP/IP로 통신을 행하는 컴퓨터가 가지는 네트워크 내에서의 주소에 해당하는 IP어드레스와, IP어드레스의 서브 어드레스인 포트 번호를 조합한 네트워크 어드레스를 말한다.


- 소켓은 네트워크 상에서 클라이언트 프로그램과 서버 프로그램 사이의 통신 방법이다. 소켓은 "접속의 끝 부분"으로 정의된다.


- 소켓이란 네트워크상에서 서버와 클라이언트 두 개의 프로그램이 특정 포트를 통해 양방향 통신이 가능하도록 만들어주는 소프트웨어 장치라 말할 수 있다.

종합해보면, socket은 IP 어드레스와 포트 넘버가 합쳐진, 네트워크 상에서 서버 프로그램과 클라이언트 프로그램이 통신을 할 수 있도록 해주는 소프트웨어 장치.

---

### 채널 

채널은 일종의 게이트웨이이다. 기존의 파일이나 소켓 등에서 사용하던 스트림이 네이티브 IO 서비스를 이용할 수 있도록 도아주는 메소드를 제공한다. 하지만 채너은 기존의 스트림과 구별되는 몇 가지 큰 차이점이 존재한다. 채널은 데이터를 보내거나 데이터를 받기 위한 타겟으로 ByteBuffer를 사용한다는 점이다. ByteBuffer를 사용함으로써 직간접적으로 여러 가지 다양한 네이티브 서비스를 이용할 수 있기 때문이다. 

또 이렇게 채널을 통해 데이터를 주고 받으면, 운영체제 수준의 네이티브 IO 서비스들을 직간접적으로 이용할 수 있다는 점이다. 따라서 기본적으로 채널을 통한 IO 통신은 기존의 스트림보다 좀더 효율적이고 기존에 지원되지 않았던 메모리 맵 파일, 파일 락킹 같은 기능들도 이용할 수 있게 된다.

마지막으로 채널은 스트림과 달리 단방향 뿐만 아니라 양방향 통신도 가능하다. 항상 양방향 통신을 이용할 수 있는 것은 아니지만 소켓 채널의 경우 별다른 설정 없이 양방향 통신이 가능하지만 파일 챈ㄹ의 경우에는 그렇지 않다.

---

### HTML DOCTYPE 선언이유

HTML은 버전 별로 지원하는 태그가 조금씩 다르다. 그래서, HTML이 어떤 버전으로 작성되었는지 미리 선언해, 웹브라우저가 내용을 올바로 표시할 수 있도록 해주는 것이 <!DOCTYPE>이다 ! 

유형에 따라 마크업 문서의 요소와 속성등을 처리하는 기준이 되며 유효성 검사에 이용된다.

---

### MVC 패턴

#### MVC란?

- 객체지향프로그래밍에서, MVC란 사용자 인터페이스를 성공적이며 효과적으로 데이터 모형에 관련 시키기 위한 방법론 또는 설계 방식중 하나이다. MVC방식은 자바, Smalltalk,
- MVC 패턴은 목적 코드의 재사용에 유용한 것은 물론, 사용자 인터페이스와 응용프로그램 개발에 소요되는 시간을 현저하게 줄여주는 형식이라고 많은 개발자들이 평가하고 있다.

#### MVC 구성요소

**Model** 

- 소프트웨어 응용과 그와 관련된 고급 클래스 내의** 논리적 데이터 기반 구조를 표현**. 이 목적 모형은 사용자 인터페이스에 관한 어떠한 정보도 가지고 있지 않다.

**View **

- 사용자 인터페이스 내의 구성요소들을 표현(**사용자에게 보여지는 화면**)

**Controller **

- Model과 View를 연결하고 있는 클래스를 대표, **Model과 View 내의 클래스들 간 정보 교환**하는데 사용.

---

### HTTP란? (Hyper Text Transfer Protocol)

HTTP 는 브라우저가 웹 서버와 통신하기 위해 사용하는 주요 프로토콜이다. HTTP 4가지 요청 형식은 아래와 같다.

- GET : 문서를 요청. 서버가 클라이언트에 상태 정보와 복제된 문서를 보냄으로써 응답을 함. (조회)
- HEAD : 상태 정보를 요청. GET 과 동일한 형태로 응답을 하지만, 문서를 복제하지는 않는다.
- POST : 데이터를 서버로 송신. 서버는 해당 데이터를 특정 아이템에 덧붙인다. (생성)
- PUT : 데이터를 서버로 송신. 서버가 특정 아이템을 완전히 대체한다. (수정)

---

### 브라우저에서 캐싱하기

웹 페이지 성능을 최적화 하려면 캐시를 이용한다. 예를 들어, 용량이 큰 이미지가 많은 사이트를 반복 접속하는 경우에 다운로드 시간과 HTTP GET 요청수를 줄이기 위해 해당 이미지를 사용자의 디스크에 저장하고 캐시로 사용한다. 브라우저는 캐시가 최신 버전인지 이전 버전인지 어떻게 확인할까? 바로 캐시를 사용하기 전에 서버에 HEAD 요청을 날려 Last-Modified Date 를 비교해 최신임을 확인한다. 여기서 주의할 점은 모든 파일에 대해 캐시를 만드는 것이 더 효율적일지 아니면, HEAD 요청을 만들어 날리는 값들을 고려했을 때 캐시로 만들지 않는 것이 더 효율적일지 고민해야 한다. (캐시하려는 파일의 크기가 매우 작은 경우)

---

## FTP (File Transfer Protocol)

파일이 문서, 이미지, 프로그램 등 다양한 형태의 데이터를 갖고 있을 수 있기 때문에 컴퓨터 간의 파일 교환시에 호환성을 보장하는 프로토콜이 필요하다. 컴퓨터 간의 호환성이라는 것은 예를 들어, 한 컴퓨터에서는 JPEG 이미지가 .jpg 로 저장되지만 다른 컴퓨터에서는 .jpeg 로 저장될 수 있다. 또한 어떤 컴퓨터는 파일 경로를 (/) 를 사용하지만 다른 컴퓨터는 () 를 사용할 수도 있다. 이렇기 때문에 파일 전송에 대한 규약인 프로토콜을 이용하여 상호 컴퓨터 간에 파일 전송이 가능하다. FTP 의 특성은 다음과 같다.

- 어떤 형태의 데이터든 전송이 가능하다.
- 파일을 다운로드 & 업로드 할 수 있다.
- 파일에 대한 권한을 설정할 수 있다.
- ASCII 문자로 메시지가 교환된다.
- 파일을 검색하고 조회할 수 있다.

브라우저에서 파일을 다운로드 하게 되면 바로 FTP 프로토콜을 사용하게 된다.

## FTP 통신 방식

HTTP 와는 다르게 FTP 는 클라이언트에서 서버로 한번 연결을 맺어놓은 상태에서 파일을 주고 받는 것이 아니라. 클라이언트에서 서버와의 연결이 맺어지면, 해당 연결은 명령어 입력을 위해 남겨놓고 (Control Connection), 파일을 보낼 때 새로운 연결을 추가하여 파일을 전송한다. (File Connection)

---

## SMTP (Simple Mail Transfer Protocol)

메일 전송 프로그램이 서버로 메일을 보낼 때 사용하는 프로토콜이다. 오직 텍스트만 전송이 가능한 것이 특징이고, 스트림 방식을 이용하여 전송한다. SMTP 는 한 개의 메시지를 해당 서버의 여러 수신자에게 보낼 수 있다는 특징이 있다. 상태 코드는 250 (수신 성공), 550 (수신자 못 찾음)

## MIME (Multi-purpose Internet Mail Extensions)

SMTP 로 전송시 이메일에 텍스트 밖에 포함하지 못하는 단점을 보완하여, 메시지 안에 텍스트 이외의 데이터를 전송할 수 있는 프로토콜이다. 바이너리 파일을 출력 가능한 문자열 형태로 인코딩하고, 수신하는 부분에서 디코딩한다. Base64 로 인코딩 하기는 하지만, 다른 형태의 인코딩도 사용할 수 있다. 인코딩 방식은 메시지의 헤더 안에 정의한다. MIME 은 이메일 헤더에 2 줄을 추가하는데, 이메일에 MIME 이 사용되었는지 여부와 MIME 정보를 바디에 어떻게 포함시킬 건지 를 정의한다.

---

**[프록시 서버 (Proxy Server) ]**

클라이언트와 서버 사이에서 통신을 중계해 주는 컴퓨터나 프로그램을 말합니다. 프록시 서버의 주된 용도 중 하나는 빠른 전송을 위하여 서버의 응답 결과를 캐시에 저장해 두는 것입니다. 프록시 서버를 두는 두 번째 이유는 보안적인 부분인데, 첨단 기술을 다루는 회사의 경우 내부 사용자의 기밀 유출에 민감할 수밖에 없습니다. 이런 경우 프록시 서버를 이용하면 외부로 전달되는 데이터를 검사하여 특정 단어가 포함된 자료의 송.수신을 차단하거나 보안 팀에 경고 메시지를 보낼 수 있습니다.

 **[ 멀티 프로세스와 멀티 스레드 ]**

멀티 프로세스 방식은 클라이언트가 연결 요청을 하면 서버 프로그램은 자신을 복제하여 클라이언트에 대응하게 하고, 자신은 다른 클라이언트의 요청을 기다립니다. 이 방식은 원본 프로세스의 메모리를 모두 복제하기 때문에 자원 낭비가 심합니다. 그에 비해 멀티 스레드 방식은 클라이언트 요청을 처리하는 일부 코드만 별도로 분리하여 실행하기 때문에 전체 메모리를 복제할 필요가 없어, 멀티 프로세스 방식보다 메모리 낭비가 적습니다.

 **[ 요청 헤더 ]**

헤더에는 세 가지 종류가 있는데 요청이나 응답 모두에 적용할 수 있는 '일반 헤더(General-header)'와 요청 또는 응답 둘 중 하나에만 적용할 수 있는 '요청 헤더 또는 응답 헤더(Request-header/Response-header)', 보내거나 받는 본문 데이터를 설명하는 '엔티티 헤더(Entity-header)'가 있습니다. 요청 헤더가 담는 헤더명중 User-Agent가 있는데 클라이언트의 정보를 서버에게 알려주는 헤더입니다. 웹 서버는 이 헤더를 분석하여 요청자의 OS와 브라우저를 구분합니다. 

**[ CGI(Common Gateway Interface) ]**

웹 서버와 프로그램 사이의 데이터를 주고받는 규칙을 CGI(Common Gateway Interface)라고 합니다. 이렇게 웹 서버에 의해 실행되며 CGI 규칙에 따라서 웹 서버와 데이터를 주고 받도록 작성된 프로그램을 'CGI 프로그램'이라고 합니다. 

**[ 서블릿 컨테이너 ]**

서블릿의 생성과 실행, 소멸 등 생명주기를 관리하는 프로그램을 '서블릿 컨테이너(Servlet Container)'라 합니다. 서블릿 컨테이너(Jave EE 기술 중에서 서블릿, JSP 등 웹 관련 부분만 구현한 서버로 아파치 재단의 톰캣, Jetty등)가 서블릿을 대신하여 CGI 규칙에 따라 웹 서버와 데이터를 주고받습니다.

 **[ WebContent/Web-INF ]**

웹 애플리케이션의 설정과 관련된 파일을 두는 폴더로 이 폴더에 있는 파일은 클라이언트에서 요청할 수 없다. 따라서 HTML이나 JavaScript, CSS 등 클라이언트에서 요청할 수 있는 파일을 이 폴더에 두어서는 안 됩니다.

 **[ GET 요청으로 넘어온 매개변수 값의 인코딩 설정 ]**

GET 요청은 매개변수 값이 URL에 포함되기 때문에 setCharacterEncoding()으로는 문자 집합을 설정할 수 없다. 톰캣 서버에서 server.xml을 열어 <Connector>태그에 URIEncoding 속성을 추가하고, 값은 UTF-8로 설정한다. 웹 브라우저가 웹 서버로 데이터를 보낼 때는 웹 페이지의 기본 문자집합으로 인코딩하여 보내기 때문에 사용자가 입력한 값은 UTF-8로 인코딩되어 서버에 전달된다. 반면 서블릿은 UTF-8(한글 한 자를 3바이트로 표현) 3바이트를 하나의 문자로 인식하지 않고 각각의 바이트를 개별 문자로 취급하여 유니코드로 변환한다. 이렇기에 server.xml에 설정을 해주지 않을 경우 한글이 깨지게 된다.

 **[ SeverletContext 보관소 ]**

웹 애플리케이션이 시작될 때 생성되어 웹 애플리케이션이 종료될 때까지 유지된다. 이 보관소에 데이터를 보관하면 웹 애플리케이션이 실행되는 동안에는 모든 서블릿이 사용할 수 있다.

**[ HttpSession 보관소 ]**

클라이언트의 최초 요청 시 생성되어 브라우저를 닫을 때까지 유지됩니다. 보통 로그인할 때 이 보관소를 초기화하고, 로그아웃하면 이 보관소에 저장된 값들을 비웁니다. 따라서 이 보관소에 값을 보관하면 서블릿이나 JSP 페이지에 상관없이 로그아웃하기 전까지 계속 값을 유지할 수 있습니다. JSP에서는 session변수를 통해 이 보관소를 참조할 수 있습니다.

 **[ ServletRequest 보관소 ]**

클라이언트의 요청이 들어올 때 생성되어, 클라이언트에게 응답 할 때까지 유지됩니다. 이 보관소는 포워딩이나 인클루딩하는 서블릿들 사이에서 값을 공유할 때 유용합니다. JSP에서는 request변수를 통해 이 보관소를 참조할 수 있습니다.

 **[ JspContext 보관소 ]**

JSP 페이지를 실행하는 동안만 유지됩니다. JSP에서는 pageContext 변수를 통해 이 보관소를 참조할 수 있습니다.

**[ HttpSession ]**

HttpSession 객체는 클라이언트 당 한 개가 생성됩니다. 웹 브라우저로부터 요청이 들어오면, 그 웹 브라우저를 위한 HttpSession 객체가 있는지 검사하고, 없다면 새로 HttpSession 객체를 만듭니다. 이렇게 생성된 HttpSession 객체는 그 웹 브라우저로부터 일정 시간 동안 Timeout 요청이 없으면, 삭제됩니다.

 **[ JspContext의 활용 ]**

JSP 페이지를 작성하다 보면 <jsp:include>와 같은 특별한 태그를 사용하게 됩니다. 이런 태그들은 JSP 엔진이 서블릿 클래스를 생성할 때 특정 자바 코드로 변환됩니다. 이때 이 태그의 값을 다루는 객체를 '태그 핸들러'라고 부릅니다. 바로 이 태그 핸들러에게 데이터를 전달하고자 할 때 JspContext 보관소를 사용하는 것입니다.  JSP 페이지에 선언된 로컬 변수는 태그 핸들러에서 접근할 수 없습니다. 따라서 태그 핸들러에게 전달할 데이터가 아니라면 JspContext에 값을 보관할 필요가 없습니다.

**[ DI(Dependency Injection) ]**

작업에 필요한 객체를 외부로부터 주입 받는 것으로 다른 말로 역제어(IoC, Inversion of Control)'라고도 부릅니다.

---

## 2.DATABASE, TABLE 생성, 데이타 INSERT

### 2-1. DATABASE 생성

> 깨끗하게 hhddb를 생성하기 위해 사용포인트를 다른DB로 옮기고 기존 DB를 삭제하고 생성

```
USE tempdb;
DROP DATABASE hhddb;
CREATE DATABASE hhddb;
USE hhddb;

```

### 2-2. TABLE 생성

> 각 테이블 생성 
> Create Customers table

```
CREATE TABLE Customers
(
  cust_id      char(10 )  NOT NULL ,
  cust_name    char(50 )  NOT NULL ,
  cust_address char( 50)  NULL ,
  cust_city    char(50 )  NULL ,
  cust_state   char(5 )   NULL ,
  cust_zip     char(10 )  NULL ,
  cust_country char( 50)  NULL ,
  cust_contact char( 50)  NULL ,
  cust_email   char(255 ) NULL
);

```

> Create OrderItems table

```
CREATE TABLE OrderItems
(
  order_num  int          NOT NULL ,
  order_item int          NOT NULL ,
  prod_id    char(10 )     NOT NULL ,
  quantity   int          NOT NULL ,
  item_price decimal( 8,2 ) NOT NULL
);

...
...
...

```

> 모든 테이블이 잘 생성되었는지 확인

```
SELECT * FROM sys.tables ;
```

```
name        object_id   principal_id schema_id   parent_object_id type type_desc  ...  ----------- ----------- ------------ ----------- ---------------- ---- -----------...  Customers   245575913   NULL         1           0                U    USER_TABLE ...  OrderItems  261575970   NULL         1           0                U    USER_TABLE ...  Orders      277576027   NULL         1           0                U    USER_TABLE ...  Products    293576084   NULL         1           0                U    USER_TABLE ...  Vendors     309576141   NULL         1           0                U    USER_TABLE ...    (5개 행이 영향을 받음)
```

### 2-3. 데이타 INSERT

> 각 테이블에 데이타 INSERT 
> Populate Customers table

```
INSERT INTO Customers(cust_id , cust_name, cust_address, cust_city , cust_state, cust_zip, cust_country, cust_contact, cust_email)
VALUES('1000000001' , 'Village Toys' , '200 Maple Lane' , 'Detroit' , 'MI' , '44444' , 'USA' , 'John Smith', 'sales@villagetoys.com');
INSERT INTO Customers(cust_id , cust_name, cust_address, cust_city , cust_state, cust_zip, cust_country, cust_contact)
VALUES('1000000002' , 'Kids Place' , '333 South Lake Drive' , 'Columbus' , 'OH' , '43333' , 'USA', 'Michelle Green');
INSERT INTO Customers(cust_id , cust_name, cust_address, cust_city , cust_state, cust_zip, cust_country, cust_contact, cust_email)
VALUES('1000000003' , 'Fun4All' , '1 Sunny Place' , 'Muncie' , 'IN' , '42222' , 'USA' , 'Jim Jones', 'jjones@fun4all.com' );
INSERT INTO Customers(cust_id , cust_name, cust_address, cust_city , cust_state, cust_zip, cust_country, cust_contact, cust_email)
VALUES('1000000004' , 'Fun4All' , '829 Riverside Drive' , 'Phoenix' , 'AZ' , '88888' , 'USA' , 'Denise L. Stephens', 'dstephens@fun4all.com');
INSERT INTO Customers(cust_id , cust_name, cust_address, cust_city , cust_state, cust_zip, cust_country, cust_contact)
VALUES('1000000005' , 'The Toy Store' , '4545 53rd Street' , 'Chicago' , 'IL' , '54545' , 'USA' , 'Kim Howard');
```

> Populate Vendors table

```
INSERT INTO Vendors(vend_id , vend_name, vend_address, vend_city , vend_state, vend_zip, vend_country)
VALUES('BRS01' ,'Bears R Us', '123 Main Street','Bear Town' ,'MI', '44444', 'USA');
INSERT INTO Vendors(vend_id , vend_name, vend_address, vend_city , vend_state, vend_zip, vend_country)
VALUES('BRE02' ,'Bear Emporium', '500 Park Street','Anytown' ,'OH', '44333', 'USA');
INSERT INTO Vendors(vend_id , vend_name, vend_address, vend_city , vend_state, vend_zip, vend_country)
VALUES('DLL01' ,'Doll House Inc.', '555 High Street','Dollsville' ,'CA', '99999', 'USA');
INSERT INTO Vendors(vend_id , vend_name, vend_address, vend_city , vend_state, vend_zip, vend_country)
VALUES('FRB01' ,'Furball Inc.', '1000 5th Avenue','New York' ,'NY', '11111', 'USA');
INSERT INTO Vendors(vend_id , vend_name, vend_address, vend_city , vend_state, vend_zip, vend_country)
VALUES('FNG01' ,'Fun and Games', '42 Galaxy Road','London' , NULL, 'N16 6PS', 'England');
INSERT INTO Vendors(vend_id , vend_name, vend_address, vend_city , vend_state, vend_zip, vend_country)
VALUES('JTS01' ,'Jouets et ours', '1 Rue Amusement','Paris' , NULL, '45678', 'France');
```

> 각 테이블에 데이타 INSERT 
> Populate Customers table

```
INSERT INTO Customers(cust_id , cust_name, cust_address, cust_city , cust_state, cust_zip, cust_country, cust_contact, cust_email)
VALUES('1000000001' , 'Village Toys' , '200 Maple Lane' , 'Detroit' , 'MI' , '44444' , 'USA' , 'John Smith', 'sales@villagetoys.com');
INSERT INTO Customers(cust_id , cust_name, cust_address, cust_city , cust_state, cust_zip, cust_country, cust_contact)
VALUES('1000000002' , 'Kids Place' , '333 South Lake Drive' , 'Columbus' , 'OH' , '43333' , 'USA', 'Michelle Green');
INSERT INTO Customers(cust_id , cust_name, cust_address, cust_city , cust_state, cust_zip, cust_country, cust_contact, cust_email)
VALUES('1000000003' , 'Fun4All' , '1 Sunny Place' , 'Muncie' , 'IN' , '42222' , 'USA' , 'Jim Jones', 'jjones@fun4all.com' );
INSERT INTO Customers(cust_id , cust_name, cust_address, cust_city , cust_state, cust_zip, cust_country, cust_contact, cust_email)
VALUES('1000000004' , 'Fun4All' , '829 Riverside Drive' , 'Phoenix' , 'AZ' , '88888' , 'USA' , 'Denise L. Stephens', 'dstephens@fun4all.com');
INSERT INTO Customers(cust_id , cust_name, cust_address, cust_city , cust_state, cust_zip, cust_country, cust_contact)
VALUES('1000000005' , 'The Toy Store' , '4545 53rd Street' , 'Chicago' , 'IL' , '54545' , 'USA' , 'Kim Howard');
```

> Populate Vendors table

```
INSERT INTO Vendors(vend_id , vend_name, vend_address, vend_city , vend_state, vend_zip, vend_country)
VALUES('BRS01' ,'Bears R Us', '123 Main Street','Bear Town' ,'MI', '44444', 'USA');
INSERT INTO Vendors(vend_id , vend_name, vend_address, vend_city , vend_state, vend_zip, vend_country)
VALUES('BRE02' ,'Bear Emporium', '500 Park Street','Anytown' ,'OH', '44333', 'USA');
INSERT INTO Vendors(vend_id , vend_name, vend_address, vend_city , vend_state, vend_zip, vend_country)
VALUES('DLL01' ,'Doll House Inc.', '555 High Street','Dollsville' ,'CA', '99999', 'USA');
INSERT INTO Vendors(vend_id , vend_name, vend_address, vend_city , vend_state, vend_zip, vend_country)
VALUES('FRB01' ,'Furball Inc.', '1000 5th Avenue','New York' ,'NY', '11111', 'USA');
INSERT INTO Vendors(vend_id , vend_name, vend_address, vend_city , vend_state, vend_zip, vend_country)
VALUES('FNG01' ,'Fun and Games', '42 Galaxy Road','London' , NULL, 'N16 6PS', 'England');
INSERT INTO Vendors(vend_id , vend_name, vend_address, vend_city , vend_state, vend_zip, vend_country)
VALUES('JTS01' ,'Jouets et ours', '1 Rue Amusement','Paris' , NULL, '45678', 'France'); 
...
...
...
```

## 3. 데이타 검색, 조작

### 3-1. 컬럼정해서 SELECT

> 내림차순으로 정렬

```
USE hhddb;

SELECT prod_id, prod_price, prod_name
FROM Products
ORDER BY prod_price DESC;

```

```
prod_id    prod_price                              prod_name  ---------- --------------------------------------- ----------------------------------------  BR03       11.99                                   18 inch teddy bear                       RYL01      9.49                                    King doll                                RYL02      9.49                                    Queen doll                               BR02       8.99                                    12 inch teddy bear                       BR01       5.99                                    8 inch teddy bear                        RGAN01     4.99                                    Raggedy Ann                              BNBG01     3.49                                    Fish bean bag toy                        BNBG02     3.49                                    Bird bean bag toy                        BNBG03     3.49                                    Rabbit bean bag toy                    
```

### 3-2. 범위정해서 SELECT

```
SELECT prod_name, prod_price
FROM Products
WHERE prod_price BETWEEN 5 AND 10 ;
```

```
prod_name                                prod_price  ---------------------------------------- ---------------------------------------  8 inch teddy bear                        5.99  12 inch teddy bear                       8.99  King doll                                9.49  Queen doll                               9.49
```

### 3-3. IN 그룹안에서 조건걸어서 SELECT

```
SELECT prod_name, prod_price
FROM Products
WHERE vend_id IN ('DLL01' , 'BRS01' )
ORDER BY prod_name;
```

```
prod_name                                prod_price  ---------------------------------------- ---------------------------------------  12 inch teddy bear                       8.99  18 inch teddy bear                       11.99  8 inch teddy bear                        5.99  Bird bean bag toy                        3.49  Fish bean bag toy                        3.49  Rabbit bean bag toy                      3.49  Raggedy Ann                              4.99    (7개 행이 영향을 받음)
```

### 3-4. 부정절 조건으로 SELECT

```
SELECT prod_name
FROM Products
WHERE NOT vend_id = 'DLL01'
ORDER BY prod_id;
```

```
prod_name  ----------------------------------------  8 inch teddy bear                        12 inch teddy bear                       18 inch teddy bear                       King doll                                Queen doll                                 (5개 행이 영향을 받음)
```

### 3-5. LIKE 를 이용한 패턴 SELECT

> 와일드카드 문자 이용

```
SELECT prod_name
FROM Products
WHERE prod_name LIKE 'F%y';
```

```
prod_name  ----------------------------------------  Fish bean bag toy                      
```

### 3-6. LIKE를 이용한 패턴 SELECT

> 와일드카드문자 + 정규식이용

```
SELECT cust_contact
FROM Customers
WHERE cust_contact LIKE '[JM]%';
```

```
cust_contact  ----------------------------------------  John Smith                               Michelle Green                           Jim Jones                                  (3개 행이 영향을 받음)
```

### 3-7. 평균값을 구함

> AVG 함수 사용

```
SELECT AVG (prod_price) AS avg_price
FROM Products;
```

```
avg_price  ---------------------------------------  6.823333
```

### 3-8. 그룹핑하고 카운트를 구함

> GROUP BY 
> COUNT 함수 사용

```
SELECT vend_id, COUNT(*) as num_prod
FROM Products
GROUP BY vend_id;
```

```
vend_id    num_prod  ---------- -----------  BRS01      3  DLL01      4  FNG01      2
```

### 3-9. 그룹핑하고 카운트를 구하며, 그 그룹의 조건으로 필터링

> GROUP BY 
> COUNT 함수 
> HAVING
>
> - HAVING은 그룹에 대한 WHERE라고 생각하면 된다.

```
SELECT vend_id, COUNT(*) as num_prod
FROM Products
WHERE prod_price >= 4
GROUP BY vend_id
HAVING COUNT (*) >= 2;
```

```
vend_id    num_prod  ---------- -----------  BRS01      3  FNG01      2
```

### 3-10. IN 그룹을 SELECT쿼리로 중첩쿼리 만들어서 사용.

```
SELECT cust_id
FROM Orders
WHERE order_num IN
(
    SELECT order_num
    FROM OrderItems
    WHERE prod_id = 'RGAN01'
);
```

```
cust_id  ----------  1000000004  1000000005
```

### 3-11. 명시적인 INNER JOIN

```
SELECT vend_name, prod_name, prod_price
FROM Vendors INNER JOIN Products
ON Vendors. vend_id = Products .vend_id;
```

```
vend_name                                prod_name                                prod_price  ---------------------------------------- ---------------------------------------- ---------------------------------------  Doll House Inc.                          Fish bean bag toy                        3.49  Doll House Inc.                          Bird bean bag toy                        3.49  Doll House Inc.                          Rabbit bean bag toy                      3.49  Bears R Us                               8 inch teddy bear                        5.99  Bears R Us                               12 inch teddy bear                       8.99  Bears R Us                               18 inch teddy bear                       11.99  Doll House Inc.                          Raggedy Ann                              4.99  Fun and Games                            King doll                                9.49  Fun and Games                            Queen doll                               9.49
```

### 3-12. 암시적인 INNER JOIN

```
SELECT prod_name, vend_name, prod_price , quantity
FROM OrderItems, Products, Vendors
WHERE Products. vend_id = Vendors .vend_id
    AND OrderItems .prod_id = Products.prod_id
    AND order_num = 20007;
```

```
prod_name                                vend_name                                prod_price ...  ---------------------------------------- ---------------------------------------- -----------...  18 inch teddy bear                       Bears R Us                               11.99      ...  Fish bean bag toy                        Doll House Inc.                          3.49       ...  Bird bean bag toy                        Doll House Inc.                          3.49       ...  Rabbit bean bag toy                      Doll House Inc.                          3.49       ...  Raggedy Ann                              Doll House Inc.                          4.99       ...
```

### 3-13. 암시적인 INNER JOIN 에 컬럼이름 커스토마이즈

```
SELECT c. cust_name AS '고객이름', c .cust_contact AS '고객주소'
FROM Customers AS c, Orders AS o, OrderItems AS oi
WHERE c. cust_id = o .cust_id
    AND oi .order_num = o.order_num
    AND prod_id = 'RGAN01' ;
```

```
고객이름                                     고객주소  ---------------------------------------- ----------------------------------------  Fun4All                                  Denise L. Stephens                       The Toy Store                            Kim Howard                             
```

### 3-14. 명시적인 OUTER JOIN

> OUTER JOIN 은 명시적으로 JOIN기준축을 설정해 주어야 한다.

```
SELECT Customers. cust_id, Orders .order_num
FROM Customers LEFT OUTER JOIN Orders
ON Customers. cust_id = orders .cust_id;
```

```
cust_id    order_num  ---------- -----------  1000000001 20005  1000000001 20009  1000000002 NULL  1000000003 20006  1000000004 20007  1000000005 20008
```

### 3-15. 두 결과를 병합 UNION

> UNION 과정에서 중복데이타는 제거된다.

```
(
    SELECT cust_name , cust_contact
    FROM Customers
    WHERE cust_state IN ( 'IL', 'IN', 'MI')
)
UNION
(
    SELECT *
    FROM Customers
    WHERE cust_name = 'Fun4All'
);
```

```
cust_id    cust_name                                cust_address                             cust_city    ...  ---------- ---------------------------------------- ---------------------------------------- -------------...  1000000001 Village Toys                             200 Maple Lane                           Detroit      ...  1000000003 Fun4All                                  1 Sunny Place                            Muncie       ...  1000000004 Fun4All                                  829 Riverside Drive                      Phoenix      ...  1000000005 The Toy Store                            4545 53rd Street                         Chicago      ...
```

### 3-16. 스키마가 똑같은 테이블을 만들어서 모든내용 복사

```
DROP TABLE CustomersNew;

CREATE TABLE CustomersNew
(
  cust_id      char(10 )  NOT NULL ,
  cust_name    char(50 )  NOT NULL ,
  cust_address char( 50)  NULL ,
  cust_city    char(50 )  NULL ,
  cust_state   char(5 )   NULL ,
  cust_zip     char(10 )  NULL ,
  cust_country char( 50)  NULL ,
  cust_contact char( 50)  NULL ,
  cust_email   char(255 ) NULL
);

INSERT INTO CustomersNew
SELECT *
FROM Customers;

SELECT *
FROM CustomersNew;
```

```
(5개 행이 영향을 받음)  cust_id    cust_name                                cust_address                             cust_city ...  ---------- ---------------------------------------- ---------------------------------------- ----------...  1000000001 Village Toys                             200 Maple Lane                           Detroit   ...  1000000002 Kids Place                               333 South Lake Drive                     Columbus  ...  1000000003 Fun4All                                  1 Sunny Place                            Muncie    ...  1000000004 Fun4All                                  829 Riverside Drive                      Phoenix   ...  1000000005 The Toy Store                            4545 53rd Street                         Chicago   ...    (5개 행이 영향을 받음)
```

### 3-17. 데이타 업데이트

```
UPDATE Customers
SET cust_email = 'kim@thetoystore.com'
WHERE cust_id = '1000000005';

SELECT *
FROM Customers
WHERE cust_id = '1000000005';
```

```
(1개 행이 영향을 받음)  cust_id    cust_name                                cust_address                             cust_city ...  ---------- ---------------------------------------- ---------------------------------------- ----------...  1000000005 The Toy Store                            4545 53rd Street                         Chicago   ...    (1개 행이 영향을 받음)
```

### 3-18. 데이타 삭제

```
SELECT * FROM CustomersNew
WHERE cust_id = '1000000005';
```

```
cust_id    cust_name                                cust_address                             cust_city   ...  ---------- ---------------------------------------- ---------------------------------------- ------------...  1000000005 The Toy Store                            4545 53rd Street                         Chicago     ...                                                                                                             ...  (1개 행이 영향을 받음)                                                                                   ...
```

```
DELETE FROM CustomersNew
WHERE cust_id = '1000000005';
```

```
(1개 행이 영향을 받음)                                                                                   ...
```

```
SELECT * FROM CustomersNew
WHERE cust_id = '1000000005';
```

```
cust_id    cust_name                                cust_address                             cust_city   ...  ---------- ---------------------------------------- ---------------------------------------- ------------...    (0개 행이 영향을 받음)
```

### 3-19. 테이블에서 컬럼추가, 컬럼삭제

> 테이블의 모든 컬럼보기

```
SELECT *
FROM INFORMATION_SCHEMA .COLUMNS
WHERE TABLE_NAME = 'Vendors';
```

```
TABLE_CATALOG           TABLE_SCHEMA  TABLE_NAME  COLUMN_NAME   ...  ----------------------- ------------- ----------- --------------...  hhddb                   dbo           Vendors     vend_id       ...  hhddb                   dbo           Vendors     vend_name     ...  hhddb                   dbo           Vendors     vend_address  ...  hhddb                   dbo           Vendors     vend_city     ...  hhddb                   dbo           Vendors     vend_state    ...  hhddb                   dbo           Vendors     vend_zip      ...  hhddb                   dbo           Vendors     vend_country  ...                                                                   ...  (7개 행이 영향을 받음)                                          ...
```

```
alter table Vendors
add vend_phone char (20);

SELECT *
FROM INFORMATION_SCHEMA .COLUMNS
WHERE TABLE_NAME = 'Vendors';
```

```
TABLE_CATALOG           TABLE_SCHEMA  TABLE_NAME  COLUMN_NAME   ...  ----------------------- ------------- ----------- --------------...  hhddb                   dbo           Vendors     vend_id       ...  hhddb                   dbo           Vendors     vend_name     ...  hhddb                   dbo           Vendors     vend_address  ...  hhddb                   dbo           Vendors     vend_city     ...  hhddb                   dbo           Vendors     vend_state    ...  hhddb                   dbo           Vendors     vend_zip      ...  hhddb                   dbo           Vendors     vend_country  ...  hhddb                   dbo           Vendors     vend_phone    ...                                                                  ...  (8개 행이 영향을 받음)                                          ...
```

```
alter table Vendors
drop column vend_phone;

SELECT *
FROM INFORMATION_SCHEMA .COLUMNS
WHERE TABLE_NAME = 'Vendors';
```

```
TABLE_CATALOG           TABLE_SCHEMA  TABLE_NAME  COLUMN_NAME   ...  ----------------------- ------------- ----------- --------------...  hhddb                   dbo           Vendors     vend_id       ...  hhddb                   dbo           Vendors     vend_name     ...  hhddb                   dbo           Vendors     vend_address  ...  hhddb                   dbo           Vendors     vend_city     ...  hhddb                   dbo           Vendors     vend_state    ...  hhddb                   dbo           Vendors     vend_zip      ...  hhddb                   dbo           Vendors     vend_country  ...    (7개 행이 영향을 받음)
```

### 3-20. 저장프로시저 생성/실행/삭제

```
CREATE PROCEDURE sp_new_order @cust_id CHAR( 10)
AS
    DECLARE @order_num INTEGER;

    SELECT @order_num = MAX (order_num)
    FROM Orders ;

    SELECT @order_num = @order_num + 1;

    INSERT INTO Orders( order_num, order_date , cust_id)
    VALUES( @order_num, GETDATE(), @cust_id );

    RETURN @order_num ;
GO

SELECT * FROM sys.procedures ;
```

```
name                                     object_id   principal_id schema_id   parent_object_id type type_desc                                ...  ---------------------------------------- ----------- ------------ ----------- ---------------- ---- ---------------------------------------- ...  sp_new_order                             869578136   NULL         1           0                P    SQL_STORED_PROCEDURE                     ...
```

```
SELECT * FROM Orders ;
```

```
order_num   order_date              cust_id  ----------- ----------------------- ----------  20005       2004-05-01 00:00:00.000 1000000001  20006       2004-01-12 00:00:00.000 1000000003  20007       2004-01-30 00:00:00.000 1000000004  20008       2004-02-03 00:00:00.000 1000000005
```

```
EXECUTE sp_new_order '1000000001';
EXECUTE sp_new_order '1000000001';
EXECUTE sp_new_order '1000000001';

SELECT * FROM Orders ;
```

```
order_num   order_date              cust_id  ----------- ----------------------- ----------  20005       2004-05-01 00:00:00.000 1000000001  20006       2004-01-12 00:00:00.000 1000000003  20007       2004-01-30 00:00:00.000 1000000004  20008       2004-02-03 00:00:00.000 1000000005  20009       2004-02-08 00:00:00.000 1000000001  20010       2015-10-01 14:20:39.107 1000000001  20011       2015-10-01 14:20:39.113 1000000001
```

```
DROP PROCEDURE sp_new_order;
```

### 3-21. 트렌젝션을 설정하고 도중에 실패한 경우 롤백까지

> 이 예제에서는 작업진행하다가 중간에 Orders 테이블에서 삭제시 FK제약사항 때문에 예외가 발생하고 이 때문에 롤백됨.

```
BEGIN TRANSACTION ;
SAVE TRANSACTION start_point;

SELECT *
FROM OrderItems;
```

```
order_num   order_item  prod_id    quantity    item_price  ----------- ----------- ---------- ----------- ---------------------------------------  20005       1           BR01       100         5.49  20005       2           BR03       100         10.99  20006       1           BR01       20          5.99  20006       2           BR02       10          8.99  20006       3           BR03       10          11.99  20007       1           BR03       50          11.49  20007       2           BNBG01     100         2.99  20007       3           BNBG02     100         2.99  20007       4           BNBG03     100         2.99  20007       5           RGAN01     50          4.49  20008       1           RGAN01     5           4.99  20008       2           BR03       5           11.99  20008       3           BNBG01     10          3.49  20008       4           BNBG02     10          3.49  20008       5           BNBG03     10          3.49  20009       1           BNBG01     250         2.49  20009       2           BNBG02     250         2.49  20009       3           BNBG03     250         2.49
```

```
DELETE OrderItems
WHERE order_num = 20005;

SELECT *
FROM OrderItems;
```

```
order_num   order_item  prod_id    quantity    item_price  ----------- ----------- ---------- ----------- ---------------------------------------  20006       1           BR01       20          5.99  20006       2           BR02       10          8.99  20006       3           BR03       10          11.99  20007       1           BR03       50          11.49  20007       2           BNBG01     100         2.99  20007       3           BNBG02     100         2.99  20007       4           BNBG03     100         2.99  20007       5           RGAN01     50          4.49  20008       1           RGAN01     5           4.99  20008       2           BR03       5           11.99  20008       3           BNBG01     10          3.49  20008       4           BNBG02     10          3.49  20008       5           BNBG03     10          3.49  20009       1           BNBG01     250         2.49  20009       2           BNBG02     250         2.49  20009       3           BNBG03     250         2.49
```

```
SELECT *
FROM Orders;
```

```
order_num   order_date              cust_id  ----------- ----------------------- ----------  20005       2004-05-01 00:00:00.000 1000000001  20006       2004-01-12 00:00:00.000 1000000003  20007       2004-01-30 00:00:00.000 1000000004  20008       2004-02-03 00:00:00.000 1000000005  20009       2004-02-08 00:00:00.000 1000000001
```

```
DELETE Orders
WHERE order_num = 20005;
```

(1개 행이 영향을 받음)

```
SELECT *
FROM Orders;
```

```
order_num   order_date              cust_id  ----------- ----------------------- ----------  20006       2004-01-12 00:00:00.000 1000000003  20007       2004-01-30 00:00:00.000 1000000004  20008       2004-02-03 00:00:00.000 1000000005  20009       2004-02-08 00:00:00.000 1000000001
```

```
DELETE Orders
WHERE order_num = 20006;

IF @@ERROR <> 0
BEGIN
    PRINT N'에러 발생함 start_point 로 롤백함...' ;
    ROLLBACK TRANSACTION start_point;
END
```

메시지 547, 수준 16, 상태 0, 줄 22  DELETE 문이 REFERENCE 제약 조건 "FK_OrderItems_Orders"과(와) 충돌했습니다. 데이터베이스 "hhddb", 테이블 "dbo.OrderItems", column 'order_num'에서 충돌이 발생했습니다.  문이 종료되었습니다.  에러 발생함 start_point 로 롤백함...

```
SELECT *
FROM Orders;
```

```
order_num   order_date              cust_id  ----------- ----------------------- ----------  20005       2004-05-01 00:00:00.000 1000000001  20006       2004-01-12 00:00:00.000 1000000003  20007       2004-01-30 00:00:00.000 1000000004  20008       2004-02-03 00:00:00.000 1000000005  20009       2004-02-08 00:00:00.000 1000000001
```

```
COMMIT TRANSACTION ;
```

### 3-22. 인덱스 생성/확인/삭제

```
SELECT *
FROM INFORMATION_SCHEMA.COLUMNS
WHERE TABLE_NAME = 'Products';

CREATE INDEX idx_prod_name
ON Products( prod_name);

SELECT *
FROM sys.indexes
WHERE name LIKE 'idx_%';

DROP INDEX idx_prod_name
ON Products;

TABLE_CATALOG  TABLE_SCHEMA  TABLE_NAME  COLUMN_NAME  ...  -------------- ------------- ----------- -------------...  hhddb          dbo           Products    prod_id      ...  hhddb          dbo           Products    vend_id      ...  hhddb          dbo           Products    prod_name    ...  hhddb          dbo           Products    prod_price   ...  hhddb          dbo           Products    prod_desc    ...    (5개 행이 영향을 받음)    object_id   name           index_id    type type_desc      is_unique data_space_id ...  ----------- -------------- ----------- ---- -------------- --------- ------------- ...  293576084   idx_prod_name  2           2    NONCLUSTERED   0         1             ...    (1개 행이 영향을 받음)  ...
```
---

### 1.PHP의 변수 사용법 

#### 1. 변수

1.1 PHP의 변수란?

먼저 **변수**를 설명하겠습니다. MySQL에서도 등장했지만, 변수는 값을 담는 '상자'와 같은 것입니다. PHP와 MySQL을 연계할 때, 변수는 없어서는 안 될 중요한 역할을 합니다.

그럼, 실제로 변수를 사용해 보겠습니다. 먼저 예제 16-1의 스킙트를 15장에서 print 를 이용했듯, 같은 요령으로 입력합니다.

예제 16-1 variable.php

<?php

$a = "Hello";

print $a;

?>

잘못 입력한 부분이 없는지 다시 한번 확인하고, variable.php라는 파일 이름으로 웹 서버의 공유 폴더에 저장합니다. 웹 서버의 공유 폴더는 환경에 따라 다르지만, 여기서 설명한 대로 XAMPP를 설치했다면 C:\xampp\htdocs입니다. 또한, Apache가 실행 중인지 확인했다면 웹 브라우저의 주소창에 다음과 같이 입력합니다.

http://localhost/variable.php

![img](http://cfile6.uf.tistory.com/image/243C8E4956D2F1E50DD5FE)

만일, 표시되지 않는다면 15장의 '**7.3 실행 결과가 표시되지 않을 때 대처 방법**'을 참고해 점검해 보기 바랍니다.

그럼 이제 스크립트의 내용을 확인해 보겠습니다. 먼저, PHP에서는 변수 이름 앞에 $를 붙입니다. 앞의 예에서는 변수 $a로 표시했습니다. 그리고 다음 구문이 포인트입니다.

$a = "Hello";

프로그램 언어를 처음 접하는 분은 앞의 식이 낯설게 느껴질 수 있습니다. 앞의 식에서는 변수 $a에 'Hello'라는 문자열을 '대입'하고 있습니다.

프로그램 세계에서 등호(=)는 '우변에 있는 값을 좌변에 대입한다.'라는 의미입니다. 이제 변수 $a의 값의 'Hello'가 되었습니다.

참고로, MySQL의 비교 연산자에서 소개한 '같다'를 나타내는 등호(=)는 PHP에서는 ==로 표시합니다.

print는 문자열을 출력하는 명령입니다. 다음 명령은 변수 $a의 값, 즉, 문자열 'Hello'를 출력합니다.

print $a;

15장의 예를 변수를 사용해서 나타냈습니다. 이처럼 '값을 넣는 상자'와 같은 역할을 하는 것이 변수입니다. 또한, 값을 계속 넣어 두기만 하는 것이 아니라, 넣고 빼고를 자유롭게 할 수 있는 편리한 상자입니다.

1.2 변수 이름의 규칙

변수 이름을 설정하는 데에는 여러 규칙이 있습니다. PHP에서는 다음과 같은 규칙이 있습니다.

■ 맨 앞에 $를 붙인다.

■ 대문자와 소문자를 구별한다.

■ 문자와 숫자, 밑줄(_)로 구성된다.

■ $의 바로 뒤에는 숫자를 사용할 수 없다.

**$ 사용하기**

PHP의 변수는 변수의 맨 앞에 $를 붙이는 것이 특징입니다. 예를 들어, $age나 $TEL과 같이 작성합니다.

**문자와 숫자, 밑줄(_)로 구성되지만, 숫자로 시작할 수 없다.**

변수의 첫 글자는 문자 또는 밑줄(_)입니다. $19years는 안되지만, $_19years는 허용됩니다.

****

**대문자와 소문자를 구별한다.**

대문자와 소문자를 구별합니다. 예를 들어, $tel과 $Tel, $TEL은 각각 다른 변수로 취급됩니다. 여기서는 모든 변수 이름에 소문자를 사용하겠습니다.

1.3 미리 정의된 상수

PHP에는 사용자가 설정하지 않아도 이미 정의된 값이 있습니다. 예를 들어, 다음과 같이 원주율이나 PHP의 버전을 나타내는 **상수**는 그대로 사용할 수 있습니다.

▶ PHP 상수의 예

| M_PI        | 원주율        |
| ----------- | ---------- |
| PHP_VERSION | PHP의 버전    |
| PHP_OS      | 실행 중인 운영체제 |

예를 들어, 예제 16-2와 같이 입력하면 원주율이 표시됩니다.

예제 16-2 pi.php

<?php

print M_PI;

?>

![img](http://cfile7.uf.tistory.com/image/255F794856D2F5AB198A72)

1.4 변수의 자료형

다음은 변수의 자료형입니다. PHP에서는 자료형을 정의하지 않아도 변수를 사용할 수 있다는 특징이 있습니다. '문자열을 대입하면 문자열 자료형', '정수를 대입하면 정수형'과 같이 번거로운 정의를 하지 않아도 데이터를 대입했을 때 PHP에 의해 자동으로 자료형이 결정됩니다.

MySQL에서 테이블을 만들 때에는 처음부터 필드의 자료형을 결정해야 합니다. 숫자 자료형의 칼럼에 문자열을 저장할 수 없고, 저장 함수에서 사용하는 변수는 사용하기 전에 DECLARE로 자료형을 선언해야 합니다.

이에 비해 PHP는 '일단 대입하고 나서 자료형을 맞추는 구조'입니다. 다음은 PHP에서 사용할 수 있는 주요 자료형 입니다.

PHP에서 사용할 수 있는 주요 자료형

| 내용     | 자료형     |
| ------ | ------- |
| 정수     | integer |
| 부동소수점  | float   |
| 부동소수점  | double  |
| 문자열    | string  |
| 논리값    | boolean |
| 객체     | object  |
| 배열     | array   |
| 널(빈 값) | NULL    |

데이터를 대입하면 알아서 자료형을 설정해 주기 때문에, 개발자 입장에서는 특별히 신경 쓸 필요가 없습니다.

**2. PHP의 문자열 사용법**

****

\2. 문자열

이번에는 PHP의 문자열에 대해 설명하겠습니다.

2.1 문자열 결합

먼저, 문자열을 연결하는 방법입니다. 익숙해지기 전까지는 번거롭게 느낄 수도 있지만, PHP에서는 문자열을 결합할 때 온점(.)을 사용합니다. 문자열 데이터는 큰따옴표(")나 작은 따옴표(')로 감싸야 하기 때문에 '박'과 '문수'를 결합해서 표시할 때에는 "박"."문수"라고 작성합니다.

다음의 예제 16-3은 변수 $a 에 'Hello', 변수 $b에 'SQL 블로그에 오신 걸 환영합니다!'라는 문자열을 대입하고 나서, 이 두 문자열을 결합해서 표시하는 예입니다.

예제 16-3 join.php

<?php

$a = "Hello";

$b = "SQL 블로그에 오신 걸 환영합니다!";

print $a.$b;

?>

$a.$b에서 각각의 변수에 들어있는 문자열을 결합하고 있습니다.

2.2 큰따옴표와 작은따옴표의 사용법

문자열은 큰따옴표(")나 작은따옴표(')로 감싸서 표현합니다.

단, 큰따옴표(")로 감싼 문자열 중에 큰따옴표 문자가 포함되어 있거나, 작은따옴표(')로 감싼 문자열 중에 작은 따옴표 문자가 포함되어 있으면 안 됩니다. PHP에서는 큰따옴표나 작은따옴표를 문자열의 시작 지점이나 종료 지점으로판단하기 때문에, 오류가 발생하게 됩니다. 이것은 MySQL의 SQL 문과 같습니다.

예를 들어, 다음 예에서는 오류가 발생합니다.

print "문자열은 ""으로 감쌉니다.";

// 큰따옴표로 감싼 내부에 큰따옴표가 또 있다.

**이스케이프 처리**

앞서와 같은 경우, 큰따옴표나 작은따옴표 앞에 역슬래시(\)를 입력하면 오류를 피할 수 있습니다. 이런 방법을 이스케이프 처리라고 합니다.

print "문자열은 \"\"으로 감쌉니다.";

// 문자열 안의 큰따옴표(") 앞에 \를 입력한다(이스케이프처리).

**큰따옴표와 작은따옴표 사용하기**

따옴표를 사용할 때 오류를 피하는 또 다른 방법은 큰따옴표를 문자로 취급할 때에는 작은따옴표로 감싸고, 작은따옴표를 문자로 취급할 때에는 큰따옴표로 감싸는 방법입니다. 예를 들어, 다음 예에서는 오류가 발생하기 않습니다.

print "문자열은 ' '으로 감쌉니다";

다음 장부터는 MySQL을 이용하는 웹 응용프로그램을 만들 때, PHP 스크립트를 사용해서 SQL 문을 작성할 것입니다. 이렇게 하려면 mysql_query()라는 함수의 인수에 SQL문을 문자열 형태로 대입합니다.

mysql_query() 함수에 대해서는 뒤에서 좀 더 자세하게 설명하기로 하고, 일단 mysql_query(역에 SQL 문을 작성)이라는 작성법만 기억합니다.

예를 들어, INSERT INTO tb1 VALUES('A101', ...)이라는 SQL 문을 작성하려면 어떻게 하면 될까요? SQL 문은 문자열 데이터이기 때문에 따옴표로 감싸야 합니다. 하지만 작은 따옴표(")를 사용하는 SQL 문에 작은따옴표(')를 감싸면 오류가 발생합니다.

mysql_query(**'**INSERT INTO tb1 VALUES('A101',...)**'**)

// 작은따옴표(')를 작은따옴표(')로 감싸면 오류 발생

이럴 때 \으로 이스케이프 하거나, 작은따옴표(')를 문자 취급하기 위해 큰따옴표(")로 감싸야 합니다.

mysql_query(**"**INSERT INTO tb1 VALUES('A101',...)**"**)

// 작은따옴표(')를 큰따옴표(")로 감싸면 OK

또한, 반대로 안쪽의 큰따옴표(")를 문자 취급하려면 작은따옴표(')로 감싸면 됩니다.

PHP와 MySQL를 이용할 때 처음에 가장 많이 당황하는 이유가 큰따옴표와 작은따옴표의 사용법 때문입니다. mysql_query() 함수에 대해서는 차차 설명하겠지만, 일단 여기에서는 작은따옴표(')에는 작은따옴표(')를, 큰따옴표(")에는 큰따옴표(")를 사용할 수 없다는 것만 기억하기 바랍니다.

2.3 변수에 사용하는 큰따옴표와 작은따옴표의 차이

문자열 데이터에는 큰따옴표(")와 작은따옴표(')중 어느 것을 사용해도 상관없지만, 변수에 사용할 때는 처리 결과가 다릅니다.

예제 16-4처럼 $a = 123이라고 입력한 경우, print "$a"는 큰따옴표(") 안의 변숫값 123을 표시합니다.

예제 16-4 double_quotation.php

<?php

$a = 123;

print "$a";

?>

![img](http://cfile9.uf.tistory.com/image/266B6E3656D2FD3E11EF95)

그러나 예제 16-5에서처럼 print '$a'라고 입력하면 작은따옴표(') 안의 변수는 문자열로 인식됩니다. 즉, $a라는 문자열이 그대로 출력됩니다.

예제 16-5 single_quotation.php

<?php

$a = 123;

print '$a';

?>

![img](http://cfile28.uf.tistory.com/image/2770583456D2FE212CEC41)

이처럼 PHP에서 생성하는 SQL 문에  문자열 데이터로 된 변수가 있을 때에는 주의해야 합니다.

**3. PHP 함수의 개요와 자주 사용하는 몇가지 함수**

****

\3. 함수

3.1 여기서 사용하는 PHP 함수

PHP에는 1,000개 이상의 함수가 있습니다. 이블로그 에서는 여기서 등장하는 함수를 소개하겠습니다.

여기서 등장하는 함수(뒤에 소개하는 date()는 제외)

| 함수명                 | 내용                         |
| ------------------- | -------------------------- |
| die()               | 스크립트의 실행을 중지한다.            |
| exec()              | 명령을 실행한다.                  |
| phpinfo()           | PHP의 정보를 표시한다.             |
| mysql_connect()     | MySQL 서버에 접속한다.            |
| mysql_close()       | MySQL 서버의 연결을 종료한다.        |
| mysql_select_db()   | 사용할 데이터베이스를 지정한다.          |
| mysql_query()       | SQL 문을 실행한다.               |
| mysql_fetch_array() | MySQL의 실행 결과에서 결과 행을 추출한다. |
| mysql_error()       | 마지막에 일어난 오류를 반환한다.         |
| getenv()            | 환경 변수를 반환한다.               |
| gethostbyname()     | 호스트 이름에서 IP주소를 가져온다.       |
| gethostbyaddr()     | IP 주소에서 호스트 이름을 가져온다.      |

mysql_로 시작하는 것은 MySQL 데이터베이스를 다루는 함수입니다(참고로, PostgreSQL을 다루는 함수는 pg_로 시작하고, SQLite를 다루는 함수는 sqlite_로 시작합니다). MySQL 데이터베이스를 다루는 함수에 대해서는 18장에서 자세히 설명하겠습니다.

여기에서는 date()와 getenv(), gethostbyaddr() 함수를 소개하겠습니다.

3.2 date() 함수로 날짜와 시간 표시하기

먼저, 날짜와 시간을 처리하는 date() 함수를 소개하겠습니다. 단, 날짜와 시간을 나타내는 함수를 사용할 때에는 사전에 표준 시간대(Time zone)를 바르게 설정해 두어야 합니다.

**date() 함수**

date(날짜와_시간_서식_문자열)

date()는 날짜와 시간을 반환하는 함수입니다. 인수에 다음과 같은 문자열을 입력하면 각 문자열에 대응하는 날짜와 시간을 반환합니다.

date() 함수에 지정할 수 있는 문자열

| 날짜와 시간 서식 문자열 | 반환값                             |
| ------------- | ------------------------------- |
| g             | 12시간제 형식으로 시간을 표시(1자릿수)         |
| h             | 12시간제 형식으로 시간을 표시(2자릿수)         |
| G             | 24시간제 형식으로 시간을 표시(1자릿수)         |
| H             | 24시간제 형식으로 시간을 표시(2자릿수)         |
| j             | 일을 표시                           |
| I             | 요일을 영문자로 표시(Saturday 등의 문자를 반환) |
| F             | 월을 영문자로 표시(January 등의 문자를 반환)   |
| n             | 월을 1자릿수로 표시                     |
| m             | 월을 2자릿수로 표시                     |
| s             | 초를 2자릿수로 표시                     |
| Y             | 연도를 4자릿수로 표시                    |
| y             | 연도를 2자릿수로 표시                    |

예를 들어, 다음 함수를 실행하면 February와 같이 현재의 월을 영문으로 표시합니다.

date("F")

그리고 다음 함수를 실행하면 현재의 월과 일을 반환합니다.

date("n")

date("j")

웹 페이지에 날짜를 자동으로 표시할 때 유용한 함수입니다. 또한, date() 함수의 2번째 인수에는 타임스탬프(timestamp)를 설정하여 지정한 날짜를 표시할 수 있습니다. 참고로, PHP에서는 날짜와 시간 정보를 '타임스탬프'라는 형식으로 처리합니다. 타임스탬프는 1970년 1월 1일 0시부터 경과한 시간을 초로 나타낸 정수입니다.

date() 함수 이용하기

그럼, 현재 날짜를 표시하는 스크립트를 만들어 보겠습니다. 예제 16-6에서처럼 현재의 날짜를 '오늘은 ХХХХ년 Х월 Х일입니다.'라고 표시하는 스크립트를 작성합니다. 이때, 문자열을 결합하기 위해 온점(.)을 사용하겠습니다.

예제 16-6 today.php

<?php

print "오늘은 ".date("Y")."년 ".date("m")."월 ".date("j")."일입니다.";

?>

![img](http://cfile5.uf.tistory.com/image/234B184156D3046D028E2E)

3.3 환경 정보

printinfo() 함수로 환경 정보 표시하기

사용하는 PHP에 관한 다양한 정보를 제공하는 함수로 phpinfo() 함수가 있습니다. 다음 스크립트를 실행하면 정보가 표시됩니다.

<?php

phpinfo();

?>

함수에는 인수를 설정하지 않더라도 괄호를 입력해야 합니다. 이 phpinfo();라는 단 한줄의 함수로 15장의 '**8.4 phpinfo()**'와 같이 많은 환경 정보가 표시됩니다.

phpinfo() 함수가 반환하는 정보 중에 **환경 변수**가 있습니다. 이는 phpinfo() 함수에 의해 표시되는 내용 중 Apache Environment 부분에 기술되어 있습니다. 환경 변수에는 '웹 서버의 소프트웨어'와 '클라이언트의 IP 주소'등 중요한 정보가 저장되어 있습니다.

또한, REMOTE_ADDR이라는 항목에는 현재 사용하는 컴퓨터의 IP 주소가 표시되어 있으니 확인해 보기 바랍니다(localhost의 경우,  IPv4에서는 127.0.0.1, IPv6에서는 ::1).

**getenv() 함수**

다음은 getenv() 함수를 사용해서 접속 중인 클라이언트의 정보를 표시하는 PHP 스크립트를 작성해 보겠습니다.

getenv() 함수는 '환경 변수'를 반환하는 함수로서 특정 인수를 지정한면 해당하는 정보를 얻을 수 있습니다.

**getenv() 함수**

getenv(얻고자 하는 정보)

getenv 함수에 설정하는 인수와 반환되는 정보

| 인수(얻고자 하는 정보)   | 얻을 수 있는 정보       |
| --------------- | ---------------- |
| SERVER_SOFTWARE | 웹 서버의 소프트 웨어     |
| SERVER_PORT     | 사용 중인 포트         |
| PATH            | 서버에 설정되어 있는 PATH |
| REMOTE_ADDR     | 클라이언트의 IP 주소     |
| HTTP_USER_AGENT | 클라이언트의 브라우저 정보   |

예를 들어, '웹 서버의 소프트웨어'는 getenv("SERVER_SOFTWARE")로 확인할 수 있습니다. 예제 16-7의 스크립트를 실행해 보겠습니다.

예제 16-7 serv_disp.php

<?php

print getenv("SERVER_SOFTWARE");

?>

![img](http://cfile22.uf.tistory.com/image/24303F3C56D30E13100D92)

마찬가지로, getenv("REMOTE_ADDR")를 이용하면 클라이언트의 IP 주소를 알 수 있습니다.

예제 16-8 ip.php

<?php

print getenv("REMOTE_ADDR");

?>

![img](http://cfile2.uf.tistory.com/image/2640714F56D30EAE2E48D2)

3.4 gethostbyaddr() 함수로 호스트 이름 확인하기

이번에는 gethostbyaddr() 함수를 사용해 보겠습니다. gethostbyaddr() 함수는 IP주소에서 호스트 이름을 가져오는 함수입니다. 참고로 'get-host-by-addr'이라고 풀어쓰면 '주소에서(by address) 호스트(host)를 얻다(get).'라는 의미인 것을 알 수 있습니다.

**gethostbyaddr() 함수**

gethostbyaddr(얻고자 하는 호스트의 IP 주소)

앞에서 getenv("REMOTE_ADDR")로 알아낸 IP 주소를 getostbyaddr() 함수의 인수로 설정하면 클라ㅣ언트의 호스트 이름을 알 수 있습니다.

예제 16-9는 클라이언트의 호스트 이름을 표시하는 스크립트 입니다.

예제 16-9 host_disp.php

<?php

print gethostbyaddr(getenv("REMOTE_ADDR"));

?>

![img](http://cfile3.uf.tistory.com/image/244E9F3656D3100B1CDD43)

gethostbyaddr() 함수 활용하기

그럼, gethostbyaddr() 함수를 사용해서 클라이언트의 정보를 반환하는 PHP 스크립트를 만들어 보겠습니다.

앞의 getenv() 함수와 인수를 사용해서 접속한 '클라이언트의 IP 주소'와 '클라이언트의 호스트 이름', '클라이언트의 브라우저 정보'를 표시하는 PHP 스크립트를 작성해 보겠습니다.

예제 16-10 client.php

<?php

print "당신의 IP 주소는 : ";

print getenv("REMOTE_ADDR");

print "<BR>";

print "당신의 호스트 이름은 : ";

print gethostbyaddr(getenv("REMOTE_ADDR"));

print "<BR>";

print "당신의 브라우저는 : ";

print getenv("HTTP_USER_AGENT");

print "<BR>입니다.";

?>

![img](http://cfile6.uf.tistory.com/image/231C4E3A56D3119F327BB2)

**4. 비교 연산자 사용법**

****

\4. 비교 연산자

앞으로 설명할 '반복 처리'와 '조건 분기'에는 설정한 조건에 일치하는지를 판단하는 부분이 있습니다. 이때 사용하는 기호를 비교 연산자라고 합니다. PHP에서는 다음과 같은 비교 연산자를 사용합니다.

비교 연산자

| 비교 연산자 | 내용          |
| ------ | ----------- |
| a==b   | a와 b는 같다    |
| a>b    | a는 b보다 크다   |
| a>=b   | a는 b이상      |
| a<b    | a는 b미만      |
| a<=b   | a는 b이하      |
| a<>b   | a는 b와 같지 않다 |

조건이 참이면 TRUE, 거짓이면 FALSE라고 합니다. '같다'를 나타내는 ==는 등호(=)를 2번 입력합니다. =가 아니니 주의하기 바랍니다.

예를 들어, 2>1은 어느 쪽일까요? 물론 이 조건은 참이기 때문에 TRUE입니다.

**5. 반복 처리 프로그래밍**

****

\5. 반복 처리

반복 처리의 장점 중 하나는 같은 내용을 수백 번이건 수천 번이건 반복해서 실행할 수 있다는 점입니다. 여기에서는 그런 반복 처리를 하는 for와 while을 소개하겠습니다.

5.1 for를 이용한 반복 처리

for란?

for는 카운터 변수(수를 세기 위한 변수)를 준비하고, 이 변수를 하나, 둘, 셋... 처럼 증가 시킴으로써 조건 범위 내에 있는 처리를 반복하는 함수입니다. for에는 '카운터 변수가 10 이하인 경우에 반복 처리를 한다.'와 같은 '조건'을 미리 설정해 둡니다. 그리고 그 조건에 충족하기 않으면(조건의 결과가 FALSE가 되면) 반복 처리를 종료하는 구조입니다.

for의 구문은 다음과 같습니다.

**for구문**

for(초깃값: 반복_조건 ; 변화){

반복해서 실행할 내용

}

중괄호{} 안에 작성한 '반복해서 실행할 내용'부분의 처리를 반복합니다. 이 부분은 몇 행에 걸쳐서 작성해도 상관없습니다. for 뒤의 괄호() 안에는 어떻게 반복할 것인지 조건을 설정합니다.

**for 사용하기**

설명만으로는 이미지가 잘 떠오르지 않을 것입니다. 그럼, 실제로 사용해 보겠습니다. 예제 16-11의 스크립트를 입력해서 실행합니다. 예제 16-11은 별표(*) 문자를 15번 반복해서 표시하는 예입니다.

예제 16-11 for.php

<?php

for($i=1;$i<=15;$i=$i+1){

print "*";

}

?>

![img](http://cfile23.uf.tistory.com/image/2173F14156D314CC33D54F)

만일, 제대로 실행되지 않는다면 쌍반점(;)이나 중괄호 등의 기호를 잘못 입력하지는 않았는지 입력 내용을 꼼꼼히 확인하기 바랍니다.

**for 문의 흐름**

그럼, 예제 16-11의 내용을 살펴보겠습니다.

● $i=1 -> 변수 $i의 처음 값은 1이다(초깃값).

● $i<=15 -> 변수 $i가 15 이하면 반복한다(반복 조건).

● $i=$i+1 -> 반복하는 동안은 1씩 증가시킨다(변화).

이 예에서는 $i를 카운터 변수로 사용하고 있습니다. 카운터 변수는 $loopv 또는 $p 등 무엇을 사용해도 상관없지만, 옛날부터 묵시적 약속처럼 '카운터 변수는 $i'가 사용되고 있습니다.

카운터 변수의 초깃값으로 $i=1이 설정되어 있습니다. 즉, '카운트는 1부터 시작한다.'라는 의미입니다. 그리고 반복 조건이 $i<=15라고 되어 있는데, 이는 '카운터 변수 $i가 15이하이면 이 처리를 반복하시오.'라는 의미입니다. 15 이하라는 것은 당연히 15도 포함됩니다.

변화는 $i=$i+1이라고 되어 있습니다. 이는 '카운터 변수 $i를 1씩 증가시킨다.'라는 의미입니다.

프로그램의 세계에서 등호(=)는 우변의 값($i+1)을 좌변($i)에 대입한다는 의미입니다. 변수 $i에 1을 더하고 그 결괏값을 변수 $i에 대입합니다. 즉, 변수 $i를 1씩 증가시키는 꼴이 됩니다.

초깃값은 $i=1에 의해 1이 됩니다. 여기에 $+1에 의해 1이 더해져서 2가된 값을 등호로 왼쪽의 변수 $i에 대입해서 $i는 다시 2가 됩니다. 계속해서 $+1에 의해 1이 더해져서 3이 된 값을 변수 $i에 대입해서 변수 $i는 3이 되고... 이런식으로 1씩 증가하게 됩니다.

$i=$i+1을 생략하고 $i++라고 작성할 수도 있습니다. 이를 **인크리먼트**(increment)라고 합니다. 즉, 예제 16-11을 다음과 같이 작성해도 결과는 같습니다. $i=1는 1부터, $<=15는 15 이하일 때, $i++는 1을 더한다라는 처리를 하고 있습니다.

예제 16-12 for_variation.php

<?php

for($i=1;$i<=15;$i++){

print "*";

}

?>

5.2 while을 이용한 반복 처리

다음은 while을 이용한 반복 처리입니다. 이번에는 '반복 조건'이 참(TRUE)이면 '반복 처리'부분을 반복합니다. while의 구문은 다음과 같습니다.

**while 구문**

while(반복_조건){

반복 처리

}

while에는 별도로 카운터 변수의 초깃값을 설정하는 부분이 없기 때문에, 스스로 초깃값을 설정해야 합니다. 또한, 반복 중에 반드시 '반복 조건'이 거짓(FALSE)이 되도록 해야 합니다. 만일, 계속해서 '반복 조건'이 참이면, 반복 처리는 영원히 계속되니 주의해야 합니다.

while 사용하기

앞선 예에서는 for를 사용해서 별표(*)를 15회 출력했는데 이번에는 while을 사용해서 같은 내용을 실행해 보겠습니다.

예제 16-13에서는 먼저 카운터 변수 $i에 1을 대입합니다. 그리고 print "*";를 실행할 때마다 변수 $i를 1씩 증가시키는데 이 작업을 while로 반복합니다. 반복 조건은 '변수 $i가 15 이하'입니다.

예제 16-13 while.php

<?php

$i=1;

while($i<=15){

print "*";

$i++;

}

?>

$i=1;에서 $i에 1을 대입하고 조건을 확인합니다. 처음의 변수 $i는 1이기 때문에 <=15(15 이하)라는 조건에 참(TRUE)을 반환하므로 print "*"가 실행되어 *가 출력됩니다.

다음은 $i++;에서 변수 $i가 1 증가해서 2가 됩니다. 그리고 다시 while로 돌아가서 while($i<=15) 조건이 참인지 확인합니다.

이 작업을 반복해서 $i++;로 변수 $i를 증가시킨 값이 16이 되면, 조건을 만족하지 않으므로(FALSE) 16번째는 출력하지 않고 처리가 종료됩니다.

5.3 do~while을 이용한 반복 처리

while과 비슷한 구문으로 do~while이 있습니다. while과 다른 점은 조건을 검사하는 처리를 나중에 한다는 것입니다.

**do~while 구문**

do{

반복 처리

}while(반복_조건)

다음을 실행하면 예제 16-13과 같은 결과를 얻을 수 있습니다.

예제 16-14 do_while.php

<?php

$i=1;

do{

print "*";

$i++;

}while($i<=15)

?>

먼저, $i=1에서 1을 대입하고, $i++에서 1을 증가시키고, while($i<=15) 에서 15 이하일 때 라는 처리를 하고 있습니다.

주의할 점은 while의 경우에는 조건을 먼저 검사하기 때문에, 만일 조건에 일치하지 않으면 단 한번의 처리도 이루어지지 않고 종료한다는 것입니다. 그러나 do~while의 경우에는 조건을 마지막에 검사하기 때문에 적어도 1번은 실행됩니다.

 

**6. 조건 분기 프로그래밍**

****

\6. 조건 분기

6.1 if를 이용한 조건 분기

if는 조건에 따라 실행할 내용을 변화시킵니다. PHP 스크립트에서는 다음과 같이 사용합니다.

**if 구문**

if(조건){

조건이 참일 때 실행하는 처리

}else{

조건이 거짓일 때 실행하는 처리

}

괄호() 안의 조건이 참(TRUE) '조건이 참일 때 실행하는 처리'를 실행하고, 그렇지 않으면 '조건이 거짓일 때 실행하는 처리'를 실행합니다.

**if 문의 흐름**

예제 16-15의 예를 실행해 보겠습니다.

예제 16-15 condition.php

<?php

if(200>100){

print "큽니다.";

}else{

print "작습니다.";

}

?>

![img](http://cfile29.uf.tistory.com/image/257C5F4456D31BFF02AC47)

'A>B'는 'A는 B보다 크다.'라는 의미 입니다. '200과 100 중에 어느 쪽이 큰가?'라고 했을 때, 당연히 200이 큽니다. 즉, '만일 200이 100보다 크다면'(200>100)이라는 조건을 검사합니다. 이 조건은 참이기 때문에 구문중 '조건이 참일 때 실행하는 처리'가 실행됩니다.

만일, 조건이 거짓인 경우에는 else 안의 내용을 실행합니다. 참고로, 이번에는 이 구문은 실행되지 않습니다.

물론, 실제 스크립트에서는 '200>100'과 같은 당연한 조건을 설정할 일은 없습니다. 예를 들어, '데이터베이스에 접속했다면'이나, '지정한 문자가 포함되어 있다면'과 같이 데이터 처리에 필요한 판단을 할 때 이용됩니다. 또한, 구문 중의 else(조건이 거짓일 때~)의 부분은 필요없다면 생략해도 됩니다. 생략하면 조건이 참일 때에만 해당 처리가 실행되고, 그렇지 않으면 아무것도 실행되지 않습니다.

6.3 여러 개의 조건을 설정한 if 구문

if에는 조건식을 몇개라도 설정할 수 있습니다. 다음은 여러 개의 조건을 설정한 구문입니다.

**여러 개의 조건을 설정한 if 구문**

if(조건1){

조건1 이 참일 떄 실행하는 처리

}else if(조건2){

조건2 가 참일 떄 실행하는 처리

}else if(조건3){

조건3 이 참일 떄 실행하는 처리

....

}else{

모든 조건이 참이 아닐 때 실행하는 처리

}

여러 개의 조건을 설정한 if 문의 처리는 다음과 같습니다.

조건1이 참(TRUE)이면 조건1이 참일 때 실행하는 처리 부분을 실행하고, 그렇지 않으면

▽

조건2가 참(TRUE)이면 조건2가 참일 때 실행하는 처리 부분을 실행하고, 그렇지 않으면

▽

....

모든 조건이 참이 아니면 모든 조건이 참이 아닐 때 실행하는 부분을 실행하다.

**저장 프로시저에서 조건 분기 사용하기**

여기서는 사용하고 있지 않지만, MySQL의 저장 프로시저에서도 if를 사용해서 조건 분기를 할 수 있습니다.

**여러개의 조건을 설정한 if 문의 흐름**

그럼, 약간 복잡한 처리를 해보겠습니다. 접속한 시간에 따라 변화하는 인사 메시지를 만들어 보겠습니다. 현재 시각은 date("G")로 구할 수 있습니다. 즉, date("G")의 값이 18 이상과 date("G")의 값이 9 이상... 이라는 조건을 설정하고 if로 분기 처리를 합니다.

구체적으로, 0시부터는 '졸리지 않나요?', 6시 부터는 '일어나세요.', 9시 부터는 '좋은 아침 입니다.', 18시 부터는 '퇴근할 시간이네요.'라고 표시되는 예제 16-6을 만들어 보겠습니다.

예제 16-16 if.php

<?php 

​	if (date("G")>=18) {

​		print "퇴근할 시간이네요.";

​	}elseif (date("G")>=9) {

​		print "좋은 아침입니다.";

​	}elseif (date("G")>=6) {

​		print "일어나세요.";

​	}else{

​		print "졸리지 않나요?";

​	}

?>

![img](http://cfile30.uf.tistory.com/image/2552DA4E56D3215939ACB2)

실행한 시간에 따라 해당하는 문자열이 표시됩니다.

6.3 switch를 이용한 분기

변숫값에 따라 각각 다른 처리를 실행할 때에는 **switch**를 사용합니다. 예를 들어, 변수 $i가 1일 때에는 ХХ, 변수 $i가 2일 때에는 △△, 변수 $i가 3일 떄에는 ◯◯...을 실행하는 처리를 할 수 있습니다.

이 처리는 if문을 사용해서 똑같이 실행할 수 있습니다. 그러나 switch를 사용하면 좀 더 알기 쉽게 표현할 수 있습니다.

switch 구문은 다음과 같습니다.

**switch 구문**

switch(변수){

case 변숫값 1:

처리 1

break;

case 변숫값 2:

처리 2

break;

...

default;

모든 조건이 참이 아닐 때 실행하는 처리

}

switch에 설정한 변수의 값이 case에 설정한 값과 일치하면, 해당하는 처리가 실행됩니다. 각각의 처리 뒤에는 반드시 **break**를 기술합니다. break는 처리를 종료하는 명령입니다.

일치하는 값이 없으면 default;에 설정한 처리가 실행됩니다.

switch 문의 흐름

예제 16-7은 10시에는 '10시 간식입니다.', 15시에는 '3시 간식입니다.', 10시와 15시 외에는 '간식 시간이 아닙니다.'라고 표시되는 예입니다.

예제 16-17 snack.php

<?php 

​	switch (date("G")) {

​		case 10:

​			print "10시 간식입니다.";

​			break;

​		case 15:

​			print "3시 간식입니다.";

​			break;

​		default:

​			print "간식 시간이 아닙니다.";

​			break;

​	}

?>

각각의 처리 뒤에 break를 기술하는 것을 잊지 않도록 합니다. 만일, break를 기술하지 않으면 그 뒤의 처리는 실행되지 않습니다. 그리고 case 변숫값1:과 같이 쌍점(:)에도 주의하기 바랍니다.

![img](http://cfile21.uf.tistory.com/image/257BD64056D56A2A3A21C9)

이번에는 switch를 사용해서 다음과 같은 연결 모양을 출력해 보겠습니다.

◎★◯▽▲◎★◯▽▲◎★◯▽▲◎★◯▽▲◎★◯▽▲.....

for를 이용해서 1~5까지의 값을 변수에 대입하고, switch를 이용해서 CASE에 설정한 각각의 처리를 합니다. 그리고 이를 다시 for를 이용해 반복하는 방법입니다.

예제 16-18은 변수 $y가 1이면, ◎, 2면 ★, 3이면 ◯, 4이면 ▽, 5이면 ▲를 출력하는 처리를 8번 반복해서 앞의 '◎★◯▽▲'를 8연속 출력합니다.

예제 16-18 switch.php

<?php 

​	for ($x=1; $x <= 8; $x++) { 

​		for ($y=1; $y <= 5; $y++) { 

​			switch ($y) {

​				case 1:

​					print "◎";

​					break;

​				case 2:

​					print "★";

​					break;

​				case 3:

​					print "◯";

​					break;

​				case 4:

​					print "▽";

​					break;

​				case 5:

​					print "▲";

​					break;

​			}

​		}

​	}

?>

![img](http://cfile7.uf.tistory.com/image/240BDB3F56D56BF012E932)

처리 내용을 살펴보겠습니다.

먼저, 다음과 같이 변수 $y가 1이면 ◎, 2이면 ★와 같이 분기 처리를 합니다.

| 1234567891011121314 | <?php     switch ($y) {        case 1:            print "◎";            break;        case 2:            print "★";            break;        ~ 중간 생략 ~        case 5:            print "▲";            break;    }?> | [cs](http://colorscripter.com/info#e) |
| ------------------- | ---------------------------------------- | ------------------------------------- |
|                     |                                          |                                       |

그리고 이  switch문을 다음과 같이 for 문으로 반복합니다.

| 123456789101112131415161718192021 | <?php     for ($y=1; $y <= 5; $y++) {         switch ($y) {            case 1:                print "◎";                break;            case 2:                print "★";                break;            case 3:                print "◯";                break;            case 4:                print "▽";                break;            case 5:                print "▲";                break;        }    }?> | [cs](http://colorscripter.com/info#e) |
| --------------------------------- | ---------------------------------------- | ------------------------------------- |
|                                   |                                          |                                       |

변수 $y는 1, 2, 3, 4, 5로 증가하기 때문에, ◎★◯▽▲가 각각 출력됩니다.

이 카운터 변수 $y를 이용한 for 문을 카운터 변수 $x를 이용한 for 문으로 8번 반복합니다.

| 1234567891011121314151617181920212223 | <?php     for ($x=1; $x <= 8; $x++) {         for ($y=1; $y <= 5; $y++) {             switch ($y) {                case 1:                    print "◎";                    break;                case 2:                    print "★";                    break;                case 3:                    print "◯";                    break;                case 4:                    print "▽";                    break;                case 5:                    print "▲";                    break;            }        }    } ?> | [cs](http://colorscripter.com/info#e) |
| ------------------------------------- | ---------------------------------------- | ------------------------------------- |
|                                       |                                          |                                       |

참고로, 여는 중괄호 {와 닫는 중괄호 }는 1대 1이어야 합니다.

**7. 배열 사용법**

****

\7. 배열

7.1 배열이란 무엇인가?

지금까지 사용하 변수는 $i=100과 같이 1개의 값만 저장했습니다. 사실은 1개의 값처럼 보이지만, 더욱 많은 값을 저장할 수 있는 편리한 변수가 있습니다. 이를 **배열**이라고 합니다.

'일반 변수가 아닌 배열 변수'로 선언하는 방법은 몇 가지가 있지만, 가장 먼저 array()라는 함수를 소개하겠습니다. 그리고 배열 변수의 이름에도 16장 1.2 변수 이름의 규칙 에서 다룬 규칙중 하나가 적용됩니다.

예를 들어, $m이라는 변수를 배열로 선언해서 그 안에 많은 값을 저장하려면 다음과 같이 선언합니다.

$m = array("쥐", "소", "호랑이", "토끼", "Dragon");

이렇게 하면 $m이라는 하나의 변수에 '쥐', '소', '호랑이', 'Dragon'이라는 5개의 문자열이 저장됩니다. PHP에서는 '데이터를 대입하면 자료형이 알아서 설정된다.'라고 했기 때문에 $m은 문자열 자료형의 배열 변수가 됩니다.

다음은 배열에서 각각의 값을 추출하는 방법입니다. 예를 들어, 앞의 값(문자열)은 왼쪽부터 각각 1번째는 $m[0], 2번째는 $m[1], 3번째는 $m[2]... 이라는 이름으로 저장됩니다. 값을 꺼낼 때에도 그 이름을 사용합니다. 즉, print $m[2]; 를 실행하면 '호랑이'가 출력됩니다. '소'가 아니니 주의하기 바랍니다.

저장된 값과 배열 변수

| 배열 변수 | 저장된 값  |
| ----- | ------ |
| $m[0] | 쥐      |
| $m[1] | 소      |
| $m[2] | 호랑이    |
| $m[3] | 토끼     |
| $m[4] | Dragon |

대괄호 [] 안의 숫자로 '몇 번째 값'인지를 판단합니다. 이 [] 안의 숫자를 **첨자**라고 합니다. 첨자는 0부터 시작합니다. 그렇기 때문에, 배열의 마지막 첨자는 배열의 전체 수보다 1 작다는 점에 주의하기 바랍니다.

참고로, 앞의 예에서 5번째의 'Dragon'은 $m[5]가 아닌 $m[4]입니다.

7.2 배열의 값을 대입하는 방법

다음은 array() 하수를 사용하지 않고 배열 변수에 값을 대입하는 방법입니다.

**직접 대입하기**

$m[4] = "Dragon";

$m[0] = "쥐";

$m[2] = "호랑이";

$m[1] = "소";

$m[3] = "토끼";

이때는 순서에 관계없이 대입할 수가 있습니다. 또한, $m[777] = "학문"과 같이 첨자를 순서대로 사용하지 않아도 상관없습니다.

**순서대로 대입하기**

$m[] = "쥐";

$m[] = "소";

$m[] = "호랑이";

$m[] = "토끼";

$m[] = "Dragon";

이렇게 하면 가장 먼저 대입한 값부터 $m[0], $m[1]... 이 됩니다. for나 while을 사용해서 반복해서 값을 대입하면 편리합니다.

첨자를 사용하는 방법은 익숙하지 않으면 틀리기 쉬우니, 세심한 주의가 필요합니다.

배열을 사용한 예

예제 16-19는 예제 16-16을 배열을 사용해서 수정한 예입니다. 배열 변수 $m에 '졸리지 않나요?'와 '좋은 아침입니다.', '일어나세요.', '퇴근할 시간이네요.'를 대입해서, 0시부터 '졸리지 않나요?', 6시부터 '일어나세요.', 9시부터 '좋은 아침입니다.', 18시부터 '퇴그날 시간이네요.'라고 표시합니다.

예제 16-19 squence.php

| 123456789101112 | <?php     $m = array("졸리지 않나요?", "일어나세요.", "좋은 아침입니다.", "퇴근할 시간이네요.");    if (date("G")>=18) {        print $m[3];    }elseif (date("G")>=9) {        print $m[2];    }elseif (date("G")>=6) {        print $m[1];    }else{        print $m[0];    }?>[Colored by Color Scripter](http://colorscripter.com/info#e) | [cs](http://colorscripter.com/info#e) |
| --------------- | ---------------------------------------- | ------------------------------------- |
|                 |                                          |                                       |

 

2번 라인의 "졸리지 않나요?"sms $m[0], "좋은 아침입니다."는 $m[1], "일어나세요."는 $m[2], "퇴근할 시간이네요."는 $m[3]에 대입됩니다.

**첨자의 숫자 설정은 적당하게...**

첨자를 몇 개 사용하지도 않으면서 $m[777]="학문"과 같이 너무 동떨어진 숫자를 설정하면 쓸데없이 메모리를 소비하게 됩니다. 될 수 있으면 필요한 만큼만 첨자를 설정하도록 합니다.

7.3 연관 배열

첨자는 순서를 나타내는 숫자 외에도 사용자가 정한 문자를 사용할 수 있습니다. 이를 **연관 배열**이라고 합니다.

예를 들어, 시험 점수를 저장하는 배열 변수에서 영어는 $t["eng"], 국어는 $t["kor"]...과 같이 직관적으로 알기 쉬운 첨자를 설정할 수가 있습니다.

예제 16-20은 연관 배열을 사용한 예입니다. '합계 점수는:225'라고 표시됩니다.

예제 16-20 relation.php

| 1234567 | <?php     $t["eng"] = 73;    $t["math"] = 84;    $t["kor"] = 68;    print "합계 점수는 ";    print $t["eng"] + $t["math"] + $t["kor"]; ?>[Colored by Color Scripter](http://colorscripter.com/info#e) | [cs](http://colorscripter.com/info#e) |
| ------- | ---------------------------------------- | ------------------------------------- |
|         |                                          |                                       |

![img](http://cfile1.uf.tistory.com/image/2234C23E56D5749E342C34)

**연관 배열의 첨자나 큰따옴표(")나 작은따옴표(')를 사용하지 않아도 동작한다!?**

연관 배열의 첨자에는 큰따옴표(") 또는 작은따옴표(')를 사용하는 것이 정석입니다. 그러나 $m[eng]와 같이 연관 배열에 큰따옴표(")나 작은 따옴표(')를 사용하지 않아도 대개 아무런 문제 없이 동작합니다.

▶ 동작은 하지만 정석이 아닌 예

| 1234567 | <?php     $m[kim] = 100;    $m[lee] = 200;    print $m[lee];    print "<BR>";    print $m[kim]; ?> | [cs](http://colorscripter.com/info#e) |
| ------- | ---------------------------------------- | ------------------------------------- |
|         |                                          |                                       |

앞의 예는 정상적으로 실행됩니다. 하지만 엄밀히 말하면 잘못된 작성법으로 본래는 $m["kim"], $m["lee"] 라고 작성해야 합니다. $m[kim] 이나 $m[lee] 라고 작성해도 눈에 보이는 오류는 표시되지 않지만, 사실은 작은 오류가 발생한 상태입니다. 그러나 PHP에는 가능한 한 최선을 다해 스크립트를 해석하는 기능이 있습니다. 눈앞에 오류가 표시되지 않는다고해도 오류가 없는 것은 아니니 연관 배열의 첨자는 반드시 큰따옴표(")나 작은따옴표(')를 사용하도록 합니다.

****

**※ 근데 저는 위의 저 코드는 오류를 발생하고 있습니다. 버전이 올라가서 그런듯 합니다.**

이 장의 내용은 모두 MySQL과 연계하는 데 필요한 내용입니다. 특히, 프로그램 언어를 처음 접하는 분이라면 for나 while, switch 등은 프로그램 언어의 기본이니 사용 방법에 익숙해지도록 합시다.

체크!

★ PHP의 변수 이름 규칙을 이해하고 있다.

★ PHP에서 문자열을 결합하는 방법을 이해하고 있다.

★ 변수에 사용하는 큰따옴표(")와 작은 따옴표(')의 차이점을 이해하고 있다.

★ 날짜와 시간을 표시할 수 있다.

★ 클라이언트의 IP 주소와 웹 서버의 정보를 표시할 수 있다.

★ for를 이용한 반복 처리를 이해하고 있다.

★ while을 이용한 반복 처리를 이해하고 있다.

출처:  http://recoveryman.tistory.com/206  [회복맨 블로그]
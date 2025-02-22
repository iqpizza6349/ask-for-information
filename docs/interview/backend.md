---
id: backend
title: 백엔드
---

> 본 문서는 직접 면접을 응시한분들이 작성하는 문서이며, 기업 보안 관련 문제에 대한 이슈가 발생할 시 해당 기업의 내용을 제거할 예정입니다.

## 당근마켓

:::note
면접시간: 1시간
:::

- 간단 자기소개
- 자바스크립트의 객체지향 특징
- 프로토타입을 사용하며 얻는 장점
- 자바스크립트에서 프로토타입을 설정하는 방법
- 자바스크립트에서 부모와 자식이 같은 프로퍼티를 가진다며 부모의 프로퍼티에 접근하느 방법
- 프로토타입을 사용하여 private를 만드는 방법
- 클로저란?
- NodeJS가 비동기를 처리하는 방식
- NodeJS에서 결구 쓰레드를 사용하게 되는데 그렇다며 멀티쓰레드인가?
- 멀티쓰레딩의 문제점
- 교착상태란?
- 교착상태를 해결하는 방법
- 자바의 synchronized가 내부적을 동작하는 방법
- 싱글쓰레드의 이점
- DB의 트랜잭션 격리 수준에 대해 설명하라
- DB에 트랜잭션이 필요한 이유
- DB 인덱스란?
- DB 인덱스의 동작 원리
- DB 인덱스에 사용하는 자료구조
- B-트리 어떻게 동작하는가?
- DB 인덱스가 B+, B-트리를 많이 사용하는 이유
- DB 인덱스를 사용하기 좋은 경우는?
- XXS란?
- CSRF란?
- CORS란?
- 서버에서 로그인을 구현할때 사용한 방법
- JWT의 장/단점
- JWT의 보안취약점을 해결하기 위한 방법
- Session의 장/단점
- HTTPS에 대해 설명하라, HTTPS의 인증방식은?
- OAuth의 인증방식을 설명해보아라

## FLO

:::note
면접시간: 1시간
:::

- Java 메인 클래스의 A메서드에서 인스턴스를 생성하고 다른 함수에 넘겨줬을 때 그 함수에서 해당 인스턴스를 다른 인스턴스로 변경할 경우 리턴하지 않아도 메인 클래스의 A메서드에 영향을 미치는가
- Java final의 의미와 사용하는 경우
- Java Checked Exception vs Unchecked Exception 차이
- Java Spring에서 @Transactional 속성과 동작 방식
- JavaScript 익명 함수와 클로저의 차이점
- JavaScript 자유 변수란
- JavaScript 일급 객체란
- GO 장점인 동시성, 병렬형 프로그래밍을 이용해 개발했는지
- GO 인터페이스 타입이 자바 오브젝트처럼 동작할 수 있는 이유
- GO 구현을 목적으로 리시버 메서드를 생성할 때 포인터로 받을 때와 값으로 받을 때 나누는 기준
- GO Buffered channel vs Unbuffered channel 퍼포먼스 면에서 차이점
- GO 채널을 통해 값을 주고받을 때 고루틴이 어떻게 상호작용 하는지 동작 원리 
- Database 카디널리티에 대해 설명
- Database 1:N 관계 테이블에서 1이 Optional일 경우와 Optional이 아닐 경우 차이
- Database ERD에서 실선, 점선, 그리고 까마귀발과 고리의 의미와 차이점
- Database Join 중 한 가지를 구체적으로 설명 
- Docker와 Docker Compose 사용한 이유
- Docker Service 삭제하는 법
- GO, JAVA, PYTHON를 사용하는 이유을 각각 구체적으로 설명

## FLO(2차)

:::note
면접시간: 2시간

라이브 코딩 1시간 + 질의응답 1시간
:::

- @Controller와 @RestController의 차이점과 동작 원리
- POST, PATCH method를 사용할 때 어떤 식으로 값을 받는가
- RESTful API는 어떤 것이라고 생각하는지, 얼마나 관심있는지
- ```Map<Integer, String> map = new HashMap<>()``` 에서 해시맵을 생성할 때 타입을 생략할 수 있는 이유는 무엇인가
- HashMap은 thread-safe하지 않은데, 이를 thread-safe하게 만들어 보아라
- Java에서 String은 메모리 구조 중 어디에 할당되는가 (+ Python, GO)
- String을 사용하지 않고 StringBuilder을 사용한 이유는 무엇인가
- Builder 패턴을 쓰는 이유 중 가장 중요한 이유는 무엇이라 생각하는지
- Slf4j를 사용하여 로그를 출력할 수 있는 이유는 어딘가에 객체가 생성되서일 것인데, 그 때 생성된 객체를 확인하는 방법은 무엇인가
- Java 메인 클래스의 A메서드에서 인스턴스를 생성하고 다른 함수에 넘겨줬을 때 그 함수에서 해당 인스턴스를 다른 인스턴스로 변경할 경우 리턴하지 않아도 메인 클래스의 A메서드에 영향을 미치는가
- 클로저란 무엇인가
- Java는 일급 객체인가(+ GO)

## 빅픽처인터렉티브

:::note
면접시간: 40분
:::

- GO언어를 시작하게 된 계기
- Spring IOC & DI & AOP란
- @Autowired를 사용하여 의존성 주입을 하였을 때 일어날 수 있는 문제점과 그를 해결할 수 있는 방안
- Spring AOP에서 Pointcut과 JoinPoint 등 각 용어들의 동작 방식에 대해 설명
- Java Reflection의 동작 원리를 설명
- 만약 랜덤채팅 서비스에 사용자가 많아져 1대의 서버로 동작할 수 없게 됐을 때 어떻게 할 건지 구체적으로 설명
- 서버를 많이 둔다면 클라이언트가 어떤 기준으로 무슨 서버에 요청해야 할 건지 어떻게 구분할지
- 핸들링 전용 서버를 만든다면 같은 채팅방에 있는 유저에게 제대로 채팅이 전송될지 
- MySQL로 선착순 100명에게 쿠폰을 나눠주려고 할 때 어떻게 할 건지 구체적으로 설명
- SERIALIZABLE을 사용하여 나눠줄 경우 100번째 받는 사용자는 어떻게 처리될지 

## 오후두시랩

:::note
면접시간: 1시간

질의응답 40분 + 라이브 코딩 20분
::

- 간단 자기소개
- 마이스터고를 선택한 이유 및 백엔드 분야를 선택한 이유
- Restful API의 정의
- TCP 및 UDP의 차이
- TCP, UDP 등과 웹 통신에서 사용되는 HTTP 프로토콜의 차이
- 프로세스 및 스레드의 차이
- DB 트랜잭션의 정의 및 동작 과정
- 프로젝트에서 DB 정규화는 어떻게 진행했는지
- 리눅스(Linux)에서 스크립트를 만들고 실행할 때 해야 하는 작업 (실행 권한 할당)
- 인터페이스와 구현체를 따로 만드는 이유
- 스프링의 IoC, DI를 설명
- 스프링 컨테이너를 설명
- AWS의 VPC 및 보안 그룹 설명
- Linked List를 이용해 스택 메서드를 구현 (라이브 코딩)
- Java에서 Thread-safe하게 개발하는 방법
- Java Lock 인터페이스의 구현체 종류 및 특징 (ReentrantLock, ReadWriteLock)

## 테크타카(ARGO)

:::note
면접시간: 30분
:::

- 간단 자기소개
- HTTP METHOD (GET, POST, PUT, PATCH, DELETE)의 사전적 정의와 서버가 수행하는 동작
- HTTP STATUS code의 200대, 400대, 500대 별 의미
- String 리터럴과 new String의 차이
- 동일성(```==```), 동등성(```equals```)
- Array, List, Set, Map 의 특징들
- Array와 List 차이점
- List와 Set의 contains 메소드의 시간복잡도
- hashcode를 override 하지 않고 equals만 override 했을 때 발생할 수 있는 이슈
- HashSet, HashMap에서 hashing 충돌이 발생하게 되는 경우, 어떻게 처리되는 지 설명
- hashing 충돌이 발생했을 때 해결하는 방법 1가지
- 해당 알고리즘(구구단과 간단한 알고리즘)의 시간복잡도와 그 이유를 구체적으로 설명
- ```@GenerateValue(strategy=GenerationType.IDENTITY)``` 전략으로 ID를 가진 Entity를 구성하였을 때, 엔티티에 id를 임의로 넣어서 save했을 때와 그렇지 않을 때의 차이를 구체적으로 설명
- JPA Entity가 반드시 필연적으로 ID를 사용자 입력으로 받는다면, select 쿼리가 추가로 발생하게 되는 데 select 쿼리가 추가적으로 생기지 않도록 하는 구체적인 방법 설명
- JPA를 사용하면서 겪은 문제와 해결방법 구체적으로 설명
- 최근 읽거나 읽은 전공 도서

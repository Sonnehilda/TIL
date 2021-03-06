# REST

## 네트워크 소프트웨어 아키텍쳐

---

- 네트워크에서 통신을 구성할 때 이런 구조로 설계하라는 지침 정도로 볼 수 있겠다.
- '웹' 기반의 전송을 위해 쓰이는 경우가 대부분이다.
    - *웹 API 쪽에서 굉장히 많이 쓰인다.*
    - *'REST API’ 라고 부르는데, 이제는 그냥 '웹 API'와 동일하다고 볼 수 있을 정도로 보편화되었다.*

## 조건

---

- Client-Server : 클라이언트와 서버로 분리되어야하며 서로 의존성이 없어야 한다.
- Stateless (무상태성) : 상태 정보를 따로 저장하지 않으며, 이용자가 누구인지 혹은 어디서 접근하는지와 관계 없이 결과가 무조건 동일해야 한다.
    - *현실적으로 무상태성 조건을 가만히 놔두면 디도스 공격의 위험에 노출되기 쉽다.*
    - *이를 위해 OAuth 2.0 (또는 OpenID)을 대표적으로 사용한다.*
- Cache - HTTP를 비롯한 네트워크 프로토콜에서 제공하는 캐싱 기능을 적용할 수 있어야 한다.
- Uniform Interface - 데이터가 표준 형식으로 전송될 수 있도록 구성 요소 간 통합 인터페이스를 사용한다.
- Layered System - API는 REST 조건을 만족하면 필연적으로 오픈될 수 밖에 없기 때문에, 요청된 정보를 검색하는데 있어 계층 구조로 분리되어야 한다.
- Self-descriptiveness - API를 통해 전송되는 내용은 별도 문서 없이 쉽게 이해할 수 있도록 자체 표현 구조를 지녀야 한다.

## 메소드 (Method)

---

[해당 문서 (HTTP : 메소드) 를 참고.](https://www.notion.so/HTTP-245184e444b8471fb6e1523195ecf67d)

| POST | 자원 생성 (Create) |
| --- | --- |
| GET | 자원 조회 (Read) |
| PUT | 자원 수정 (Update) |
| DELETE | 자원 삭제 (Delete) |

## 메시지 (Message)

---

[해당 문서 (HTTP : 응답 코드) 를 참고.](https://www.notion.so/HTTP-245184e444b8471fb6e1523195ecf67d)
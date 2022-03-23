# API

### Application Programming Interface, 응용 프로그램 프로그래밍 인터페이스

---

- 프로그램을 작성하기 위한 일련의 부 (Sub) 프로그램이다.
- [라이브러리](https://www.notion.so/Library-285b2a38cf9f4e409eb8dadca32d7d26)와 종종 헷갈리곤 하는데, 서로 다르다.
    - *API의 핵심은 정의된 프로토콜을 기반으로 상호 작용을 할 수 있도록 일종의 약속된 시스템이라고 볼 수 있다.*
    - *라이브러리는 실제 이를 바탕으로 구현된 결과물이다.*
- [프레임워크](https://www.notion.so/Framework-8dc294911f1b4732b54a7a7c1b23b926)는 그것을 기반으로 명확하게 정의된 대량의 라이브러리가 있다는 점에서 API와 비슷하다.
    - *하지만 일반적인 API는 전체 제어 구조를 호출하는 쪽에서 원하는대로 진행할 수 있지만, 프레임워크에서는 그럴 수 없는 경우가 많다는 점이 다르다.*
- 일반인이 흔히 접할 수 있는 것은 아무래도 [HTTP](https://www.notion.so/HTTP-245184e444b8471fb6e1523195ecf67d) 기반의 웹에서 사용되는 [REST](https://www.notion.so/REST-b797027aae934d919a3fa6a1abd47951)ful API다.

## 설명

---

- API 자체는 사양 (specification) 만을 정의하기 때문에 구현 (Implementation) 과는 독립적이다.
- API는 다양한 형태로 존재한다.
    - *유닉스의 POSIX 표준*
    - *윈도우의 MFC나 Win32*
    - *C++의 표준 템플릿 라이브러리 (STL)*
    - *Java SE API*
- 프로그램에 플러그인 형태로 설계된 API가 적용되면, 이미 작성되어 컴파일되고 완성된 프로그램의 수정없이 프로그램의 기능을 추가하는 것이 가능하다.
- API가 실제 기능 구현체인 라이브러리와 함께 제공되는 경우도 있으며, 이 경우를 SDK (Software Development Kit) 라고 한다.
- SDK는 일반적으로 API, 라이브러리와 함께 프로그램을 개발하는데 필요한 여러 보조 프로그램을 포함한다.

> 한마디로, API는 소스 코드 수준에서 정의되는 인터페이스라고 할 수 있다.
> 

## RESTful API

---

[해당 문서 (REST) 를 참고.](https://www.notion.so/REST-b797027aae934d919a3fa6a1abd47951)
# 성공과 실패를 결정하는 1%의 네트워크 원리 스터디

[1% 네트워크 원리](https://product.kyobobook.co.kr/detail/S000000559964) 책 내용을 정리하여 발표 및 인터뷰 형식으로 진행

## 🗓 기간

- 2023-08-10(목) ~ 2023-10-26(목)
- 3개월
- 매주 목요일 오후 8시에 디스코드에서 진행

## 👨‍👩‍👧 인원

- 6명
- 발표 순서

  |![image](https://avatars.githubusercontent.com/u/92148749?v=4)|![image](https://avatars.githubusercontent.com/u/141324304?v=4)|![image](https://avatars.githubusercontent.com/u/82931413?v=4)|![image](https://avatars.githubusercontent.com/u/116046530?v=4)|![image](https://avatars.githubusercontent.com/u/77628363?v=4)|![image](https://avatars.githubusercontent.com/u/65996149?v=4)|
  |:---:|:---:|:---:|:---:|:---:|:---:|
  |[김유빈](https://github.com/kyukong)|[김희연](https://github.com/YeonieKim)|[신동희](https://github.com/easydong02)|[박수원](https://github.com/Suwon-Park)|[이나연](https://github.com/yeon2lee)|[오유라](https://github.com/o-dev-lab)|

## 🚀 진행내용

- 모든 인원은 일주일에 한 번씩 깃허브에 학습 내용을 정리해요.
- 발표자는 학습한 내용을 다른 팀원들에게 발표해요.
- 발표자 외 다른 팀원들은 발표자에게 인터뷰를 진행해요.
- 서기는 인터뷰 질문들은 모두 기록해요.

## 📑 진행방식

### 1. 학습 내용 깃허브 정리

- 스터디 레포지토리를 `fork` 하여 개인 레포지토리에 저장해요.
- 이번주 챕터에 해당하는 폴더에 `.md` 파일로 학습 내용을 정리해요.
    - 정리 방식이나 분량은 제한이 없어요.
    - 다른 팀원들의 파일과 겹치지 않도록 파일명은 이름으로 작성해요. (ex. 김유빈.md)
- 스터디 레포지토리에 PR 을 보내요.
    - PR 제목 : X주차 ChapterXX StoryXX~XX 김유빈
    - **수요일 오후 11시 59분까지 제출해요.**
- PR 은 발표 및 인터뷰가 끝난 후 스터디장이 머지해요.
- **학습 내용을 정리하지 않을 경우 5,000원의 벌금이 있어요.**

### 2. 발표 진행

- 발표자는 처음 정한 순서대로 돌아가며 진행해요.
- 발표자는 10분동안 학습한 내용을 다른 팀원들에게 설명해요.
- 발표가 끝나면 발표자 외 팀원들은 발표자에게 10분동안 질문해요.
    - 책에 작성되어 있지 않은 부분도 질문이 가능하지만 지식 자랑이 아닌, 공유 목적이면 가능해요.
- 다음주 발표자가 서기를 맡아 인터뷰 질문들을 기록해요.
    - 이번주 챕터에 해당하는 폴더에 해당 날짜 및 챕터 정보가 포함된 `.md` 파일에 작성해요.
        - ex. 2023-08-01_Ch01_Story01_02.md
- 작성한 파일을 PR 로 올리면 스터디 종료 후 스터디장이 머지해요.
    - PR 제목 : XXXX-XX-XX ChapterXX StoryXX~XX
- **발표 자리에 참석하지 않을 경우 10,000원의 벌금이 있어요.**
  - 모인 벌금들은 스터디 종료 후 각자 n분의 1로 나누어 가질 예정이에요. 😄 

### 3. 마무리 회고

- 발표 및 인터뷰를 마치고 5분동안 간단한 회고를 진행해요.

## 📖 학습 내용 순서

### Chapter 01. 웹 브라우저가 메시지를 만든다 - 웹 브라우저의 내부 탐험

**1주차 - 8/10**

Story 01. HTTP 리퀘스트 메시지를 작성한다

Story 02. 웹 서버의 IP 주소를 DNS 서버에 조회한다

**2주차 - 8/17**

Story 03. 전 세계의 DNS 서버가 연대한다

Story 04. 프로토콜 스택에 메시지 송신을 의뢰한다

### Chapter 02. TCP/IP의 데이터를 전기신호로 만들어 보낸다 - 프로토콜 스택과 LAN 어댑터의 탐험

**3주차 - 8/24**

Story 01. 소켓을 작성한다

Story 02. 서버에 접속한다

Story 03. 데이터를 송ㆍ수신한다

**4주차 - 8/31**

Story 04. 서버에서 연결을 끊어 소켓을 말소한다

Story 05. IP와 이더넷의 패킷 송ㆍ수신 동작

Story 06. UDP 프로토콜을 이용한 송ㆍ수신 동작

### Chapter 03. 케이블의 앞은 LAN 기기였다 - 허브와 스위치, 라우터의 탐험

**5주차 - 9/7**

Story 01. 케이블과 리피터, 허브 속을 신호가 흘러간다

Story 02. 스위칭 허브의 패킷 중계 동작

**6주차 - 9/14**

Story 03. 라우터의 패킷 중계 동작

Story 04. 라우터의 부가 기능

### Chapter 04. 액세스 회선을 통해 인터넷의 내부로! - 액세스 회선과 프로바이더의 탐험

**7주차 - 9/21**

Story 01. ADSL 기술을 이용한 액세스 회선의 구조와 동작

Story 02. 광섬유를 이용한 액세스 회선(FTTH)

Story 03. 액세스 회선으로 이용하는 PPP와 터널링

**8주차 - 9/28**

Story 04. 프로바이더의 내부

Story 05. 프로바이더를 경유하여 흐르는 패킷

### Chapter 05. 서버측의 LAN에는 무엇이 있는가 - 방화벽과 캐시 서버의 탐험

**9주차 - 10/5**

Story 01. 웹 서버의 설치 장소

Story 02. 방화벽의 원리와 동작

Story 03. 복수 서버에 리퀘스트를 분배한 서버의 부하 분산

**10주차 - 10/12**

Story 04. 캐시 서버를 이용한 서버의 부하 분산

Story 05. 콘텐츠 배포 서비스

### Chapter 06. 웹 서버에 도착하여 응답 데이터가 웹 브라우저로 돌아간다 - 불과 몇 초인 '긴 여행'의 끝

**11주차 - 10/19**

Story 01. 서버의 개요

Story 02. 서버의 수신 동작

**12주차 - 10/26**

Story 03. 웹 서버 소프트웨어가 리퀘스트 메시지의 의미를 해석하여 요구에 응한다

Story 04. 브라우저가 응답 메시지를 받아 화면에 표시한다

# 마당02 코딩별 안내서 - 웹 기술편
## Assignment #06 ep.16 ~ ep.21 (2023.01.18)
> * ep.16 인터넷 익스플로러가 사라진 이유와 브라우저 엔진
> * ep.17 아, 쿠키가 먹는 게 아니라고요?
> * ep.18 프런트엔드, 백엔드?
> * ep.19 서버가 뭔지 아직도 모른다고?
> * ep.20 슈퍼 개발자만 할 수 있다, 풀스택?
> * ep.21 서버리스는 서버가 없다는 뜻?

<br><br>

### ✔️ 오늘의 3줄 요약

* 쿠키는 각 도메인에 대한 사용자의 정보를 저장하고 있다가 서버와 통신하며 사용자를 기억하게 도와줌
* 프런트엔드는 사용자가 이용하는 화면의 인터페이스를 작업하고, 백엔드는 사용자가 웹사이트를 이용하는데 필요한 기능들을 처리하는 작업. 풀스텍은 프런트엔드+백엔드+데브옵스
* 서버는 항상 인터넷이 연결되어 있고 접속 요청에 응답하는 항상 켜져있는 컴퓨터이며, 서버만 전문으로 관리하는 회사에 서버를 위탁운영 하는 경우를 서버리스라고 함.

<br><br>


### 📚 책에서 기억하고 싶은 내용

> * 쿠키: 사용자가 웹사이트를 방문했을 때 브라우저를 통해 사용자의 컴퓨터에 
보관하는 기록물
> * HTTP: HyperText Transfer Protocol, 인터넷에서 사용자와 서버가 정보를 주고받기 위한 프로토콜, 일종의 규칙 
> * 사용자가 브라우저를 통해 웹사이트에 접속하면 HTTP는 우리에게 그 주소에 해당하는 데이터를 보내주고 연결을 끊어버리는데, 이러한 문제를 보완하기 위해 쿠키가 우리의 정보를 어딘가에 저장하고 있다가 서버에 전송해줌
> * 쿠키는 도메인 1개에만 한정하며, 자동으로 컴퓨터에 저장되어 서버에 전송됨

<br><br>

> * Front-end
>   * 장점: 개발자가 작업한 결과물을 바로 볼 수 있음
>   * 단점: 프런트엔드 기술은 변화 속도가 매우 빨라서 개발자가 공부해야할 내용이 많음
> * Back-end
>   * 장점1: 개발환경이 안정적임. 변화가 크지 않아 한번 배워두면 계속 개발 할 수 있음
>   * 장점2: 프런트엔드는 필수로 배워야하는 언어가 있지만 (HTML, CSS, Javascript), 백엔드는 선택할 수 있는 언어가 다양함
>   * 단점: 사용자와 거리가 멀어서 흥미가 떨어질 수 있음
> * Full-stack
>   * 프론트엔드, 백엔드, 데브옵스를 포함 
>   * 웹페이지의 화면도 만들고, 데이터베이스에 데이터를 저장하기도 하고, 완성된 프로그램을 서버에도 올려야 하는 등 모든 과정을 전부 다 해야함

<br><br>

> * 서버(server)
>   * 모니터가 없는 컴퓨터로 항상 인터넷에 연결되어 있으며 저장소와 메모리 크기가 어마어마 하다.
>   * 항상 주소 입력을 기다리며, 주소가 입력되면 해당 데이터를 꺼내서 보여줌
> * 서버리스(serverless)
>   * 직접 관리하지 않는 서버
>   * 예전에는 회사마다 직접 서버를 관리했지만, 서버를 전문적으로 관리 및 운영을 하는 회사(ex.아마존, 구글, 마이크로소프트)가 등장하면서 우리가 직접 관리하지 않아도 됨
>   * 단점1: 서버리스에는 서버를 위한 소프트웨어를 작은 함수 단위로 쪼개어져있으며 요청할 때만 함수가 실행되는데, 이 함수를 실행하는데 시간이 필요함 (cold start) -> 응답 시간에 영향을 줌
>   * 단점2: 지금 사용하는 서버리스 서비스를 다른 서버리스 서비스로 옮기는게 쉽지 않음
>   * 서버리스는 사이드프로젝트를 하는 사람이나, 프로토타입을 출시하는 기업에게 추천.

<br><br>


### 🤔 오늘 읽은 소감

*  풀스텍에 데브옵스까지 포함되는지는 몰랐다. 별개인줄 알았는데, 역시 풀스텍은 기획부터 배포까지 다 할 줄 알아야 하는 구나. 풀스텍의 길은 정말 멀지만 목표로 삼고 노력해야지.
* 서버는 알고 있었는데 서버리스의 개념을 잘 모르고 있었다는 것을 깨달았다. 책을 읽으면서 대략 들어보기만 했던 용어들이 점차 정리되는 것 같아 신기하고 뿌듯하다.

<br><br>

### 🧩 궁금하거나 잘 이해되지 않는 내용

* HTTP와 HTTPS의 차이

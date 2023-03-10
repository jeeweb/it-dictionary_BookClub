# 마당04 코딩별 안내서 - 컴퓨터 공학 편 ②

## Assignment #12 ep.35 ~ ep.38 (2023.01.24)

> - ep.35 비밀번호는 어떻게 저장될까?
> - ep.36 객체 지향 프로그래밍이 뭐죠? ①
> - ep.37 객체 지향 프로그래밍이 뭐죠? ②
> - ep.38 함수형 프로그래밍이 뭐죠?

<br><br>

### ✔️ 오늘의 3줄 요약

- 비밀번호를 안전하게 저장하기 위해서는 해시 함수로 변환하여 저장하며, 보안을 더 강화하기 위해 솔트와 합쳐서 해시함수를 통과 시키기도 함
- 객체지향 프로그래밍은 중복과 실수를 줄이기 위해 클래스와 상속을 사용
- 함수형 프로그래밍은 선언형 프로그래밍 특징을 가진 함수 중심의 코드 작성 방식

<br><br>

### 📚 책에서 기억하고 싶은 내용

> - 비밀번호를 안전하게 저장하기 ① 해시 함수
>   - 비밀번호를 무작위 값으로 변환해주는 함수
>   - 동일한 입력값에 대해 동일한 출력 값을 가짐
>   - 입력값이 조금만 바뀌어도 출력값은 완전히 다른 결과가 나옴 -> 무작위성
>   - 한쪽 방향으로만 설계된 함수라서, 반대로 입력하면 원래 값이 나오지 않음
>   - 해시 함수가 변경한 값을 원래의 값과 연결한 표인, 레인보우 테이블이 노출되면 해시함수도 위험함
> - 비밀번호를 안전하게 저장하기 ② 솔트
>   - 비밀번호에 무작위 텍스트인 솔트와 합쳐서 해시 함수에 통과 시키는 방식

<br>

> - 프로그래밍 패러다임 (programming paradigm)
>   - 프로그래머가 프로그래밍을 할 때의 관점, 방식
>   - 대표적인 프로그래밍 패러다임: 절차 지향 프로그래밍, 객체 지향 프로그래밍, 함수형 프로그래밍
> - 객체 지향 프로그래밍
>   - 클래스(class): 속성은 같지만 데이터는 다른 경우, 입력에 오류를 줄이기 위해 사용
>   - 상속: 기본이 되는 클래스를 상속해서 중복되는 내용을 해결하고 여기에 또 다른 속성을 추가 할 수 있음
> - 선언형 프로그래밍: 원하는 결과값을 선언 (예. CSS)
> - 명령형 프로그래밍: 원하는 결과값에 어떻게 도달하는지 단계를 선언. 개발자가 실수하기 쉽고, 동료가 이해하기 어려울 수 있음.
> - 함수형 프로그래밍: 함수 중심으로 코드를 적는 방식으로, 선언형 프로그래밍 컨셉을 유지

<br>

> - 개발자의 번아웃 대처하기
>   - 컴퓨터와 잠시 멀어져 제대로 휴식 취하기
>   - 일하는 스케줄에 시간 제한 두기
>   - 몸을 움직이는 운동과 건강한 음식으로 활력 찾기

<br><br>

### 🤔 오늘 읽은 소감

- 프로그래밍 패러다임의 다른 종류의 각각의 개념과 특성도 찾아봐야겠다.

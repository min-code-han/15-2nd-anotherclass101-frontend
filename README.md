# **AnotherClass101🌷**#
<img width="1028" alt="스크린샷 2021-01-11 00 02 36" src="https://user-images.githubusercontent.com/71719160/104126531-7489e900-53a0-11eb-99f2-f4dd69275f9b.png">



## 🌷**프로젝트 소개**

> 안녕하세요. 'AnotherClass101'는 WECODE 2차 프로젝트 학습용으로 제작된 '클래스101'클론 프로젝트입니다. 클래스101은 다양한 분야의 크리에이터에서 여러 활동을 영상으로 배울 수 있게 돕는 온라인 클래스 플랫폼입니다. 이번 클론 프로젝트에서는 회원가입과 로그인, 마이페이지를 포함하여 메인화면, 크리에이터 생성등의 내용을 구현했습니다.

## 🌷**프로젝트 시연영상**

[https://youtu.be/tagQh4wZ0B4](https://youtu.be/tagQh4wZ0B4)

---


## 🌷 프로젝트 참가자 (Front & Back)

![2차사진](https://user-images.githubusercontent.com/71719160/104126401-9fc00880-539f-11eb-8f30-0fc738fdab1f.jpg)

### **👩‍👧‍👧FrontEnd**
김별이, 박소윤, 한민아

### 👩‍👦‍👦 **BackEnd**

김민철, 석여주(PM), 이재혁

---

## 🌷**기술 스택**

### **FrontEnd**

> HTML(JSX) / JavaScript (ES6) / React (CRA 세팅) / Styled-Component / Hooks(useState / useEffect / useRef) / Redux / React-Router / asiox

### **BackEnd**

> Python / Django / CORS Header / Bcrypt / PyJWT / MySQL / AqueryTool (데이터베이스 모델링) / Postman,Httpie (API 관리) / AWS(서버 및 DATABASE관리) / Django-seed및 Faker

### **협업 도구**

> Slack / Git + GitHub / [Trello](https://trello.com/b/9SEvYOoX/anotherclass101)를 이용, 일정관리 및 작업 현황 확인

---

# **⭐️ 구현한 기능**



### Header

- `Token` 유무에 따라 레이아웃 변경. (로그인성공 ⇒ 주문및배송/내 쿠폰/내 클래스 추가됨)
- `Token` 유무에 따라 페이지 이동 통제.
(로그인 안되어 있을시 ⇒ 다른 메뉴로  넘어가려면 "로그인 후 이용가능한 서비스 입니다" 라는 알람과 동시에 로그인 페이지로 이동)
- `useHistory`  사용하여 페이지 이동.
- `Styled-Component` 로 스타일을 `props`  로 넘겨주어 `Modal`  통제.
- `on-click` 이벤트로 소메뉴 모달창 띄우기.

### 메인 **페이지**

- fetch() 함수 이용하여 데이터 받아오기.
- map() 함수 이용하여 화면에 데이터 보여주기. 
- 반복적으로 쓰이는 부분 `Component` 로 분리해서 만든후 재사용.
- 레이아웃이 비슷하지만 조금씩만 바뀌는 부분에 대해서는 조건부 랜더링 사용해서 통제.
- $ 단위로 오는 데이터 ⇒ ₩ 단위로 바꿔주기.
- `String`  으로 오는 숫자 데이터 `Number` 로 바꿔주기.
- 좋아요 이모티콘 누를시 숫자도 +1 되도록 로직구현.
- Carousel 슬라이더 라이브러리 안쓰고 직접 구현.
- 조건부랜더링 을 이용하여 조금식 다른 컴포넌트 재사용 가능하도록 제작.



---

# 🌷**후기**

- 한민아 https://velog.io/@mincode_/Class101clone-project-%EA%B0%9C%EB%B0%9C%EC%9E%90-%EB%A1%9C%EC%84%9C%EC%9D%98-%ED%9B%84%EA%B8%B0

---

# 🌷**레퍼런스**

- 이 프로젝트는  [클래스101](https://class101.net/)을 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것으로 해당 프로젝트 외부인이 사용할 수 없습니다.

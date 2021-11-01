# BoostCourse-Reservation-System
부스트 코스 웹 풀스택 강의를 통해 만든 예약 관리 시스템입니다.<br>
동료 학습자의 원활한 학습을 위해 프로젝트 관련 소스코드는 올리지 않습니다. <br>

<h2>기술스택</h2>
<code>JAVA8</code>, <code>Spring MVC</code>, <code>Tomcat 8.5</code>, <code>Javascript</code>, <code>MySQL</code><br><br>

자바스크립트 코드의 경우 라이브러리 사용을 최소화하고 대부분의 코드를 바닐라 자바스크립트를 이용해서 구현

<h2>해당 프로젝트를 통해 배운점</h2>
대부분의 코드를 바닐라 자바스크립트로 구현하면서 DOM 조작 방법, 콜백 함수, 동기와 비동기 처리, 생성자 함수, 클래스를 통한 객체 동적 생성, 프로토타입 등의 개념을 익힐 수 있었다.<br>
프론트엔드와 백엔드를 모두 구현해보면서 서버와 클라이언트가 데이터를 주고받는 전체적인 흐름을 이해할 수 있었다.<br>

<h2>개선한점</h2>
1. 서버로부터 받은 데이터를 화면에 반영해야 할 때, DOM API를 사용해서 엘리먼트를 만들어내는 반복적인 작업으로 처리하였던 것을 HTML templateing으로 반복적인 html 부분을 템플릿으로 만들어두고 서버에서 받은 데이터를 결합해서 화면에 추가하는 것으로 변경하였다. <br>
2. 자주 사용되는 함수의 경우 객체 형태로 묶어 사용하였고 객체 리터럴 방식, 생성자 함수, ES6 class를 사용하였다.<br>
3. 좋은 UX 제공을 위해 요청을 AJAX로 처리하여 빠른 응답을 받을 수 있도록 하였다.<br>
4. 인터셉터를 사용하여 로그인 기능을 처리하였다.<br>
5. 브라우저에서 바로 접근할 수 있었던 샘플 이미지를 별도의 다운로드 컨트롤러를 만들어 처리하였다.<br>

<h2>동작</h2>

<h3>메인페이지</h3>

![메인페이지 사진](https://user-images.githubusercontent.com/60775067/121348112-e9b71580-c962-11eb-825e-ad2f4bc5db83.jpg)

<h3>각 항목의 상세페이지</h3>

![상세페이지 사진](https://user-images.githubusercontent.com/60775067/121347689-6eedfa80-c962-11eb-999c-f1aad6f66891.jpg)

<h3>리뷰페이지</h3>

![리뷰페이지](https://user-images.githubusercontent.com/60775067/121347908-ae1c4b80-c962-11eb-9bfd-8d55d6fd77d5.jpg)

<h3>예약하기</h3>

![예약페이지](https://user-images.githubusercontent.com/60775067/121348235-0e12f200-c963-11eb-8c21-f07372546baa.jpg)


<h3>로그인</h3>

![로그인 화면](https://user-images.githubusercontent.com/60775067/121348302-271ba300-c963-11eb-8f88-a861be8b0301.jpg)

<h3>나의 예매 내역 확인</h3>

![예약 확인 페이지](https://user-images.githubusercontent.com/60775067/121348367-3f8bbd80-c963-11eb-8e19-bd1de26ad926.jpg)

<h3>리뷰 </h3>

![리뷰작성페이지](https://user-images.githubusercontent.com/60775067/121348428-516d6080-c963-11eb-8c5b-4103615ad6bd.jpg)


https://user-images.githubusercontent.com/60775067/121347199-df484c00-c961-11eb-8b2f-3f13aa3c9a99.mp4







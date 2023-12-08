# 🌱 프로젝트 개요

### 1. 기획의도

  - 혼자 여행하는 사람들은 증가하는데, 다수의 여행 사이트는 최소 2명 이상부터 구매할 수 있는 여행 패키지를 주로 제공하고 있음
  - 혼자 여행하기 때문에 여행 동행을 구하는 여행자들이 많은데, 최소한의 인적 정보를 알 수 없어 안전 문제가 생길 수 있음
  - 대부분의 여행 사이트는 후기 게시판이 없어 실제 여행의 만족도나 장단점을 알 수 없음
<br>

👏 **그렇다면 여행 패키지 상품 판매와 여행 동행 매칭 서비스를 제공하는 플랫폼을 구축해보자!**

<br>

### 2. 벤치마킹
![image](https://github.com/dogpaw1230/teamProject/assets/146051611/4d54d30b-0f62-4cd2-9be6-cb37760abf2c)

  - **여행 동행을 구하는 서비스 제공**

    a. 구체적인 장소와 일정을 명시할 수 있고, 조회수와 동행 신청수 등이 한눈에 들어옴
    
    b. 동행을 구하는 사람의 기본적인 정보가 명시되어 있어 이용자들에게 신뢰를 줄 수 있음
    
    <br>

  - **여행 후기 작성 기능 제공**

    a. 여행 상품의 상세 페이지에 댓글 형식으로 후기를 작성하는 기능을 제공
    
    b. 여행 후기만을 따로 모아놓은 게시판이 있으면 이용자간의 교류가 활발할 것으로 예상
    
<br><br>

# 💡 프로젝트의 목적

> **"혼자 여행하기 부담스러운 여행자들을 위한 소셜 네트워크 기반의 동행 매칭과 다양한 여행 상품 판매를 제공하는 플랫폼 구축"**

<br>

### ⚙️ 제공하는 기능


- **여행 상품 검색 및 예약** : 원하는 여행 상품을 찾아 예약할 수 있는 기능

- **동행 구하기 게시판** : 간편한 동행 신청이 가능한 게시판

- **여행 후기 게시판** : 여행 경험을 공유하고 다른 이용자들과 소통하는 게시판

<br><br>

# 😎 프로젝트 소개

### 1. 팀 소개

![팀소개](https://github.com/dogpaw1230/teamProject/assets/146051611/242c61e0-a323-4169-ba02-c1844161649a)



### 2. 기술 스택

- Backend : Java, Spring, MyBatis, JSP, Tomcat, MySQL
  
![backend1](https://github.com/dogpaw1230/teamProject/assets/146051611/a7178dc7-59d4-4111-ab3c-ebe6cc368548)

<br>

- Frontend : HTML, CSS, Javascript, JQuery

<br>

![frontend](https://github.com/dogpaw1230/teamProject/assets/146051611/d42ca3b2-28bf-48e1-823c-e15c01617b78)

<br>

### 3. ERD
<br>

![ERD](https://github.com/dogpaw1230/teamProject/assets/146051611/b6d07c79-d857-4932-8a2e-349c5d9d492a)

### 4. 시연 영상

영상 보러가기 👉  [BlueHorizon](https://youtu.be/-U5Wa2IEOi8)

<br><br>


# 👩🏻‍💻 프로젝트 주요 기능

### 1. 여행 상품 검색
> 여행하고 싶은 지역, 나라, 날짜를 검색하면 조건에 맞는 여행 상품을 보여줍니다.

<br>

<img width="648" alt="여행상품검색" src="https://github.com/dogpaw1230/teamProject/assets/146051611/2e975b1a-da29-4364-88bd-63f97a259766">

🔍 **검색**

  - 지역 선택 클릭 : 국내 or 해외(아시아, 유럽, 아메리카 등)를 선택할 수 있음
  - 세부 지역 선택 클릭 : 도시(국내 선택한 경우) or 나라(해외 선택한 경우)를 선택할 수 있음
  - 날짜 선택 클릭 : 원하는 날짜를 선택할 수 있음

<br>

### 2. 여행 상품 예약
> 선택한 상품의 상세 설명과 예약 가능한 날짜 및 가격을 표시합니다.
> 
> 예약자 정보 입력하고 예약을 진행할 수 있습니다.

<br>

<img width="640" alt="상품상세정보" src="https://github.com/dogpaw1230/teamProject/assets/146051611/19682951-3f2f-47ed-a0eb-dc3bb6ac7805">
<img width="640" alt="상품상세정보" src="https://github.com/dogpaw1230/teamProject/assets/146051611/5822e623-09aa-4079-8442-5365c421cf24">

📍 **예약**

  - 상품 상세 설명 
  - 상품 별 예약 가능한 날짜와 가격 정보를 달력에 표시 : 원하는 날짜 클릭하면 달력 하단에 출발일과 상품 가격을 한번 더 표시함
  - ➀ ➔ 예약자 정보를 입력하는 폼
  - ➁ ➔ 예약자를 추가/삭제할 수 있음
  - ➂ ➔ 예약자를 추가하면 추가한 인원만큼 상품 가격에 적용

<br>

### 3. 동행 신청 및 수락/거절하기
> 여행 동행을 구하는 게시글 및 댓글을 작성할 수 있습니다.
>
> 동행을 신청하거나 신청을 받을 수 있습니다.
>
> 마이페이지에서 내역을 확인할 수 있고, 신청한 동행을 취소하거나 신청받은 동행을 수락 또는 거절할 수 있습니다.

<br>

👭 **동행**

<img width="640" alt="동행1" src="https://github.com/dogpaw1230/teamProject/assets/146051611/a5610e32-47fd-4f2c-8658-181c4985e137">

<br>

  - 여행 동행 게시글을 검색하고 볼 수 있음
<img width="640" alt="동행2" src="https://github.com/dogpaw1230/teamProject/assets/146051611/12714142-9d1a-43be-9450-0c02067dc063">

<br>

  - 여행 동행을 신청할 수 있음
<img width="640" alt="동행3" src="https://github.com/dogpaw1230/teamProject/assets/146051611/7791d62c-0d10-42c4-8944-ea487a402d4d">
<img width="640" alt="동행4" src="https://github.com/dogpaw1230/teamProject/assets/146051611/906a50a5-0195-4d1c-b63d-cd6f1ad90a2c">

<br>

  - 마이페이지에서 내가 신청한 동행 내역과 신청 받은 동행 내역을 볼 수 있음


<br>


### 4. 여행 후기 게시판
> 후기를 작성할 때, 프로필 이미지를 설정할 수 있습니다.
> 
> 게시글에 여러 장의 이미지를 업로드할 수 있습니다.

<br>

<img width="640" alt="후기게시글" src="https://github.com/dogpaw1230/teamProject/assets/146051611/84cb7feb-d8f1-4c4c-a5ac-a31df7c13c68">


<br><Br>

📝 **여행 후기 작성**

  - 여행 후기 게시판에 후기를 작성할 수 있음
  - 프로필 사진을 업로드 할 수 있음
  - 게시글에 사진을 업로드 할 수 있음
  - 댓글을 등록할 수 있음

<br><br>

# 💣 트러블 슈팅

### ⚡️ 서버에서 요청 처리
<table>
  <thead>
    <tbody>
      <tr>
        <td>문제상황</td>
        <td>예약자가 2명 이상일 때, url로 하나의 키와 매칭되는 여러 개의 값이 전송되는데 서버에서 이를 어떻게 처리할 지 고민</td>
      </tr>
      <tr>
        <td>원인</td>
        <td>인원 추가 버튼을 누르면 동적으로 요소가 생성되도록 구현했기 때문에 하나의 키에 여러 개의 값이 매칭됨</td>
      </tr>
      <tr>
        <td>해결</td>
        <td>서버에서 요청을 받을 때, 전달된 정보를 List 형태의 매개변수로 받아 처리함</td>
      </tr>
    </tbody>
  </thead>
</table>

<img width="640" alt="후기게시글" src="https://github.com/dogpaw1230/teamProject/assets/146051611/5ca2810c-0bcb-4060-b08c-168f80c7b3e0">

<br>

### 💥 날짜만 다른 중복 데이터 처리
<table>
  <thead>
    <tbody>
      <tr>
        <td>문제상황 </td>
        <td>여행 상품을 검색했을 때, 날짜만 다른 같은 내용의 여행 상품이 여러 개 검색되는 문제</td>
      </tr>
      <tr>
        <td>원인</td>
        <td>각 여행 상품은 최소 2주 이상의 예약 가능한 날짜를 가지고 있기 때문에, 특정 날짜 이후에는 동일한 여행 상품이 여러 개 나타남</td>
      </tr>
      <tr>
        <td>해결</td>
        <td>이용자가 선택한 날짜로부터 가장 가까운 날짜를 새로운 컬럼으로 지정하고, group by로 필요한 데이터를 select 할 수 있도록 MyBatis를 수정함     </td>
      </tr>
    </tbody>
  </thead>
</table>

<img width="640" alt="후기게시글" src="https://github.com/dogpaw1230/teamProject/assets/146051611/cb2d8b77-802c-4448-a435-db0c6b814cfd">

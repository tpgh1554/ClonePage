## 1. 클론 페이지(Tesla)

[전기차, 태양광 및 청정 에너지 | Tesla](https://www.tesla.com/ko_KR/?redirect=no)

## 2. 레이아웃

- MainPage
    
    ![Section 1.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/37470f1e-4a0c-4bce-9574-7ab31403d02b/Section_1.png)
    
- MobilePage
    
    ![Untitled.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/587bbf51-ca2b-416f-9010-666c6b20cc8c/Untitled.png)
    

## 3. HTML/CSS

- HTML
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Document</title>
      <link rel="stylesheet" href="./css/tesla.css">
    </head>
    <body>
      <div class="container">
        <div class="navigation">
          <!-- 네비게이션바 -->
          <nav>
            <a href="#">
              <img src="./images/TESLA LOGO-03 - 복사본.png" class="logo">
            </a>
              <ul class="ul1">
                <li><a href="#">차량</a></li>
                <li><a href="#">충전</a></li>
                <li><a href="#">살펴보기</a></li>
                <li><a href="#" class="shop">Shop</a></li>
              </ul>
              <ul class="ul2">
                <li>
                  <a href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 -960 960 960" width="24">
                      <path fill="#FFFFFF" d="M478-240q21 0 35.5-14.5T528-290q0-21-14.5-35.5T478-340q-21 0-35.5 14.5T428-290q0 21 14.5 35.5T478-240Zm-36-154h74q0-33 7.5-52t42.5-52q26-26 41-49.5t15-56.5q0-56-41-86t-97-30q-57 0-92.5 30T342-618l66 26q5-18 22.5-39t53.5-21q32 0 48 17.5t16 38.5q0 20-12 37.5T506-526q-44 39-54 59t-10 73Zm38 314q-83 0-156-31.5T197-197q-54-54-85.5-127T80-480q0-83 31.5-156T197-763q54-54 127-85.5T480-880q83 0 156 31.5T763-763q54 54 85.5 127T880-480q0 83-31.5 156T763-197q-54 54-127 85.5T480-80Zm0-80q134 0 227-93t93-227q0-134-93-227t-227-93q-134 0-227 93t-93 227q0 134 93 227t227 93Zm0-320Z"/>
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 -960 960 960" width="24">
                      <path fill="#FFFFFF" d="M480-80q-82 0-155-31.5t-127.5-86Q143-252 111.5-325T80-480q0-83 31.5-155.5t86-127Q252-817 325-848.5T480-880q83 0 155.5 31.5t127 86q54.5 54.5 86 127T880-480q0 82-31.5 155t-86 127.5q-54.5 54.5-127 86T480-80Zm0-82q26-36 45-75t31-83H404q12 44 31 83t45 75Zm-104-16q-18-33-31.5-68.5T322-320H204q29 50 72.5 87t99.5 55Zm208 0q56-18 99.5-55t72.5-87H638q-9 38-22.5 73.5T584-178ZM170-400h136q-3-20-4.5-39.5T300-480q0-21 1.5-40.5T306-560H170q-5 20-7.5 39.5T160-480q0 21 2.5 40.5T170-400Zm216 0h188q3-20 4.5-39.5T580-480q0-21-1.5-40.5T574-560H386q-3 20-4.5 39.5T380-480q0 21 1.5 40.5T386-400Zm268 0h136q5-20 7.5-39.5T800-480q0-21-2.5-40.5T790-560H654q3 20 4.5 39.5T660-480q0 21-1.5 40.5T654-400Zm-16-240h118q-29-50-72.5-87T584-782q18 33 31.5 68.5T638-640Zm-234 0h152q-12-44-31-83t-45-75q-26 36-45 75t-31 83Zm-200 0h118q9-38 22.5-73.5T376-782q-56 18-99.5 55T204-640Z"/>
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 -960 960 960" width="24">
                      <path fill="#FFFFFF" d="M234-276q51-39 114-61.5T480-360q69 0 132 22.5T726-276q35-41 54.5-93T800-480q0-133-93.5-226.5T480-800q-133 0-226.5 93.5T160-480q0 59 19.5 111t54.5 93Zm246-164q-59 0-99.5-40.5T340-580q0-59 40.5-99.5T480-720q59 0 99.5 40.5T620-580q0 59-40.5 99.5T480-440Zm0 360q-83 0-156-31.5T197-197q-54-54-85.5-127T80-480q0-83 31.5-156T197-763q54-54 127-85.5T480-880q83 0 156 31.5T763-763q54 54 85.5 127T880-480q0 83-31.5 156T763-197q-54 54-127 85.5T480-80Zm0-80q53 0 100-15.5t86-44.5q-39-29-86-44.5T480-280q-53 0-100 15.5T294-220q39 29 86 44.5T480-160Zm0-360q26 0 43-17t17-43q0-26-17-43t-43-17q-26 0-43 17t-17 43q0 26 17 43t43 17Zm0-60Zm0 360Z"/>
                    </svg>
                  </a>
                </li>
              </ul>
          </nav>
        </div>
        
    
        <!-- 메인비디오 -->
        <div class="main-video">
          <video src="./media/teslavideo.webm" autoplay loop>
            <p class="maintext2">지금 바로 시승 신청해 보세요</p>
          </video>
          <div class="textbox">
            <div class="textbox1">
              <p class="maintext1">Tesla <span>경험하기</span></p>
            </div>
            <div class="textbox2">
              <p class="maintext2">지금 바로 시승 신청해 보세요</p>
            </div>
          </div>
          <div class="btnbox">
            <a href="#"><button class="mainbtn">시승 신청하기</button></a>
          </div>
        </div>
    
        <!-- 모델3 -->
        <div class="model3">
          <img src="./images/model3.jpg" class="model3img">
          <p class="model3text">Model 3</p>
          <div class="box">
            <div class="model3btn">
              <a href="#"><button class="model3btn1">시승 신청하기</button></a>
              <a href="#"><button class="model3btn2">주문하기</button></a>
            </div>
          </div>
        </div>
    
        <!-- 모델Y -->
        <div class="modely">
          <img src="./images/Homepage-Model-Y-Global-Desktop.avif" class="modelyimg">
          <p class="modelytext">Model Y</p>
          <div class="box">
            <div class="modelybtn">
              <a href="#"><button class="modelybtn1">시승 신청하기</button></a>
              <a href="#"><button class="modelybtn2">주문하기</button></a>
            </div>
          </div>
          
        </div>
    
        <!-- 모델s -->
        <div class="models">
          <img src="./images/Model-S-homepage-desktop.avif" class="modelsimg">
          <p class="modelstext">Model S</p>
          <a href="#" class="modelstext2">인벤토리 둘러보기</a>
          <div class="box">
            <div class="modelsbtn">
              <a href="#"><button class="modelsbtn1">시승 신청하기</button></a>
              <a href="#"><button class="modelsbtn2">주문하기</button></a>
            </div>
          </div>
        </div>
    
        <!-- 모델x -->
        <div class="modelx">
          <img src="./images/Homepage-Model-X-Desktop-LHD.avif" class="modelximg">
          <p class="modelxtext">Model X</p>
          <a href="#" class="modelxtext2">인벤토리 둘러보기</a>
          <div class="box">
            <div class="modelxbtn">
              <a href="#"><button class="modelxbtn1">시승 신청하기</button></a>
              <a href="#"><button class="modelxbtn2">주문하기</button></a>
            </div>
          </div>
        </div>
    
        <!-- solarsystem -->
        <div class="solar">
        <img src="./images/card5.jpg" class="solarimg">
        <p class="solartext">태양광과 <b>Powerwall</b></p>
        <p class="solartext2">모든 전력을 공급</p>
        <div >
          <a href="#"><button class="solarbtn">자세히 알아보기</button></a>
        </div>
        </div>
    
        <!-- accesory -->
        <div class="acc">
        <img src="./images/card6.jpg" class="accimg">
        <p class="acctext">액세서리</p>
        <div>
          <a href="#"><button class="accbtn">지금 쇼핑하기</button></a>
        </div>
        </div>
        <footer>
        <div class="footer1">
          <span>Tesla ⓒ 2024</span>
          <span>개인정보 처리방침 및 법적 고지</span>
          <span>이용약관</span>
          <span>문의하기</span>
          <span>새 소식</span>
          <span>위치</span>
          <div class="footptag">
            <p>테슬라코리아 유한회사 | 사업자등록번호:524-88-00237 | 데이비드존파인스타인, 케네스어니스트무어 | 통신판매업신고: </p>
            <p>제2016-서울강남-02964호 | <a href="#">사업자정보확인</a> | 호스팅제공자:Tesla inc. | 주소:서울특별시 강남구 테헤란로 134, 14층 | </p>
            <p>대표전화:080-617-1388 | <a href="">southkorea@tesla.com</a></p>
          </div>
        </div>
        </footer>
      </div>
    </body>
    </html>
    ```
    
- CSS
    
    ```css
    * {
      margin: 0 auto;
      padding: 0;
    }
    body {
      margin: 0 auto;
      padding: 0;
    }
    @media screen and (max-width: 767px) {
      /* 화면 너비가 767px 이하인 경우에 적용될 스타일 */
      body {
        min-width: 768px;
      }
    }
    .container {
      margin: 0 auto;
      padding: 0;
      
    }
    .navigation {
      position: absolute;
      width: 100%;
      display: flex;
      margin: 0;
      padding: 0;
      background-color: transparent;
    }
    
    /* 네비게이션 */
    nav {
      margin: 0 auto;
      width: 100%;
      height: 40px;
      padding: 4px;
      display: flex;
      justify-content: center;
      align-items: center;
      z-index: 1;
    }
    .logo {
      margin: 0;
      padding: 0;
      display: flex;
      width: 110px;
    }
    .ul1 {
      
      display: flex;
      padding: 0;
      margin: 0;
      justify-content: center;
      align-content: center;
      list-style: none;
      color: #fff;
    }
    .ul1 li:hover .navigation{
      background-color: #fff;
    }
    .ul1 li{
      position: relative;
      font-size: 14px;
      padding-left: 16px;
      padding-right: 16px;
      color: #fff;
    }
    .ul1 a {
      padding: 0;
      margin: 0;
      color: #fff;
      text-decoration: none;
    }
    .ul2 {
      padding: 0;
      display: flex;
      align-content: flex-end;
      list-style: none;
    }
    .ul2 a {
      padding: 0;
      margin: 0;
    }
    .ul2 svg {
      padding: 10px;
      display: flex;
      list-style: none;
    }
    button {
      background-color: transparent;
      border: 0;
    }
    
        /* 메인 */
        .main-video {
          margin-top: -50px;
          position: relative;
          z-index: -1;
          top: 0;
          left: 0;
          width: 100%;
          height: 100vh;
          padding: 0;
          margin: 0 auto;
          text-align: center;
          overflow: hidden;
          border: 0;
        }
        .textbox1 {
          width: 100vw;
          margin: 0;
          padding: 0;
          z-index: 1;
          display: flex;
          justify-content: center;
        }
        .maintext1 {
          position: absolute;
          top: 19%;
          text-align: center;
          color: white;
          font-size: 41px;
          font-weight: 800;
          white-space: nowrap;
          z-index: 1;
        }
        .maintext1 span {
          font-weight: 400;
        }
        .textbox2 {
          width: 100vw;
          margin: 0;
          padding: 0;
          z-index: 1;
          display: flex;
          justify-content: center;
        }
        .maintext2 {
          position: absolute;
          top: 27%;
          text-align: center;
          color: white;
          font-size: 14px;
        }
        .btnbox {
          width: 100vw;
          margin: 0;
          padding: 0;
          z-index: 1;
          display: flex;
          justify-content: center;
        }
        .mainbtn {
          position: absolute;
          top: 83%;
          transform: translate(-50%, -50%);
          text-align: center;
          color: #fff;
          border: 3px solid white;
          border-radius: 3px;
          width: 260px;
          height: 40px;
          font-size: 14px;
          z-index: 1;
        }
        video {
          width: 100%;
          height: 100%;
          object-fit: cover;
        }
    
        /* 모델3 */
        .model3 {
          display: flex;
          position: relative;
          width: 100%;
          height: 100vh;
          margin: 0 auto;
          padding: 0;
        }
        .model3img {
          position: absolute;
          width: 100%;
          height: 100%;
          object-fit: cover;
          overflow: hidden;
        }
        
        .model3text {
          position: absolute;
          top: 19%;
          left: 50%;
          transform: translate(-50%, -50%);
          text-align: center;
          color: black;
          font-size: 42px;
          font-weight: bold;
          z-index: 1;
        }
        .box {
          width: 100vw;
          margin: 0;
          padding: 0;
          z-index: 1;
          display: flex;
          justify-content: center;
        }
        .model3btn {
          position: absolute;
          top: 80%;
          gap: 10px;
          display: flex;
          justify-content: center;
          z-index: 1;
          margin: 0;
        }
        .model3btn1 {
          text-align: center;
          color: #fff;
          border: 0;
          border-radius: 3px;
          background-color: #22251c;
          width: 260px;
          height: 40px;
          font-size: 14px;
          margin: 0;
        }
        .model3btn2 {
          text-align: center;
          background-color: #dfdfdf;
          border: 0;
          border-radius: 3px;
          width: 260px;
          height: 40px;
          font-size: 14px;
          margin: 0;
        }
        /* 모델Y */
        .modely {
          display: flex;
          position: relative;
          width: 100%;
          height: 100vh;
          margin: 0 auto;
          padding: 0;
        }
        .modelyimg {
          position: absolute;
          width: 100%;
          height: 100%;
          object-fit: cover;
          overflow: hidden;
        }
        .modelytext {
          position: absolute;
          top: 19%;
          left: 50%;
          transform: translate(-50%, -50%);
          text-align: center;
          color: black;
          font-size: 42px;
          font-weight: bold;
          z-index: 1;
        }
        .modelybtn {
          overflow: hidden;
          height: 60px;
          position: absolute;
          top: 80%;
          gap: 10px;
          display: flex;
          flex-grow: unset;
          align-content: center;
          flex-wrap: wrap;
          justify-content: center;
          z-index: 1;
          margin: 0;
        }
        .modelybtn1 {
          text-align: center;
          color: #fff;
          border: 0;
          border-radius: 3px;
          background-color: #22251c;
          width: 260px;
          height: 40px;
          font-size: 14px;
          margin: 0;
        }
        .modelybtn2 {
          text-align: center;
          background-color: #dfdfdf;
          border: 0;
          border-radius: 3px;
          width: 260px;
          height: 40px;
          font-size: 14px;
          margin: 0;
        }
        
        /* 모델S */
        .models {
          display: flex;
          position: relative;
          width: 100%;
          height: 100vh;
          margin: 0 auto;
          padding: 0;
        }
        .modelsimg {
          position: absolute;
          width: 100%;
          height: 100%;
          object-fit: cover;
          overflow: hidden;
        }
        .modelstext {
          position: absolute;
          top: 19%;
          left: 50%;
          transform: translate(-50%, -50%);
          text-align: center;
          color: black;
          font-size: 42px;
          font-weight: bold;
          z-index: 1;
        }
        .modelstext2 {
          position: absolute;
          top: 24%;
          left: 50%;
          transform: translate(-50%, -50%);
          text-align: center;
          color: black;
          font-size: 14px;
          z-index: 1;
        }
        
        .modelsbtn {
          overflow: hidden;
          height: 60px;
          position: absolute;
          top: 80%;
          gap: 10px;
          display: flex;
          flex-grow: unset;
          align-content: center;
          flex-wrap: wrap;
          justify-content: center;
          z-index: 1;
          margin: 0;
        }
        .modelsbtn1 {
          text-align: center;
          color: #fff;
          border: 0;
          border-radius: 3px;
          background-color: #22251c;
          width: 260px;
          height: 40px;
          font-size: 14px;
          margin: 0;
        }
        .modelsbtn2 {
          text-align: center;
          background-color: #dfdfdf;
          border: 0;
          border-radius: 3px;
          width: 260px;
          height: 40px;
          font-size: 14px;
          margin: 0;
        }
        /* 모델x */
        .modelx {
          display: flex;
          position: relative;
          width: 100%;
          height: 100vh;
          margin: 0 auto;
          padding: 0;
        }
        .modelximg {
          position: absolute;
          width: 100%;
          height: 100%;
          object-fit: cover;
          overflow: hidden;
        }
        .modelxtext {
          position: absolute;
          top: 19%;
          left: 50%;
          transform: translate(-50%, -50%);
          text-align: center;
          color: black;
          font-size: 42px;
          font-weight: bold;
          z-index: 1;
        }
        .modelxtext2 {
          position: absolute;
          top: 24%;
          left: 50%;
          transform: translate(-50%, -50%);
          text-align: center;
          color: black;
          font-size: 14px;
          z-index: 1;
        }
        .modelxbtn {
          overflow: hidden;
          height: 60px;
          position: absolute;
          top: 80%;
          gap: 10px;
          display: flex;
          flex-grow: unset;
          align-content: center;
          flex-wrap: wrap;
          justify-content: center;
          z-index: 1;
          margin: 0;
        }
        .modelxbtn1 {
          text-align: center;
          color: #fff;
          border: 0;
          border-radius: 3px;
          background-color: #22251c;
          width: 260px;
          height: 40px;
          font-size: 14px;
          margin: 0;
        }
        .modelxbtn2 {
          text-align: center;
          background-color: #dfdfdf;
          border: 0;
          border-radius: 3px;
          width: 260px;
          height: 40px;
          font-size: 14px;
          margin: 0;
        }
    
        /* 태양광 */
        .solar {
          display: flex;
          position: relative;
          width: 100%;
          height: 100vh;
        }
        .solarimg {
          width: 100%;
          height: 100%;
          object-fit: cover;
          overflow: hidden;
        }
        .solartext {
          position: absolute;
          top: 19%;
          left: 50%;
          white-space: nowrap;
          transform: translate(-50%, -50%);
          text-align: center;
          color: black;
          font-size: 42px;
          transition: font-size 0.3s ease;
          z-index: 1;
        }
        
        @media (max-width: 768px) {
          .solartext {
            font-size: 40px
    
          }
        }
        .solartext2 {
          position: absolute;
          top: 24%;
          left: 50%;
          transform: translate(-50%, -50%);
          text-align: center;
          color: black;
          font-size: 14px;
          z-index: 1;
        }
        .solarbtn {
          position: absolute;
          top: 79.3%;
          left: 50%;
          transform: translate(-50%, -50%);
          text-align: center;
          background-color: #22251c;
          color: #fff;
          border: 0;
          border-radius: 3px;
          padding: 5px;
          width: 260px;
          height: 42px;
          font-size: 14px;
          z-index: 1;
        }
    
        /* 액세서리 */
        .acc {
          display: flex;
          position: relative;
          width: 100%;
          height: 100vh;
        }
        .accimg {
          width: 100%;
          height: 100%;
          object-fit: cover;
          overflow: hidden;
        }
        .acctext {
          position: absolute;
          top: 19%;
          left: 50%;
          transform: translate(-50%, -50%);
          text-align: center;
          color: black;
          font-size: 40px;
          z-index: 1;
        }
        .accbtn {
          position: absolute;
          top: 83%;
          left: 50%;
          transform: translate(-50%, -50%);
          text-align: center;
          background-color: #fff;
          color: #22251c;
          border: 0;
          border-radius: 3px;
          padding: 5px;
          width: 260px;
          height: 42px;
          font-size: 14px;
          z-index: 1;
        }
    
        /* footer */
        footer {
          background-color: black;
          color: white;
          font-size: 12px;
          padding: 20px 0px 10px 0px;
          text-align: center;
          text-decoration: none;
          font-weight: lighter;
        }
        footer span {
          margin-right: 10px;
        }
        .footptag {
          margin-top: 30px;
          font-size: 10px;
        }
        .footptag p {
          margin: 6px;
          font-weight: 300;
        }
        .footptag a {
          text-decoration: none;
          color: white;
          text-decoration: underline;
        }
    ```
    

## 4. 구현

### 기능

- 네비게이션, 사진, 비디오, 텍스트를 화면의 정중앙 배치
- 반응형 사이트 : flex 사용하여 화면 크기에 맞게 컨텐츠 정중앙 배치
- 화면이 줄어듦에 따라 overflow 설정
- Main
    
    [bandicam 2024-04-21 18-21-23-837.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/94981692-34e6-4989-9f8c-8729adfb2491/bandicam_2024-04-21_18-21-23-837.mp4)
    
- Mobile
    
    [bandicam 2024-04-21 18-32-23-414 (2).mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/25aa2044-49a5-419a-8817-a7bea1c8d9e0/bandicam_2024-04-21_18-32-23-414_(2).mp4)
    

## 부족한 점

1. 모바일 화면 크기에서 햄버거 버튼 만들기
2. hover 했을 때 서브메뉴 보여주기
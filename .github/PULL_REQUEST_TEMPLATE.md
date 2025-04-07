## 신경써서 구현한 부분
 제가 신경써서 구현한 부분은 아이콘을 로그인 입력창 부분 안에 박혀 있는 것처럼 보이게 만든 것입니다.
 .icon {
     position: relative;
     width: 100%;
     margin-bottom: 10px;
  }
.icon i {
     position: absolute;
     font-size: 30px;
     top: 50%;
     left: 25%;
     transform: translateY(-50%);
     color: gray;
     background-color: white;
  }
.icon input {
     text-align: left;
     width: 60%;
     padding: 20px 20px; 
     border-radius: 50px;
     border: none;
     outline: none;
     font-size: 24px;
     box-sizing: border-box;
     padding-left: 90px;  
  }
## 질문

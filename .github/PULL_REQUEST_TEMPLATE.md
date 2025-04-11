## 신경써서 구현한 부분
left-container
- intro-container
- intro
- box-conatine
    + txtbox

right-container
- login-container
    + login-head
    + input-container
    + submit

위와 같이 구역을 나누어 작업하였습니다.


화면 크기를 조절하였을 때 최대한 모양을 유지하기 위해 `display : flex`를 추가하였습니다.

로그인 화면에서 username과 psassword 앞에 이모티콘은 유니코드에서 들고오려했으나 디자인의 통일성을 위해 `svg`를 사용했습니다.

사람 (username)

```
<svg width="20" height="20" viewBox="0 0 24 24" fill="#888" xmlns="http://www.w3.org/2000/svg">
<path d="M12 12c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm0 2c-3.87 0-7 3.13-7 7v1h14v-1c0-3.87-3.13-7-7-7z"/>
</svg>
```

자물쇠 (password)

```
<svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M12 2C8.13 2 5 5.13 5 9v4H4v8h16v-8h-1v-4c0-3.87-3.13-7-7-7zm0 2c3.31 0 6 2.69 6 6v4H6v-4c0-3.31 2.69-6 6-6z" fill="#888"/>
</svg>
```



## 질문
개선 할 부분이 있다면 리뷰 해주세요!
피드백은 언제나 환영입니다!😉

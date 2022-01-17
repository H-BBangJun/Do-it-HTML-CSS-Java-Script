<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name = "author" coutent = "펭수">
    <title>과제1</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <div class = "header">
        <header style = "font-size : 25px;">이곳은 헤더 영역입니다.</header>
        <img src="https://file2.nocutnews.co.kr/newsroom/image/2019/10/17/20191017112711803642_0_777_437.jpg" alt="이미지 사진">
    </div>
    <div classs = "main">
        <main style = "font-size : 25px;">이 곳은 메인 영역입니다.</main>
      <div>
            저는 빨간색 상자입니다.
      </div>
    </div>
    <div class = "footer">
            <footer style = "font-size : 25px; ">이곳은 푸터 영역입니다.</footer>
         <div>
             저는 파란색 상자입니다.
        </div>
    </div>
</body>
</html>

./main.css
.header {
    background : yellowgreen;
    margin-top :20px;
    margin-bottom: 20px;
}
.main {
    background : tomato;
    margin-top :20px;
    margin-bottom: 20px;
}
.main div {
    background : red;
    width : 300px;
    height : 120px;
    width : 300px;
    height : 120px;
}
.footer {
    background : thistle;
    margin-top :20px;
    margin-bottom: 20px;
}
.footer div {
    background  : blue;
    color : white;
    width : 300px;
    height : 120px;
}

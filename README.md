<!DOCTYPE html>
<html lang="ko-KR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!-- *탭 로고 및 문구 변경 -->
    <title>케로로</title>
    <link rel="icon" href="logo.png" />

    <!-- *구글 웹폰트 적용 -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=42dot+Sans:wght@300..800&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap"
      rel="stylesheet"
    />

    <!-- *CSS 간단 적용 -->
    <style type="text/css">
      body {
        font-family: "42dot Sans", sans-serif;
        background-color: #a7e496;
      }
      #header {
        background-color: #a7e496;
        color: white;
        width: 100%;
        height: 160px;
      }
      #main {
        background-color: #f3edb9;
        color: #43613a;
        width: 80%;
        height: 600px;
        margin: auto;
      }
    </style>
  </head>

  <!-- *text-align: center로 모든 요소 가운데 정렬 -->
  <body style="text-align: center">
    <!-- *상단바 꾸미기 -->
    <div id="header">
      <img src="케로로로고.png" style="margin-top: 1%; height: 75%" />
    </div>

    <!-- *메인 컨테이너 -->
    <div id="main">
      <!-- *사진에 하이퍼링크 적용 -->
      <a href="https://namu.wiki/w/%EC%BC%80%EB%A1%9C%EB%A1%9C">
        <img src="케로로.png" style="margin-top: 1%; margin-bottom: 1%" />
      </a>

      <!-- *소개 -->
      <div style="font-size: 30px"><b>케로로</b></div>
      <div style="color: #77966f">중사</div>

      <!-- *<br>로 엔터 -->
      <br />

      <div>안녕! 나는 <b>케로로</b>야</div>
      <br />
      <div>좋아하는 간식은 스타후르츠★</div>

      <br />

      <div>최근에 생긴 취미는 <u>프로그래밍 공부</u>야</div>
      <a
        href="https://ko.wikipedia.org/wiki/C_(%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D_%EC%96%B8%EC%96%B4)"
      >
        <img src="c.png" style="margin-top: 1%; height: 10%" />
      </a>
      <a href="https://ko.wikipedia.org/wiki/C%2B%2B">
        <img src="cpp.png" style="margin-top: 1%; height: 10%" />
      </a>
      <a
        href="https://ko.wikipedia.org/wiki/%EC%8A%A4%EC%9C%84%ED%94%84%ED%8A%B8_(%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D_%EC%96%B8%EC%96%B4)"
      >
        <img src="swift.png" style="margin-top: 1%; height: 10%" />
      </a>
      <div>요즘은 이런 언어를 공부하고 있어~!</div>

      <br />

      <!-- *구분선 -->
      <hr width="80%" color="#ddd695" />
      <br />
      <div>나에 대해 더 궁금하다면 사진을 눌러 봐!</div>
    </div>
  </body>
</html>

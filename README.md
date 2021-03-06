# TIL
오늘 내가 배운 것들(Today I Learned)

## 1일차 학습 

- GitHub 계정 생성 
- GitHub 저장소 생성
- Gitkraken 설치
- Gitkraken 을 사용하여 GitHub 저장소 데이터를 내 컴퓨터로 복제(Clone)

## 월요일 학습

- HTML 이란?
- 시멘틱 마크업
- 기본 문법<br>
        <태그이름 속성="값"> 컨텐츠 </태그이름>
- 텅 빈 요소 <br>
     Empty Element - 닫는 태그를 가지지 않음
- 표준 호환모드 <br>
        <!doctype HTML> -> 왜 작성해야하는지 알게됨, 평소에는 쓰는 이유를 알지 못함
- 주 언어 설정 <br>
      <meta charset="utf-8"> -> 한글 호환언어 로만 알고 있었음
- 제목과 단락<br>
          h1 단 1회만 사용 / 주석표기법
- 이미지와 피규어 <br>
      img, figure, figcaption
- 문법 검사<br>
      https://validator.w3.org/ 문법 검사를 할수 있는 사이트가 있는지 몰랐음
      Entity코드 - https://entitycode.com/
- 순차/비순차 목록 <br>
       ul 비순차<br>
       ol 순차<br>
       li 목록요소<br>

       
## 화요일 학습

-앵커와 하이퍼링크<br>
1. 저장링크를 가진 앵커<br>
```html
<p>마우스 드래그로 그림을 그려보세요.
  <a href="" download="my_painting.png">다운로드</a>
</p>

<canvas width="300" height="300"></canvas>
```
2. 새 탭/창을 여는 앵커
```html
<a target="_blank" href="https://ko.wikipedia.org">
  위키백과 (새 탭에서 열림)
</a>
```
<br>
앵커안에 이미지를 넣어서 사용가능

-설명 목록 <br>
       dl 설명목록<br>
       -dt 용어<br>
       - dd 용어 설명<br>


-인용과 줄 바꿈 <br>
q 인라인 인용 <br>
cite 창작물 참조 <br>
blockquote 블록 인용 - 처음 알게된사실  <br>
br 줄바꿈 <br>

- 어휘 요소들 <br>
strong 중요성 강조 요소  <br>
em 강조 요소  <br>
b 중요성, 관련성 없이 다른 글자와 구분을 목적으로 사용 되는 요소 <br>
i  다른 글자와 구분되는 기술적 용어, 관용구, 생각 등에 사용 되는 요소 <br>

- 섹션/메인 요소<br>
article - 명시적으로 나열될 경우만 적합<br>
section 그룹화된 콘텐츠 <br>
독립성이 크면 article<br>
aside 부 컨텐츠 (광고)<br>
nav 링크 <br>
ul li요소 사용한다<br>
header -제목 목차 검색 요소<br>
footer - 저자 링크 저작권<br>
main 섹션요소 아님 메인요소 내부에 요소들이 들어가는것 헤더와 푸터는 제외<br>


## 수요일 학습

-컨테이너 요소<br>
의미를 가지지 않는다. 적절한 요소가 없을때 사용<br>
<div>그룹을 묶을때 (블록컨테이너)<br>
<span>인라인요소 한 글자 <br>

-텍스트 레벨 시멘틱 요소 <br>
아래첨자 - sub 수학식<br>
위첨자 - 각주 약어 sup<br>
mark 하이라이트 글자 요소<br>
abbr - 축약<br>
time 시간<br>
s 더이상 관련이 없거나 더 이상 정확하지 않은 요소<br>
취소선 <br>
  
```html
<span>공유<data value=“0”>0</data></span>
<p><time datetime=“2020-04-01”>오늘마감<time><data value=“7”>7개</data> 구매</p>
```

++까먹은거 <cite>출저<br>


-그룹핑요소 <br>
Address - 사람, 기업의 정보 제공 <br>
Pre 저장된 테스트 서식 보존 요소<br>
아스키코드, 컴퓨터 코드(code)<br>
전화 a- href tel : <br>
```html
<address> 
	서울특별시 주소 대표전화 <a hef=“tel:+822938372839>02 39393039<a>
</address> 
```




-임베디드 emcedded 요소 <br>
1. HTML 픽쳐(Picture) 요소
    1. Source srcset - media =“(min-width :900px)”속성으로 폭으로 반응형 웹 구현 가능
2. HTML 비디오(Video) 요소
    1. Source poster controls loop=“true” (반복)
3. HTML 오디오(Audio) 요소
    1. Src = img ,controls ,autoplay
4. HTML 트랙(Track) 요소
    1. 자막 표시 default 기본값 
```html
 <video src =“비디오 주소”>
       <track src =“자막” kind =“subtitles“ scrlang=“ko” label= “한국어”> 다른언어도 가능
       </video>
```
5. HTML 인라인 프레임(iframe) 요소
    1. 다른 html 페이지를 포함하여 화면에 표시! 동영상 지도!
    2. W,h 값설정 src frame border =“0”allowfullscreen style border = “0”
6. HTML 이미지 맵(map) 요소
    1. Area - 핫스팟 지역 정의 하이퍼링크 설정 map 내부에서만 사용 가능
    2. 이미지 맵 사이트를 사용하기 
    3. Alt,tilte 꼭 사용하기
    4. Shape coords (좌표값) href target alt hreflang download
7. HTML 확장 가능한 벡터그래픽(SVG) 요소
    1. 백터 그래픽을 기술하기 위한 마크업 언어
    2. <img> - svg 파일
    3. <svg>- circle cw=“75” cy=“75” r=“40”
    4. 코드로 넣어서 css 수정 가능























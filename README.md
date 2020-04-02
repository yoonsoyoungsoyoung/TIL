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
아래첨자 - <sub> 수학식
위첨자 - 각주 약어 <sup>
<mark> 하이라이트 글자 요소
<abbr> - 축약
<time> 시간
<s> 더이상 관련이 없거나 더 이상 정확하지 않은 요소
취소선 
  
```html
<span>공유<data value=“0”>0</data></span>
<p><time datetime=“2020-04-01”>오늘마감<time><data value=“7”>7개</data> 구매</p>
```
++까먹은거 <cite>출저



# 제목(Header)

# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
공백을 2칸넣어주면 줄바꿈이 된다 

# 강조(Emphasis)

_이텔릭_ 언더바 사이에 있는 글자는 기울어짐
**두껍게** ** ** 사이에 들어가면 두껍게
<b>아무런 글자</b>
**_이텔릭 + 두껍게_**
~~취소선~~
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록1
1. 순서가 필요한 목록2
1. 순서가 필요한 목록3 ← alt로 순서 바꿀 수 있음 
    1. 순서가 필요한 목록 ← 4칸 들여쓰기 하면 한 목록 안에 다시 순서지정 
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록 ← 4칸 들여쓰기 하면 목록 하나의 요소 안에 다시 리스트화 
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://www.google.com/">GOOGLE</a> ← 이걸 어떻게 쉽게 표시하느냐
<br/>링크를 대신하는 문법은 다음과 같다<br/>
[GOOGLE](https://www.google.com/) ← 표현하고 싶은 글자를 대괄호에 넣고 바로 옆 소괄호안에 링크
<br/>캡션을 달아주는 문법은 다음과 같다<br/>
<a href="https://www.google.com/" title="구글로 이동!">GOOGLE</a>
<br/>GOOGLE에다가 마우스 갖다대면 설명창이 뜬다 이걸 쉽게 하면?<br/>
[GOOGLE](https://www.google.com/ "구글로 이동!") ← 이렇게 하면 된다ㅇㅇ 쉽다

# 이미지(Image)

![KOREA POLYTECHINCS](https://www.kopo.ac.kr/assets2021/img/logo_header_pc.png)

[![KOREA POLYTECHINCS](https://www.kopo.ac.kr/assets2021/img/logo_header_pc.png)](https://www.kopo.ac.kr)
<br/>
대괄호로 묶고 링크를 옆에 입력하면 이미지 링크연결 가능함 즉 링크는 아무대나 연결할 수 있다.

# 인용문(BlackQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> (네이버 국어 사전) >로 사용하면 된다. 
<br/> 다음과 같이 중첩이 가능하다.
<br/>

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1  
>>> 중중첩된 인용문 2  
>>> 중중첩된 인용문 3  

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://www.google.com/">GOOGLE</a>
```
<br/>
```사이에다가 넣으면 코드를 강조할 수 있다.
예를들면 다음과 같다.<br/>

```css
.list > li {
    position: absolute;
    top: 48px;
}
```

```javascript
function f() {
    var a = 'AAA';
    return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext ← 줄바꿈 없이 입력 그대로 출력할 수 있다.
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--: 
static | 기준 없음 | 0
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

<br/>
--|--|--| 이렇게 칸을 나누면 되는데 :은 글자정렬을 의미한다 
<br/>
:위치에 따라 :--는 좌, --:는 우, :--:는 가운데 정렬

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href="https://www.naver.com/" title="네이버로 이동!" target="_blank">NAVER</a>

<img src="https://www.kopo.ac.kr/assets2021/img/logo_header_pc.png" alt="KOREA POLYTECHNICS">

# 수평선(Horizontal Rule)
#으로 헤더제목 쓰면 밑에 줄이 생긴다. 이걸 #을 안쓰고 줄긋기 하는 방법은 다음과 같다.
↓↓↓

---
***
___
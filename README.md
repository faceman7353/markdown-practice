# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈


동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세


# 강조
 _이텔릭_<br />
  **두껍게**

**_이텔릭_ + 두껍게**


~~취소선~~


<u>밑줄</u>

# 목록

1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록


- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록


# 링크

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com "GOOGLE로 이동")


<a href="https://naver.com" title="NAVER로 이동" target="_black">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동")


# 이미지
![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/css/images/logo.png)


# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어사전)

# 인용문 중첩 기능

> 인용문을 작성하세요
>> 중첩된 인용문     
>>> 중첩된 인용문 1  
>>> 중첩된 인용문 2  
>>> 중첩된 인용문 3  


# 인라인 코드 강조

css 에서 `background` 혹은   `background-image`   속성으로 요소에   배경이미지를 삽입 할수있습니다.


# 블록코드 강조

```html
<a href="https://google.com" target="_blank">GOOGLE</a>

```

```javascript
function func(){
    var = 'AAA';
    return a;
}

```

##### 등등으로 사용할수있다.


```plaintext
일반 문서 입니다.
텍스트만 강조하기위해 사용할수있습니다.


```

---
# 표

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치상 부모요소 | X
fixed | 뷰포트 | X

##### :으로 정렬을 할수있다.

---

# 원시 HTML(Raw html)

동해물과 <u>백두산</u>이 마르고 닳도록<br />
하느님이 보우하사 우리 나라만세


##### 원시 html에서는 u테그 대신에 span테그를 사용할수도 있다.

```plaintext
<span style="text-decoration: underline">백두산</span> 이렇게도 가능하다.

```

### 원시HTML이 많이 사용되니 참고로 더 공부해놓으면 좋을것같다.


***


# 수평선

```plaintext
어떤 특정 내용들을 구분해주기 위해 사용하는것.
```

---

***
___




# git사용법
##### git-hub 저장소에 저장하는 방법

```plaintext
현재 작성한 프로젝트를 git을통해 버전 관리하겠다 라는의미.

> git init

---

현재 상태 확인

> git status
---

작업한 내용을 버전 추가

> git add .
---
상태 확인 

> git status
---
이제 버전 만들기 시작

> git commit -m 'README.md 생성'
---
이제 막 저장소를 만들었으면 저장소를 연결해야한다.

>git remote add origin https://github.com/faceman7353/markdown-practice.git
---
연결되었으면 업로드

> git push origin master

```

***





# Node.js

```plaintext

Node.js는 Chrome V8 Javascript 엔진으로 만들어진(빌드된) Javascript 런타임
런타임 - 어떤 프로그래밍 언어가 동작하는 환경.

javascript  가 동작할수있는 환경
javascript는 프로그래밍 언어

 
Node.js가 깔린 컴퓨터
Chrome 같은 웹 브라우저


Node.js - 웹페이지를 개발하기 위해서 약간의 도움을 받기 위한 프로그램5ㅅ

웹페이지를 개발할시 html, css, javasctip만으로 개발할수있는데 비효율적
그래서 개인의 컴퓨터에  node.js 를 포함한 라이브러리를 설치후 html,css,javascript 로 변환하여
사용하여야한다.
변환작업을 만들어주어야한다.

```

# NVM(Node.js version Manaver - 내가 원할때 언제든 버전을 바꾸어 쓸수있는 기능)

***

```plaintext

nvm 윈도우버전
구글 검색창 
nvm-windows검색

첫번째 나오는 링크 클릭

조금내려가면 Download Now 클릭

nvm-setup.zip 다운로드

다운 및 설치 완료후

터미널에서 실행해봄.
- nvm --version
버전확인

이제 nvm 터미널에서 설치 및 사용

nvm install 16.14.2 (현재 최신 안정된 버전)
nvm use 16.14.2  

만약 exit:staus1 이라고 뜨면 터미널이나 vscode 를 관리자 권한으로 실행해서 다시 해보면 됨.

이제 터미널에서 node를 사용할수있게됨.

node --version
> v 16.14.2

만약 삭제를 할시

nvm uninstall 버전

NPM(node package manager)
-전세계의 개발자들이 만든 다양한 기능(패키지 , 모듈)들을 관리
npm은 생태계임.
패키지 = 모듈 같다고 보면된다.
 
 trade-off (상충관계)

```



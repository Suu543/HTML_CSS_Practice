# What is HTML?

**Hyper-Text-Markup-Language**

- Used to structure content on a web page(images, test, forms etc)
- We structure content using HTML tags
- HTML(Hyper Text Markup Language)은 페이지에 제목, 문단, 표, 이미지, 동영상 등을 정의하고 그 구조와 의미를 부여하는 정적 언어로 웹의 구조를 담당합니다.
- 온전히 튼튼한 구조(Semantic)를 만드는 것에만 집중해야 합니다.

```html
<p>content</P>
<a>link</a>
<img>
```

# What is CSS?

**Cascading Style Sheets**

- Works alongside HTML
- Used to style web pages to make them look better

- Change colors, position, effect, font sizes etc
- CSS(Cascading Style Sheets)는 마크업 언어(HTML, XML 등)가 실제 표시되는 방법(색상, 크기, 폰트, 레이아웃 등)을 지정하여 콘텐츠 구조를 꾸며주는 정적 언어로 웹의 시각적인 표현을 담당합니다.
- 적당한 크기와 아름다운 색상, 원하는 위치를 지정하는데 집중할 수 있습니다.

# What is JavaScript?

- JavaScript는 콘텐츠를 바꾸고 움직이는 등 페이지를 동적으로 꾸며주는 역할을 하는 프로그래밍 언어로 웹의 동적 처리를 담당합니다.
  JS는 HTML과 CSS를 동원해서 그들의 업무(구조, 시각적 표현 등)도 담당할 수 있지만, 그들만큼 잘하진 못하기 때문에(성능적으로) 되도록 동적 처리에만 집중해야 합니다.

  집을 지을 때 골조 전문, 미장 전문, 인테리어 전문 등 효율적인 작업을 위해 각 분야가 나뉘듯 웹 페이지를 제작할 때 각 언어의 역할을 다른 언어가 대체하지 않도록 주의해야 하며, 각 역할이 제대로 수행되도록 구조적, 기술적으로 언어(코드)를 최적화시킬 필요가 있습니다.
  (많은 입문자가 실전 과정으로 넘어갈 때 이 3가지의 단순한 역할을 도대체 왜 하나하나 파일과 폴더별로 구분하고 더 복잡하게 작성하는지 의아해하지만, 이는 언급한 것처럼 더욱 규모가 크고 복잡한 웹 페이지를 만들 때 구조적, 기술적으로 최적화하는 과정이며 유지/보수, 확장성, 생산성 등을 위해서 꼭 필요합니다. 이런 과정 자체를 이해하고 익숙해지는 것이 학습할 때 매우 중요합니다.

# Web Standard

- 웹 표준(Web Standard)이란 ‘웹에서 사용되는 표준 기술이나 규칙’을 의미하며 W3C의 권고안에서 나온 기술들이 여기에 해당합니다.
  이 표준 기술들을 기준으로 웹 브라우저들(크롬, IE, 사파리 등)이 만들어지는데, 브라우저를 만드는 업체(구글, MS, 애플 같은)에서 표준 기술을 해석하는 차이, 새로운 기술 삽입([표준화 제정 단계](https://wit.nts-corp.com/2013/10/16/280)에 따른) 등으로 조금은 다르게 구동되는 브라우저가 생기게 됩니다.
  지금은 거의 사라졌지만 Active X, Flash 같은 기술은 표준이 아닙니다.

# Web Accessibility

- 웹 접근성이란 정상적인 웹 콘텐츠 사용이 가능한 일반 사용자부터 고령자, 장애인 같은 신체적, 환경적 조건에 제한이 있는 사용자를 포함해 모든 사용자들이 동등하게 접근할 수 있는 웹 콘텐츠를 제작하는 방법을 말합니다.
  청각 장애인을 위해 영상에 자막을 넣거나, 마우스를 사용할 수 없는 사람들을 위해 키보드를 통해서도 웹을 이용할 수 있게 하거나(혹은 그 반대), 이미지에 대체 텍스트를 제공하는 간단한 방법들까지 모두 웹 접근성에 해당합니다.
  아래 링크에 접근성에 대한 지침이나 제작기법 등의 문서가 상세하게 정리되어 있으니 참고하세요.

  [웹 접근성 연구소](https://www.wah.or.kr:444/Accessibility/define.asp)
  [한국형 웹 콘텐츠 접근성 지침 2.1](https://www.wah.or.kr:444/Participation/guide.asp)
  [웹 콘텐츠 제작기법](https://www.wah.or.kr:444/Participation/technique.asp)

# VS CODE Snippet

| Windows 단축키            | macOS 단축키              | 설명                                      |
| ------------------------- | ------------------------- | ----------------------------------------- |
| “Ctrl + B”                | “Cmd + B”                 | 사이드바 열기/닫기                        |
| “Ctrl + P”                | “Cmd + P”                 | 빠른 열기(파일이나 기호 탐색)             |
| “Ctrl + Shift + P”        | “Cmd + Shift + P”         | 모든 명령 표시(에디터의 모든 명령에 접근) |
| “Ctrl + F”                | “Cmd + F”                 | 찾기(검색)                                |
| “Ctrl + H”                | “Cmd + Opt(Alt) + F”      | 찾기(검색)/바꾸기(대체)                   |
| “Alt + Up”                | “Alt + Up”                | 줄 위로 이동                              |
| “Alt + Down”              | “Alt + Down”              | 줄 아래로 이동                            |
| “Shift + Alt + UpArrow”   | “Shift + Alt + UpArrow”   | 위에 줄 복사                              |
| “Shift + Alt + DownArrow” | “Shift + Alt + DownArrow” | 아래 줄 복사                              |
| “Tab”                     | “Tab”                     | 들여쓰기                                  |
| “Shift + Tab”             | “Shift + Tab”             | 내어쓰기                                  |
| “Ctrl + PageUp”           | “Cmd + Shift + [”         | 이전 편집기 열기(좌측 창으로 전환)        |
| “Ctrl + PageDown”         | “Cmd + Shift + ]”         | 다음 편집기 열기(우측 창으로 전환)        |
| “Ctrl + \”                | “Cmd + \”                 | 편집기 분할(백슬래쉬)                     |
| “Ctrl + 숫자”             | “Cmd + 숫자”              | `숫자`번째 분할된 편집기 그룹에 포커스    |
| “Ctrl + W”                | “Cmd + W”                 | 편집기 닫기                               |

# Vector vs Rastor

| 이미지 종류 | 장점                                     | 단점                                                  |
| ----------- | ---------------------------------------- | ----------------------------------------------------- |
| 비트맵      | 정교하고 다양한 색상을 자연스럽게 표현   | 확대/축소 시 계단 현상, 품질 저하                     |
| 벡터        | 확대/축소에서 자유로움, 용량 변화가 없음 | 정교한 이미지(인물, 풍경 사진 같은)를 표현하기 어려움 |

# JPG(JPEG)

JPG(Joint Photographic coding Experts Group) Full-color와 Gray-scale의 압축을 위해 만들어졌으며 압축률이 훌륭해 사진이나 예술 분야에서 많이 사용됩니다.

- 손실 압축
- 표현 색상도(24비트, 약 1600만 색상) 뛰어나 고해상도 표시장치에 적합
- 이미지의 품질과 용량을 쉽게 조절 가능
- 가장 널리 쓰이는 이미지 포맷

> 높은 압축률(적은 용량)!

# PNG

PNG(Portable Network Graphics)는 Gif의 대체 포맷으로 개발되었습니다.

- 비손실 압축
- 8비트(256 색상) / 24비트(약 1600만 색상) 컬러 이미지 처리
- Alpha Channel 지원(투명도)
- W3C 권장 포맷

> 투명도 지원!

# GIF

IF(Graphics Interchange Format)는 이미지 파일 내에 이미지 및 문자열 같은 정보들을 저장할 수 있습니다.

- 비손실 압축
- 여러 장의 이미지를 한 개의 파일에 담을 수 있음(움짤, 애니메이션)
- 8비트 컬러만 지원(다양한 색상을 표현하는 작업에는 적합하지 않음)

> 동영상 같은 이미지!(애니메이션)

# WEBP

JPG, PNG, GIF를 모두 대체할 수 있는 구글이 개발한 이미지 포맷입니다.

- 완벽한 손실/비손실 압축 지원
- GIF 같은 애니메이션 지원
- Alpha Channel 지원(손실, 비손실 모두)

> 완벽한 포맷! 그러나 지원 브라우저가…

# SVG

SVG(Scalable Vector Graphics)는 마크업 언어(HTML/XML) 기반의 벡터 그래픽을 표현하는 포맷입니다.

- 해상도의 영향에서 자유로움
- CSS로 Styling 가능
- JavaScript로 Event Handling 가능
- 코드 혹은 파일로 사용 가능

> 벡터 이미지에 익숙하지 않다면 다루기 조금 까다로울 수 있습니다.

# HTML Entity List

| 기호 | 영어(발음)                               | 한글           |
| ---- | ---------------------------------------- | -------------- |
| `    | Grave(그레이브)                          | -              |
| ~    | Tilde(틸드)                              | 물결표시       |
| !    | Exclamation(엑스클러메이션) mark         | 느낌표         |
| @    | At(엣) sign                              | 골뱅이         |
| #    | Number(넘버) sign, Sharp(샵)             | 샵, 우물 정    |
| $    | Dollar(달러) sign                        | 달러           |
| %    | Percent(퍼센트) sign                     | 퍼센트         |
| ^    | Caret(캐럿)                              | -              |
| &    | Ampersand(엠퍼센드)                      | -              |
| *    | Asterisk(에스터리스크)                   | 별표           |
| -    | Hyphen(하이픈), Dash(대쉬)               | 마이너스       |
| _    | Underscore(언더스코어), Low dash(로대쉬) | 밑줄           |
| =    | Equals(이퀄) sign                        | 이꼬르         |
| “    | Quotation(쿼테이션) mark                 | 큰 따옴표      |
| ‘    | Apostrophe(아포스트로피)                 | 작은 따옴표    |
| :    | Colon(콜론)                              | 땡땡이         |
| ;    | Semicolon(세미콜론)                      | 털 달린 땡땡이 |
| ,    | Comma(콤마)                              | 쉼표           |
| .    | Period(피리어드), Dot(닷)                | 점, 마침표     |
| ?    | Question(퀘스천) mark                    | 물음표         |
| /    | Slash(슬래쉬)                            | -              |
| \|   | Vertical bar(버티컬 바)                  | -              |
| \    | Backslash(백슬래쉬)                      | -              |
| ()   | Parenthesis(퍼렌서시스)                  | (소)괄호       |
| {}   | Brace(브레이스)                          | 중괄호         |
| []   | Bracket(브래킷)                          | 대괄호         |
| <>   | Angle Bracket(앵글 브래킷)               | 꺽쇠괄호       |

# Open-Source License

> 오픈소스란 어떤 제품을 개발하는 과정에 필요한 소스 코드나 설계도를 누구나 접근해서 열람할 수 있도록 공개하는 것.

오픈소스라 하면 보통 무료 저작권이고 공짜로 사용해도 문제가 없다고 생각하지만 사실 다양한 종류의 오픈소스 라이선스가 존재하며 개인적 이용은 가능하지만, 상업적 이용에 제한이 있거나 경우에 따라 비용을 지불해야 할 수도 있습니다.

현실적으론 처음부터 끝까지 모든 코드를 직접 작성할 수 없기 때문에 많은 경우 오픈소스에 의존하게 됩니다. 개인적인 사용을 목적으로는 문제가 없겠지만, 회사에서(상업적으로) 아무 생각 없이 사용하다가는 문제가 돼서 해고당하거나 피해 보상을 해줘야 할지도 모릅니다.
물론 인터넷에 떠도는 코드 몇 줄 복사해서 썼다고 그 정도 심각한 문제가 되진 않겠지만, 항상 조심하는 것이 좋습니다.
회사에서 작업 중에 괜찮은 오픈소스를 찾았다면 반사적으로 ‘License’부터 찾으세요!

수많은 라이선스를 다 공부할 필요는 없고, 보기만 해도 흐뭇해지는 라이선스를 몇 가지 소개합니다.

### Apache License

아파치 소프트웨어 재단에서 자체 소프트웨어에 적용하기 위해 만든 라이선스입니다.
개인적/상업적 이용, 배포, 수정, 특허 신청이 가능합니다.

### MIT License

매사추세츠공과대학(MIT)에서 소프트웨어 학생들을 위해 개발한 라이선스입니다.
개인 소스에 이 라이선스를 사용하고 있다는 표시만 지켜주면 되며, 나머지 사용에 대한 제약은 없기 때문에 인기가 많습니다.

### BSD License

BSD(Berkeley Software Distribution)는 버클리 캘리포니아대학에서 개발한 라이선스입니다.
MIT와 동일하게 라이선스 표시만 지켜주시면 됩니다.

### Beerware

오픈소스 개발자에게 맥주를 사줘야 하는 라이선스입니다.
물론 만날 수 있다면 말이죠!

그 외 더 많은 오픈소스 라이선스에 대한 정보는 [OpenSource.org](https://opensource.org/licenses)에서 확인하실 수 있습니다.

# HTML Syntax(elements)

```HTML
<TAG></TAG>
<TAG>Content</TAG>
```

- 또한 태그는 열리고(open) 닫히는(close) 태그 구조를 가지고 있으며 이는 한 쌍입니다.
  (시작하고(start) 종료되는(end) 구조라고 부르기도 합니다)
  이 구조는 태그의 범위를 만들어 줍니다.
- 입문자가 주의할 점은 닫히는 태그는 태그 이름 앞에 `/`(슬래시)가 붙는다는 것입니다.

# Attributes and Value

- 태그(요소)의 기능을 확장하기 위해 ‘속성’을 사용할 수 있습니다.

  ```HTML
  <TAG Attribute(속성)="Value(값)"
  ```

- <img />는 이미지를 삽입할 때 사용하는 태그입니다. 하지만 태그만 사용하면 어떤 이미지를 삽입하는지 알 수 없기 때문에 src(source)라는 속성을 사용해서 삽입할 이미지의 경로를 지정합니다. 그리고 alt(alternative)라는 속성은 이미지를 출력하지 못하는 상황에 이미지 대신 보여질 텍스트를 지정합니다.<div></div>는 의미를 가지지 않는 태그로 어떤 내용이든 묶어낼(Wrap) 수 있습니다.위에선 '홍길동'이라는 텍스트를 묶었으나 그 내용이 무엇을 의미하는지 알 수 없기 때문에 name이라는 태그 별명(class)을 추가했습니다.

- > <img />와 같이 닫히는 태그가 없으면 빈 태그(Empty Tag)라고 합니다. 다시 설명합니다.

```html
<img src="./my_photo.jpg" alt="Hello World" />
<div class="name">
    Hello
</div>

<!-- 다음과 같이 이해할 수 있습니다. -->
<이미지삽입 소스위치="./my_photo.jpg" 대체텍스트="내 프로필 사진" />
<의미없는분할 태그별명="name">홍길동</의미없는분할>
```

# Parent and Child Element

- 태그A가 태그B의 콘텐츠로 사용되면, 태그B는 태그A의 부모 요소, 태그A는 태그B의 자식 요소라고 합니다.

```HTML
<PARENT>
    <CHILD></CHILD>
</PARENT>
```

```html
<section class="fruits">
	<h1>
        <section class="fruits">
  <h1>과일 목록</h1>
  <ul>
    <li>사과</li>
    <li>딸기</li>
    <li>바나나</li>
    <li>오렌지</li>
  </ul>
</section>

<!-- 다음과 같이 이해할 수 있습니다. -->
<섹션영역 태그별명="fruits">
  <주제1>과일 목록</주제1>
  <순서없는목록>
    <항목>사과</항목>
    <항목>딸기</항목>
    <항목>바나나</항목>
    <항목>오렌지</항목>
  </순서없는목록>
</섹션영역>

    </h1>
</section>

-----------------------------
<section></section> 안에는(콘텐츠) <h1></h1>, <ul></ul>, <li></li>가 있고 <ul></ul> 안에는(콘텐츠) <li></li>가 있습니다.
(이하 닫히는 태그는 생략할게요)
이러한 구조에서 <section>는 <h1>과 <ul>의 부모 요소입니다.
또한 <ul>은 <li>의 부모 요소입니다.
반대로 <h1>과 <ul>은 <section>의 자식 요소입니다.
또한 <li>는 <ul>의 자식 요소입니다.

여기서 <ul>은 <section>의 자식 요소이면서 <li>의 부모 요소입니다.
이처럼 부모와 자식 요소는 상대적인 개념입니다.
(조금 더 나아가면 <section>은 <li>의 조상(상위) 요소, 반대로 <li>는 <section>의 후손(하위) 요소라고 합니다)

우리가 기본적인 가계도를 통해 할아버지, 엄마, 삼촌, 형제 같은 호칭을 정의하듯(혹은 반대로 호칭을 통해 가계도를 이해하듯), HTML의 구조도 위와 같은 개념으로 호칭을 정의하여 추후 선택자(Selector)를 통해 CSS와 JS로 HTML을 다룰 때 중요하게 사용됩니다.
```

# Empty Tag

- HTML에는 닫히는 개념이 없는 태그들이 있습니다.
  다음과 같은 형태를 가집니다.

```HTML
<!-- `/`가 없는 빈 태그 -->
<TAG>

<!-- `/`가 있는 빈 태그 -->
<TAG/>
<TAG />
```

# HTML 문서의 범위

- `index.html` 같은 HTML 파일을 우리는 HTML 문서라고 표현할 수 있습니다.
  HTML 문서의 범위를 나타내는(의미하는) 태그들을 알아봅시다.

```html
<!DOCTYPE html>
<html>
  <head>
    문서의 정보
  </head>
  <body>
    문서의 구조
  </body>
</html>
```

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="author" content="홍길동">
    <meta name="description" content="우리 사이트가 최고!">
    <title>내 사이트</title>
    <link rel="stylesheet" href="./css/main.css">
    <script src="./js/main.js"></script>
</head>
<body>
    <section>
      <h1></h1>
      <div>
        <ul>
          <li></li>
          <li></li>
        </ul>
      </div>
    </section>
</body>
</html>
```

## HTML (전체 범위)

- <"HTML">는 HTML 문서의 전체 범위를 지정합니다.
  웹 브라우저가 해석해야 할 HTML 문서가 어디에서 시작하며, 어디에서 끝나는지 알려주는 역할을 합니다.

## HEAD (정보 범위)

- 웹 브라우저가 해석해야 할 HTML 문서의 정보 범위를 지정합니다.
  여기서 말하는 정보에는 
- 웹 페이지의 제목, 웹 페이지의 문자 인코딩 방식, 연결할 외부 파일의 위치, 웹 페이지를 구조화하기 위한 기본 세팅 값 같은 것들을 말합니다.
  다르게는 ‘**화면을 구성하기 위한 기본 설정**’이라고 표현할 수 있습니다.

## BODY (구조 범위)

- 웹 브라우저가 해석해야 할 HTML 문서의 구조 범위를 지정합니다.
  구조는 사용자가 화면을 통해서 볼 수 있는 내용(콘텐츠)의 형태나 레이아웃 등을 의미하며 로고, 헤더, 푸터, 내비게이션, 메뉴, 버튼, 입력창, 팝업, 광고 등 보이는 모든 것들이 구조에 해당합니다.
  구조는 BODY 범위 안에서만 생성합니다.

## DOCTYPE (DTD, 버전 지정)

- DOCTYPE(DTD, Document Type Definition)은 마크업 언어에서 문서 형식을 정의합니다.
  이는 웹 브라우저에 우리가 제공할 HTML 문서를 어떤 HTML 버전의 해석 방식으로 구조화하면 되는지를 알려줍니다.
  (HTML은 크게 1, 2, 3, 4, X-, 5 버전이 있습니다)

  현재의 표준 모드는 HTML5 입니다.

  ```html
  <!-- HTML 5 -->
  <!DOCTYPE html>
  ```

- > Windows 운영체제가 95, 98, ME, XP, Vista, 7, 8, 10 버전이 있는 것과 비슷하다고 생각하시면 쉽습니다.

## HTML 문서의 정보

```html
<head></head> 안에서 사용하는 태그들은 HTML 문서의 정보를 가지고 있습니다.
```

## TITLE(웹 페이지의 제목)

```html
<head>
	<title>네이버</title>
</head>
```

## META (웹 페이지의 정보)

- HTML 문서(웹페이지)에 관한 정보(표시 방식, 제작자(소유자), 내용, 키워드 등)를 검색엔진이나 브라우저에 제공합니다.
  빈(Empty) 태그입니다.

  ```HTML
  <head>
      <meta charset="UTF-8">
      <meta name="author" content="홍길동">
      <meta name="description" content="하하하">
  </head>
  
  <!-- 다음과 같이 이해할 수 있습니다. -->
  <문서의정보범위>
    <정보 문자인코딩방식="UTF-8">
    <정보 정보종류="사이트제작자" 정보값="홍길동">
    <정보 정보종류="사이트설명" 정보값="우리 사이트가 최고!">
  </문서의정보범위>
  ```

|           |                                                      |                                                      |
| --------- | ---------------------------------------------------- | ---------------------------------------------------- |
| 속성      | 의미                                                 | 값                                                   |
| `charset` | 문자인코딩 방식                                      | `UTF-8`, `EUC-KR` 등..                               |
| `name`    | 검색엔진 등에 제공하기 위한 정보의 종류(메타 데이터) | `author`, `description`, `keywords`, `viewport` 등.. |
| `content` | `name` 이나 `http-equiv` 속성의 값을 제공            |                                                      |

# LINK (CSS 불러오기)

- 외부 문서를 연결할 때 사용합니다.
  특히 HTML 외부에서 작성된 CSS 문서(`xxx.css` 파일)를 불러와 연결할 때 사용합니다.
  빈(Empty) 태그입니다.

```html
<head>
    <link rel="stylesheet" href="./css/main.css">
    <link rel="icon" href="./favicon.png">
</head>

<!-- 다음과 같이 이해할 수 있습니다. -->
<문서의정보범위>
  <외부문서연결 관계="CSS" 문서경로="./css/main.css">
  <외부문서연결 관계="사이트대표아이콘" 문서경로="./favicon.png">
</문서의정보범위>
```

| 속성   | 의미                                        | 값                        |
| ------ | ------------------------------------------- | ------------------------- |
| `rel`  | (필수)현재 문서와 외부 문서와의 관계를 지정 | `stylesheet`, `icon` 등.. |
| `href` | 외부 문서의 위치를 지정                     | 경로                      |

## STYLE(CSS 작성하기)

- CSS를 외부 문서에서 작성하여 연결하는 것이 아니고 HTML 문서 내부에 작성할 때 사용합니다.

  ```html
  <style>
    img {
      width: 100px;
      height: 200px;
    }
    p {
      font-size: 20px;
      font-weight: bold;
    }
  </style>
  
  <!-- 다음과 같이 이해할 수 있습니다. -->
  <스타일정의>
    <!-- CSS 코드 -->
  </스타일정의>
  ```

## SCRIPT(JS 불러오거나 작성하기)

```html
<!-- 불러오기 -->
<script src="./js/main.js"></script>

<!-- 작성하기 -->
<script>
  function windowOnClickHandler(event) {
    console.log(event);
  }
  window.addEventListener('click', windowOnClickHandler);
</script>

<!-- 다음과 같이 이해할 수 있습니다. -->

<!-- 불러오기 -->
<자바스크립트 문서경로="./js/main.js"></자바스크립트>

<!-- 작성하기 -->
<자바스크립트>
  <!-- JS 코드 -->
</자바스크립트>
```

# HTML 문서의 구조

```html
<body></body> 안에서 사용하는 태그들은 HTML 문서의 구조를 나타냅니다.
```

## DIV(막 쓰는 태그)

<div></div>의 ‘div’는 ‘division’으로 약자로 ‘분할’을 뜻하고 ‘문서의 부분이나 섹션을 정의’합니다.명확한 의미를 가지지 않기 때문에 정말 많은 경우 단순히 특정 범위를 묶는(wrap) 용도로 사용합니다.보통 이렇게 묶인 부분들에 CSS나 JS를 적용하게 됩니다.

```html
<body>
  <div>
    <p></p>
  </div>
  <div>
    <div>
      <h1></h1>
      <p></p>
    </div>
  </div>
</body>

<!-- 다음과 같이 이해할 수 있습니다. -->
<body>
  <묶음1>
    <p></p>
  </묶음1>
  <묶음2>
    <묶음2-1>
      <h1></h1>
      <p></p>
    </묶음2-1>
  </묶음2>
</body>
```

- > “DIV는 아무 의미가 없다. 왜냐하면 아무 의미가 없기 때문이다.”

## IMG(이미지 넣는 태그)

- < img >는 HTML에 이미지를 삽입할 때 사용합니다.(웹 페이지에 이미지를 삽입하는 방식은 크게 2가지로, ‘HTML에서 삽입(IMG)’과 ‘CSS에서 삽입(background)’이 있습니다)

```html
<body>
  <img src="./kitty.png" alt="냥이">
</body>

<!-- 다음과 같이 이해할 수 있습니다. -->
<body>
  <이미지 경로="./kitty.png" 대체텍스트="냥이">
</body>
```

|       |                                              |      |
| ----- | -------------------------------------------- | ---- |
| 속성  | 의미                                         | 값   |
| `src` | (필수)이미지의 URL                           | URL  |
| `alt` | (필수)이미지의 대체 텍스트(alternate)를 지정 |      |

- 위 표에서 ‘(필수)’라고 되어 있는 속성들(`src`, `alt`)은 ``를 사용할 때 반드시 포함되어야 할 속성(필수 속성, Required Attributes)입니다.
  만약 ``라고 작성하여 `alt` 속성이 누락되었다면 이는 웹 표준에 어긋납니다.

# 웹 표준 검사하기

- 우리가 작성한 HTML 문서가 표준에 부합하는지 테스트를 해볼 수 있습니다.
  [W3C validator](https://validator.w3.org/#validate_by_upload)에 접속하여 작성한 HTML 문서를 업로드하고 테스트를 시작하세요!
  기본적인 표준 여부를 판단할 수 있습니다.
  특히 입문자라면 익숙해질 때까지는 자주 확인하는 것이 좋습니다.

# CSS 선언 방식

### 태그에 직접 작성하기(인라인)

- 이 방법은 HTML 태그에 직접 작성하기 때문에 선택자가 필요하지 않습니다.

  ```html
  <div style="color: red;">태그에 직접 작성1</div> <!-- red -->
  <div style="color: red;">태그에 직접 작성2</div> <!-- red -->
  <div style="color: red;">태그에 직접 작성3</div> <!-- red -->
  <div style="color: red;">태그에 직접 작성4</div> <!-- red -->
  ```

### HTML에 포함하기(내장)

- CSS만 따로 작성하기 때문에 선택자가 필요합니다.
  CSS 코드가 HTML의 "<style> </style>" 안에 포함되어 있습니다.

  ```html
  <head>
    <style>
      div {
        color: red;
      }
    </style>  
  </head>
  <body>
    <div>HTML에 포함1</div> <!-- red -->
    <div>HTML에 포함2</div> <!-- red -->
    <div>HTML에 포함3</div> <!-- red -->
  </body>
  ```

### HTML 외부에서 불러오기

- CSS 코드를 완전히 분리할 수 있습니다.
  분리된 하나의 CSS 파일을 여러 HTML 파일이 불러와서 사용할 수 있겠네요.

```html
<!-- HTML 1 -->
<head>
  <link rel="stylesheet" href="/css/main.css">
</head>
<body>
  <div>HTML에 외부에서 불러오기1</div> <!-- red -->
</body>

<!-- HTML 2 -->
<head>
  <link rel="stylesheet" href="/css/main.css">
</head>
<body>
  <div>HTML에 외부에서 불러오기2</div> <!-- red -->
</body>

```

```css
/* main.css */
div {
  color: red;
}
```

# 선택자

- 위에서 설명했듯 선택자는 HTML의 특정한 요소를 선택하는 사인(sign)입니다.
  여러 종류가 있는데 우선 그중 2가지만 알아보겠습니다.

```CSS
/*<h1>은 글자색이 빨강이야!*/
h1 {
  color: red;
}
/*<p>는 글자색이 파랑이야!*/
p {
  color: blue;
}
```

```html
<h1>제목1</h1> <!--red-->
<h1>제목2</h1> <!--red-->
<p>본문1</p> <!--blue-->
<p>본문2</p> <!--blue-->
```

# 클래스로 찾기

```CSS
/*class="title"은 글자색이 빨강이야!*/
.title {
  color: red;
}
/*class="main-text"는 글자색이 파랑이야!*/
.main-text {
  color: blue;
}
```

```html
<h1 class="title">제목1</h1> <!--red-->
<h1>제목2</h1>
<p class="main-text">본문1</p> <!--blue-->
<p>본문2</p>
```

- `class`라는 HTML 속성에 원하는 별명을 입력합니다.
  제목에는 `title`을 본문에는 `main-text`라는 별명을 지정했네요.
  이제 CSS에서 이 별명을 기준으로 요소를 찾을 수 있습니다.
  단, 주의할 점은 선택자에 앞에 `.`이 붙는다는 것입니다.
  `.`은 클래스를 나타내며 CSS의 `.title`은 HTML의 `class="title"`와 동일합니다.
  `.`이 없는 선택자 `title`은 태그 ``를 의미하게 되니 전혀 다른 뜻으로 인식됩니다.
  이처럼 `.`과 같은 특수한 기호들을 이용해서 HTML과 CSS를 매칭하므로 누락하기 쉽습니다. 따라서 꼼꼼한 선택자 작성이 중요합니다.

# 속성

- 이제 속성을 알아봅시다.
  크기, 여백, 색상 같은 눈에 보이는 스타일을 지정할 수 있습니다.

# 크기

#### - width(가로 너비)

- 요소의 가로 너비를 지정합니다.
  단위는 `px`(pixels)을 사용합니다.

#### - height(세로 너비)

- #### 요소의 세로 너비를 지정합니다.

```css
div {
	width: 300px;
	요소가로너비: 너비값;
}

div {
    height: 150px;
    요소세로너비: 너비값;
}
```

#### font-size(글자 크기)

- 요소 내용(Text)의 글자 크기를 지정합니다.

```css
div {
  font-size: 16px;
  글자크기: 크기값;
}
```

# 여백

#### margin(요소의 바깥 여백)

- 요소의 **바깥 여백**을 지정합니다.
  바깥 여백은 요소와 요소 사이의 여백(거리, 공간)을 생성할 때 사용합니다.

```css
div {
  margin-top: 20px;
  margin-right: 20px;
  margin-bottom: 20px;
  margin-left: 20px;
  요소바깥여백-위쪽: 여백값;
  요소바깥여백-오른쪽: 여백값;
  요소바깥여백-아래쪽: 여백값;
  요소바깥여백-왼쪽: 여백값;
}
```

#### padding(요소의 내부 여백)

요소의 **내부 여백**을 지정합니다.
내부 여백은 자식 요소를 감싸는 여백을 의미합니다

```css
div {
  padding-top: 20px;
  padding-right: 20px;
  padding-bottom: 20px;
  padding-left: 20px;
  요소내부여백-위쪽: 여백값;
  요소내부여백-오른쪽: 여백값;
  요소내부여백-아래쪽: 여백값;
  요소내부여백-왼쪽: 여백값;
}
```

#### 색상

#### color(글자 색상)

- 요소 내용(Text)의 글자 색상을 지정합니다.
  정말 많은 입문자가 `font-color`, `text-color`로 실수를 합니다만 그런 속성은 없습니다.

```css
div {
	color: red;
	글자색상: 빨강
}
```

#### background(요소 색상)

- 요소의 배경 색상을 지정합니다.
  `color`는 글자의 색만 지정할 수 있으며, 요소의 (배경)색을 바꾸려면 `background-color`가 필요합니다.

```css
div {
  background-color: red;
  요소배경: 빨강;
}
```



# 참고자료

https://heropy.blog/2019/04/24/html-css-starter/


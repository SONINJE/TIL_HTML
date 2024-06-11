# Create a web page using HTML/CSS
![js](https://img.shields.io/badge/HTML-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)
![js](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
## HTML/CSS Base
### HTML
> + **Hyper Text Markup Language**
> >  + **HyperText** : 한 웹 페이지에서 다른 웹 페이지로 이동할 수 있는 기능을 갖춘 문서를 작성하기 위한 언어
> >  + 하이퍼링크 시스템, 구조를 설계할 때 사용하는 언어, **MARK UP** 언어를 가지고 있습니다.

### CSS
> + **Cascading Style Sheets**
> > + Style sheet
> >    - HTML 문서의 요소에 선택적으로 스타일을 적용할 수 있습니다.

## Requirements :floppy_disk:
빌드를 위한 필수 설치파일
+ [Visual Code](https://code.visualstudio.com)
+ [Chrome Brower](https://support.google.com/chrome/answer/95346?hl=ko&co=GENIE.Platform%3DDesktop)
  
## web development field
+ 웹 디자인
+ 웹 콘텐츠 기획
+ 프론트엔드 개발
+ 백엔드 개발
+ 서버 및 데이터베이스 관리

## Extensions
+ **view-in-browser** (Koppt HO)
  + 확장툴을 편집기에서 작성된 HTML 페이지를 웹 브라우저로 바로 확인할 수 있는 기능 제공
+ **Auto Close Tag** (Jun Han)
  + HTML/XML 클로즈 코드 자동 생성되는 확장 프로그램
+ **Live Preview** (microsoft.com)
  + HTML 파일 상단 오른쪽 분할돋보기 아이콘으로 실시간 미리보기 지원
+ **indent-rainbow** (oderwat)
  + 코드 가독성을 높여주는 기능
---

## SERVER / CLIENT
> + 웹 사이트를 제공하는 사람들은 다른 사람이 웹 사이트에 접근할 수 있게 하기 위해 웹 사이트를 구헝하고 있는 여러 가지 자원을 컴퓨터에 저장하고, 사람들이 접근할 수 있도록 환경을 설정한 다음 자원을 관리하는 소프트웨어를 실행한다
> 이때 자원을 저장하고 있는 컴퓨터를 "서버 컴퓨터"라고 한다

> + 서버의 반대편에는 CLIENT가 있다. 클라이언트는 웹을 이용하는 사용자 또는 컴퓨터를 뜻한다. 클라이언트가 웹 브라우저의 주소창에 URL을 입력해 웹 사이트에 대한 접근을 시도하면, 해당 URL에 위치한 웹 서버는 이를 감지에 클라이언트가 웹 사이트에 접근할 수 있게 한다.

![image](https://github.com/SONINJE/HTML_STUDY/assets/106592497/30b117bf-4cbb-4b80-b259-0863be36cb72)


## HTML 문서 기본 구조
``` HTML
<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="utf-8">
    <title>여기에는 문서의 제목을 입력해주세요</title>
  </head>
  <body>
    여기에 웹페이지에 표시할 콘텐츠(태그)를 입력해주세요
  </body>
</html>
```

### 문서 형식 선언 ***(!DOCTYPE html)***
> + 문서의 내용이 시작되기 전에 해당 문서가 어떤 마크업 형식으로 작성이 되어있는지 명시
>  + DOCTYPE 뒤에 html이라고 쓰여져 있는 것은 '이 문서가 HTML5로 작성되었다' 라는 뜻

### 문서의 시작과 끝 ***(html lang= "ko")***
> + 문서 형식을 선언 이후에 실제 문서의 내용을 표시하는 태그가 <html> 태그
>  + 태그에는 선택적으로 lang라는 속성을 추가할 수 있는데 lang = "kr" 은 '한국어를 사용'이라는 뜻 Ex) 영어 en, 일본어 ja 

### 문서의 정보 ***(head)***
> + **head**와 **boby**라는 두개의 하위 태그, 
>    + head의 역활은 브라우저에게 문서을 정보를 전달 (웹페이지의 품질에 영향을 주는 정보)
> + 다향은 설정 태그를 추가 입력 가능

### 인코딩 방식 설정 ***(meta charset="utf-8)***
> + meta 태그는 문서의 키워드 또는 설정 들 문서와 관련된 여러가지 항목들을 지정할 때 사용하는 태그 (문자셋 - 인코딩방식)설정
>    + utf-8로 설정 시 한국어 지원가능

### 문서의 제목 ***(title)***
> + 문서의 제목을 입력하는 태그
> + 웹페이지의 제목을 결정

### 화면에 표시될 콘텐츠 ***(boby)***
> + ''태그는 웹 브라우저 화면에 표시될 콘텐츠를 입력하는 태그
> + 텍스트, 이미지, 미디어 요소 등 다양한 콘텐츠들을 포함
>

## 태그 종류
[태그모음 tistory[참조]](https://stajun.tistory.com/entry/HTML-%ED%83%9C%EA%B7%B8-%EC%A0%95%EB%A6%AC)

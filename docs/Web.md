# Web

## 웹 브라우저

`.html` 이라는 확장자를 가진 파일을 구동해서 보여주는 소프트웨어이다.

**예시**

크롬, 엣지, 익스플로러, 사파리, 파이어폭스 ..

### 역할

 - `html` 파일의 뷰어 역할을 한다.
 - 사용자의 웹 서핑을 위한 다양한 부가 기능(즐겨찾기, 방문 기록 저장)을 제공한다.
 - 개발자에게 필요한 웹 페이지 분석을 위한 개발 도구도 제공한다.



## 웹 특성

### 표준

html문서를 만들었는데 3가지 브라우저에서 열었을 때 다 다르게 보여진다.

만약 버튼이라는 특성마저 브라우저마다 다르게 만들어진다면 웹 개발은 정말 복잡해 질 것이다.

그래서 표준을 만들어서 `HTML 5` 로 규격화 하였다.

이 표준을 준수하여 만들면 대부분의 브라우저에서 의도한 대로 보여지는 웹 페이지를 만들 수 있다.

### 접근성 

모든 사용자들이 차별없이 브라우저를 통해 웹 정보를 쉽게 사용할 수 있도록 하는 것을 말한다.

일시적으로 키보드나 마우스를 사용할 수 없는 상황에서도 웹 사용이 가능하도록 하는 것이 접근성을 높이는 예로 볼 수 있다.

크롬의 기본 첫 페이지를 살펴보았을 때

- 검색어를 입력할 때 키보드를 통해서 `tab` 키를 통해 다른 요소로 접근이 가능하게 하는 것
- 키보드가 없거나 작동하지 않은 상황에서 마우스로 입력할 수 있도록 하는 것

이런 특징들이 접근성을 높이는 방법이라고 할 수 있다.

### 호환성 (크로스 브라우징)

웹 브라우저의 버전, 종류에 관계없는 접근이 가능하도록 하는 것을 말한다.

접근이 보여지는 것에 대한 의미가 아니라 정보와 기능 제공에 있어서 동일해야 한다는 의미를 말한다.

웹 표준을 준수하면 브라우저 호환성을 확보할 수 있다.



## HTML  

**H**yper **T**ext **M**arkup **L**anguage

### Hyper Text  

다른 위치나 다른 웹 페이지로 이동할 수 있도록 만들어진 요소들을 의미한다.

지금은 웹 문서를 이루고 있는 요소 하나 하나가 하이퍼 텍스트로 의미가 확장되었다.

### Markup Language 

데이터를 그 자체로 어떤 방식으로 어디에 어떻게 표현할지 정의하고 구조를 나타내는 언어이다.

Programming Language  

데이터를 가공을 하고 `어떤 것을 해라` 라는 명령을 내리는 언어이다.

### 웹을 구성하는 언어

| 언어       | 역할                                                         |
| ---------- | ------------------------------------------------------------ |
| HTML       | 웹의 뼈대를 만드는 언어이다.<br> 여러 요소를 정의한다.       |
| CSS        | 각 요소들을 색깔, 모양을 변경할 수 있다.<br> 위치나 여러가지를 바꿀 수 있다. |
| JavaScript | 동적인 요소를 담당한다.                                      |



## 에디터

언어의 문법에 맞추어 편집을 도와주는 편집기이다.

| 구분              | 종류                        |
| ----------------- | --------------------------- |
| 웹 에디터         | `repl.it` `jsbin` `codepen` |
| 통합개발환경(IDE) | `vscode` `intelliJ`         |

### VSCode

##### 확장 프로그램

 - auto rename tag

   태그 작성 시에 여는 태그와 닫는 태그를 동시에 수정이 가능하게 해줌

 - live server

   코드를 수정하고 저장을 하면 브라우저에 실시간으로 반영되어 보여줌

 - prettier

   문법에 맞게 자동으로 코드를 수정 보완해줌

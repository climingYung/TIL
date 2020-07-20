리액트는 가장 큰 특징 중 3가지가 있는데 그중 하나가 바로 VIEW를 구성해주는 JSX라는 문법이 있다.

JSX
`const element = <h1>안녕하세요<h1>;`
위에 처럼 이상한 문법의 언어가 있다. 당연히 <script></script> 안에서 실행해도 에러가 나오고
.js안에 넣어서 실행해보아도 에러가 날것이다,

공식문서에 따르면 저건 공식 문법도 아니고 HTML 태그도 아닌 자바스크립트의 확장 문법이다.

```React.DomRender(
	element,
	document.getElementByID('myApp')
```

처럼 저 앨리먼트를 선언한 변수를 자바스크립트 안에 마크업을 하는 것이다.

가독성을 위해서 JSX 문법을 사용하는것.

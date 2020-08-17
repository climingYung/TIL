jqeury란 클라이언트 측 HTML스크립팅을 간소화 하기 위해 고안된 크로스 플랫폼 자바스크립트라이브러리이다.

    보통 자바스크립트에서 dom을 부를때

`const myBlock = document.getElementByID('myBlock');`

을 사용해서 가져온다면.

jquery에서 쉽게

`var $myBlock = $('#myBlock')`
이런식으로 쉽게 가져올수있다.

axios처럼 ajax라는 기능이 있어서 비동기호출을 할수 있다.

DOM 조작에 매우 유리하지만 cdn이나 Jquery 파일이 있어야 사용가능하다.

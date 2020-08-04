React Component에는 2가지가 있는데

class형 Component와
fucntion형 Component 2가지가 있다.

먼저 class형 컴포넌트에서는
Es6에서 도입된 Class문법이 있다.

`class App extends Component` 라고 선언해준다. 주의할게있다면 return하기전에 `render()`메서드를 적어주고 return안에는 한 개의 자식만 변환된다.

리액트 생명주기 API, state로 값을 받을때 그리고 컴포넌트 내에서 주요 기능을 사용할때 사용한다.

그리고 함수형 컴포넌트
자바스크립트에서 함수를 만드는것처럼 리액트 컴포넌트를 만들수 있는데 이를 함수형 컴포넌트라고한다.

`const examFucntuon = () => {}` return안에는 동일하게 한개의 자식만 반환한다.

함수형 컴포넌트와 다르게 생명주기 API를 사용하지않을 때 사용하는것같다.

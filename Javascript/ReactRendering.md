`const element = <h1>Hello, world</h1>;`
이런식으로 JSX를 이용해서 element를 만들어 보았다,

`ReactDom.Render()`를 이용하면 앨리멘트를 DOM에 렌더링 할 수있다.

index.html에 <div id="myApp"></div>인곳에 element를 렌더링 하기 위해선

```
const element = <h1>Hello, world</h1>;
ReactDOM.render(
	element,
	document.getElementById('myApp')
)
```

React에서 DOM을 업데이트할떄 Virturl DOM을 사용하기 떄문에 필요한 업데이트만 이용해서 DOM을 업데이트 해준다.

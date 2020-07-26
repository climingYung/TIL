State 상태 리액트에서 상태는 무엇일까?

Props는 사용자에게 중요한 정보를 주는것이라면

컴포넌트 내부에서 사용할수있는 상태 state는 꼭 필요하며 중요하다.

Props와 state는 결과적으론 분리되어있어야된다.

```class App extends COmponents {
	 constructor(props){
		 super(props);

		 this.state={
			 value: {title : ttile , subTitle: subTitle}
		 }
	 }
}
```

를 이용해서 컴포넌트안에 constructor가 있으면 컴포넌트가 처음에 실행되면 constructor가 실행되면서 props를 초기화 시켜주며

안에있는 `this.state`를이용해서 값을 할당해줄 수있다.

React의 Ref

기본적인 React의 데이터 플로우에서는 props는 부모 컴포넌트가 자식과 상호작용할 수있는 유일한 수단이다.

기본적인 데이터 플로우에서 벗어나 직접적으로 자식을 수정해야하는 경우가 생길떄 Ref를 이용해야된다.

사용해야될 경우엔 (React 공식문서)

1. 포커스, 텍스트 선택영역 or 미디어의 재생 관리
2. 애니메이션을 직접적으로 실행 시킬때,
3. 서드파티 DOM 라이브러리를 React와 같이 사용시

```
class MyComponent extends React.Component {
  constructor(props) {
    super(props);
    this.myRef = React.createRef();
  }
  render() {
    return <div ref={this.myRef} />;
  }
}
```

처럼 DOM ref를 주고 사용할 수 있다.

접근을 위해선

```const ref = <Element>.myRef.curent```
로 접근이 가능하다.


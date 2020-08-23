똑같은 노드를 복제 할때 쓸 수있는 `.cloneNode()` 라는 것이 있다.

선택가능한 옵션이있는데 자식과 같이 복사 할건지 해당 요소만 복제할건지 선택할수있다.

`var copy = element.cloneNode(true)` 기본값은 false지만 true로 복수 할지 선택이 가능하다.

true => 자식들과 함께 복사한다.
false => 선택한 요소만 복사한다.

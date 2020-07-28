react에선 UseState라는 Hook을 이용할 수있는데.

```
import React, { useState } from 'react';

function Example() {
  // ...
}
```

이런식으로 불러와서 실행하게 된다.

그리고 처음 리액트에서

```
class Example extends React.Component {
	constructor(props) {
		super(props);
		this.state = {
			name : ''
			email : '
		}
	}
}
```

class에선 이런식으로 처음에 state를 할당하는데 함수형에서는 this.state에 값을 할당하거나 읽을 수없다.

그래서 사용할수 있는게 useState이다.

```
function Exampole() {
	const [name, setName] = useState('');
	const [email, setemail] = useState('');
	<!-- 여기서 값을 변경하고 싶다면 setState(setemail , setName)을 이용해서 값을 변경하거나 감지할수 있다. -->
}

<input
	type="text"
	value={name}
	onChange={(e) => setName(e.target.value)}

>
```

처럼 사용이 가능하다

KEY??

react에서 Key는
어떤 항목에서 변경 추가 삭제할지에 대해서 식별하는것을 도와준다.

유니크한 값을 유지해야되기때문에 안정적인 고유성을 위해서 배열안에 넣어주는것이 좋다.

```
const number = [1, 2, 3, 4, 5];
const listItems = number.map(number) =>
	<li key{number.toString()}>
	{number}
	</li>
```

key를 이용할땐 다양한 리스트중에 다른 리스트를 식별하기 위해서 사용하는것이 좋다.

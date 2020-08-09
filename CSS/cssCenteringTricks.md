새롭게 알게된 CSS 박스 가운데 정렬.

2가지.

transform 이용

```
.center-box{
	position : relative;
	width:500px;
	height:500px;
}
.center-box > center-contents{
	position:  absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
}
```

를 이용하면된다 수직이면 translateY 수평이면 translateX를

display:flex를 이용한 속성이다.
display: flex; justify-content: center; align-items: center;

flex속성을 컨트롤할 수있는 justify-content , align-items를 이용한다.

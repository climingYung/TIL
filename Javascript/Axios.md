### Axios?

     axios는 node.js 와 브라우저를 위한 http통신 javascript 라이브러리이다.

     크로스 브라우징에 최적화되어 있어서 거의 모든 브라우저에서 사용이 가능한다.

##특징

    브라우저에선 XMLHttpRequests node에선 http 요청 생성
    Promis API 지원
    요청과 응답을 중단
    JSON 데이터 자동 변환
    요청 취소
    XSRF로 부터 보호하기위한 클라이언트 측 지원.

npm , yarn등을 이용해 install이 가능하며,

GET요청을 할땐.

```
Axios({
	method: 'get',
	url: 'uri/api',
	responseType: 'data'
})
	.then(fuction(data,res){
		res.data.api
	})
```

post 요청을 할땐

```
axios({
	method: 'post'
	url: '/user/12345'
	data: {
		name: 'blahbalh',
		age: '12125'
		job: 'model'
	}
})
```

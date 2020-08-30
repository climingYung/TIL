### JavaScript forEach(callback, thisArg)



Array객체에 사용할수 있는 메서드이다..

for문 보다 깔끔하며 

forEach의 인자로 callback 함수를 등록할 수있고, 배ㅔ열의 각 요소들이 반복될 ㄸ째 이 callback 함수가 호출된다.

```
var arr = ['가','나','다','라']; 
    arr.forEach(function(item,index,arr2){ 
        console.log(item,index,arr2[index+1]); 
})
```

처럼 사용가능하다.

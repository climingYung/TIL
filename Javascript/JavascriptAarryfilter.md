filter는 이름 그대로 요소들을 걸러내는 메소드이다.

filter는 특정 조건에 부합하는 배열의 모든 값을 배열의 형태를 리턴한다..

```
const arr = [
  {name: 'apple', price : 1000},
  {name: 'banana', price : 2000},
  {name: 'apple', price: 3000}
];

function isApple(element)  {
  if(element.name === 'apple')  {
    return true;
  }
}
```

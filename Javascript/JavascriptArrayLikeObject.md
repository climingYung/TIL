자바스크립트에는 객체같지만 아닌 유사배열이있다.

예를 들어서 ``` const likeArray = document.getElementClassName('item'); ```

처럼 클래스네임이 여러개 일때 객체인거 처럼 보여준다

typeof.likeArray //를 하게되면 object라는 결과가 나오고

Array.isArray(likeArray) //를 하게되면 false가 나온다.


likeArray instanceof Array // 도 false이다.


배열에서 쓰이는 문법을 사용할수가 없어서.

Prototpye.Array.call 
call이나 apply로 Arrary에서 쓰이는 함수들을 불러와서 사용해야한다.

Array에 유용한 메서드를 사용할수 없다.(아예 사용 못하는건 아님)

foreach에 key ,value 같은걸 사용할 수없다.




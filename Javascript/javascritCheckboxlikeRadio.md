체크박스같은데 라디오 기능을 하는 동작이 필요해서 찾아보다가 정리하게 됨.

```
$('.checkbox').click(function(){ // 먼저 같은 클래스 인 checkbox라는 클래스가 있는 인풋을 클릭했을떄
    $('.checkbox').each(function(){ // 클래스가 같은 checkbox를 each for을 간편하게 돈뒤
        $(this).prop('checked', false);  선택된 .checkbox 인풋 [i]번째를 attrtibutte를 false로 만들어준뒤
    });
    $(this).prop('checked', true); 나머지 클릭된 /checkbox인풋 [i]번쨰의 attributte를 true로 만들어준다.
});
```

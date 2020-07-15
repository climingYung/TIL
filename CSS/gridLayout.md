###Grid 레이아웃

    CSS Grid(그리드)는 2차원(행과 열)의 레이아웃 시스템을 제공한다
    Flexible Box도 훌륭하지만 비교적 단순한 1차원 레이아웃을 위하며, 좀 더 복잡한 레이아웃을 위해  CSS Grid를 사용할 수 있디.

#그리드는??
flex처럼 컨테이너와 아이템이라는 두 가지를 개념으로 구분되어 있다.
컨테이너는 아이템을 감싸는 부모와 자식관계입니다.

###Grid 컨테이너 속성
grid-template-rows 명시적 행(Track)의 크기를 정의
grid-template-columns 명시적 열(Track)의 크기를 정의
grid-template-areas 영역(Area) 이름을 참조해 템플릿 생성
grid-template grid-template-xxx의 단축 속성
row-gap(grid-row-gap) 행과 행 사이의 간격(Line)을 정의
column-gap(grid-column-gap) 열과 열 사이의 간격(Line)을 정의
gap(grid-gap) xxx-gap의 단축 속성
grid-auto-rows 암시적인 행(Track)의 크기를 정의
grid-auto-columns 암시적인 열(Track)의 크기를 정의
grid-auto-flow 자동 배치 알고리즘 방식을 정의
grid grid-template-xxx과 grid-auto-xxx의 단축 속성
align-content 그리드 콘텐츠(Grid Contents)를 수직(열 축) 정렬
justify-content 그리드 콘텐츠를 수평(행 축) 정렬
place-content align-content와 justify-content의 단축 속성
align-items 그리드 아이템(Items)들을 수직(열 축) 정렬
justify-items 그리드 아이템들을 수평(행 축) 정렬
place-items align-items와 justify-items의 단축 속성

### Grid 아이템 속성

    grid-row-start	그리드 아이템(Item)의 행 시작 위치 지정
    grid-row-end	그리드 아이템의 행 끝 위치 지정
    grid-row	grid-row-xxx의 단축 속성(행 시작/끝 위치)
    grid-column-start	그리드 아이템의 열 시작 위치 지정
    grid-column-end	그리드 아이템의 열 끝 위치 지정
    grid-column	grid-column-xxx의 단축 속성(열 시작/끝 위치)
    grid-area	영역(Area) 이름을 설정하거나, grid-row와 grid-column의 단축 속성
    align-self	단일 그리드 아이템을 수직(열 축) 정렬
    justify-self	단일 그리드 아이템을 수평(행 축) 정렬
    place-self	align-self와 justify-self의 단축 속성
    order	그리드 아이템의 배치 순서를 지정
    z-index	그리드 아이템의 쌓이는 순서를 지정

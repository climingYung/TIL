### nuxt.js 의 파일구조

Assets 디렉토리

    ```assets``` 디렉토리는 style폴더 img font같이 컴파일되지 않는 에셋들을 포함하는 폴더다

components 디렉토리

    ```components``` 디렉토리는 Vue.js 컴포넌트를 포함하는 디렉토리 입니다. asyncData나 fetch 메소드를 이 컴포넌트에서 사용가능하다.

Layout 디렉토리

    layouts 는 애플리케이션의 레이아웃을 포함하는 디렉토리이다. 레이아웃은 페이지의 모습이나 느낌을 변경하는데 사용됨 

middleware 디렉토리

    middleware는 애플리케이션의 미들웨어를 포함하는 디렉토리이다. 페이지나 레이아웃이 로딩되기전 정의 할수 있는 사용자 정의 함수를 정의 할수있다.

pages 디렉토리

    plugin 디렉토리는 루트 vue.js 애플리케이션이 생성되기 전 실행하고 싶은 자바스크립트 플러그인을 포함하는 디렉토리이다. 글로벌로 컴포넌트를 등록하고 Function이나 Constant를 사용할 수 있는 곳입니다

static 디렉토리는 

    서버의 루트에 바로연결되고 변경이 되지 않는 파일을 모아두는 곳이다.

Store 디렉토리는

    vuex의 store 파일을 포함하는 디렉토리 vuex는 nuxt에 의해 바로 사용가능하지만 index.js를 생성하면 프레임워크가 자동 생성된다.


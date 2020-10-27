# react

## ch01.Hello React!
```
  Hello React!
```

## ch02.JSX
```
  JSX 실습하기
  JSX
    - Javascript XML
    - 리액트 컴포넌트에서 브라우저에 렌더링 하기 위해 사용하는 XML 문법
  상수선언, 변수, 배열, map() 함수활용
```

## ch03.리액트 함수형 컴포넌트
```
  1.기본 컴포넌트
  2.속성(Property)을 갖는 컴포넌트
  3.태그내용(Children)을 갖는 컴포넌트
  4.상태값(State)을 갖는 컴포넌트
```

## ch04.클래스형 컴포넌트
```
  리액트 클래스형 컴포넌트
  1.기본 컴포넌트
  2.속성을 갖는 컴포넌트
  3.태그내용을 갖는 컴포넌트
  4.상태값을 갖는 컴포넌트
```

## ch05.리액트 이벤트
```
  1.함수형 컴포넌트 이벤트
  2.클래스형 컴포넌트 이벤트
```

## ch06.컴포넌트 ref 속성
```
  리액트 컴포넌트 ref 속성 실습하기
  ref
  - 리액트 JSX 문법에서 사용하는 식별 ID값
  - HTML의 id속성과 같은 개념이지만 JSX id속성을 권장하지 않음
```

## ch07. 컴포넌트 생명주기
```
  컴포넌트 생명주기
  - 리액트 모든 컴포넌트는 초기화(Mount)단계, 업데이트(Update)단계, 소멸(Unmount)단계를 거친다.
  - 각 단계 별로 자동으로 실행되는 함수를 생명주기 함수라고 한다.
  - 생명주기 함수들은 클래스 컴포넌트에서만 동작한다.

  초기화(Mount) 단계
  - DOM이 생성되고 브라우저에 컴포넌트가 나타나는 단계
  - constructor -> getDerivedStateFromProps -> render -> componentDidMount 순서로 실행

  업데이트(Update) 단계
  - 초기화 단계와 소멸단계 사이에서 반복되는 단계
  - 컴포넌트의 속성값(props), 상태값(state)이 변경되면 자동으로 업데이트 함수 실행
  - getDerivedStateFromProps -> shouldComponentUpdate -? render -> getSnapshotBeforeUpdate -> componentDidUpdate 순서로 실행

  소멸(Unmount) 단계
  - 마운트 단계에 반대과정으로 컴포넌트가 브라우저에서 제거될 때 실행되는 단계
  - componentWillUnmount 함수 실행
```

## ch08.리액트 훅
```
  React Hooks
  - 함수형 컴포넌트에서 사용되는 특별한 기능을 갖는 함수들
  - 훅 함수를 이용해서 함수형 컴포넌트에서도 컴포넌트의 상태값, 생명주기 함수를 구현 할 수 있다.

  useState()
  - 함수형 컴포넌트에서 상태값을 관리하는 Hook(기능, 함수)
  - 가장 많이 사용하는 리액트 Hook

  useEffect()
  - 함수형 컴포넌트가 랜더링될 때마다 특정 작업을 수행하도록 실행하는 Hook
  - 클래스형 컴포넌트의 componentDidMount, componentDidUpdate 생명주기 함수와 동일
  
  useRef()
  - 함수형 컴포넌트에서 ref를 생성, 할당할 수 있게 하는 Hook
```

## ch09.리액트 라우터(Router)
```
  리액트 라우터
  - SPA(Single Page Application) 개발하기 위한 화면 이동을 지원하는 리액트 라이브러리
  - 리액트 Router 라이브러리를 설치 'npm add react-router-dom'
  - 파라미터 라이브러리 설치 'npm add qs'
  - 리액트 Router를 동작 시키게 위해 index.js에서 App 컴포넌트 태그를 BrowserRouter 컴포넌트 태그로 바꿔준다.
```

## ch10.리액트 Context API
```
  Context API
  - 리액트 애플리케이션에서 전역적으로 사용할 데이터를 관리하는 컴포넌트
  - Context API에서 Provier는 데이터를 설정하고 Consumer에서 설정한 데이터를 사용한다.
```

## ch11.리액트 HTTP 통신
```
  axios
  - 리액트에서 가장 많이 사용하는 타입스크립트 HTTP 클라이언트 라이브러리
  - API서버에 GET, POST 요청
  - 'npm install axios' 설치
```
## news-app
```
  리액트를 활용한 news-app 실습하기
```

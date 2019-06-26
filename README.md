# Learning Vuejs

\
Vue란?
- MVVM 패턴의 뷰모델(ViewModel) 레이어에 해당하는 화면(View)단 라이브러리

\
Vue 구조도
- View : 브라우저에서 사용자에게 비춰지는 화면
- ViewModel
    - DOM Listeners : View에서 이벤트가 발생했을 때 청취하여 JavaScript Objects 제어
    - Data Bindings : JavaScript Objects에 변화가 발생했을 때 View에 반영

\
Vue Instance
- Create Instance
```javascript
new Vue();
```

\
생성자 함수
```javascript
function FunctionName(parameters) {
    // define something
}
```
\
Vue Component
- 화면의 영역을 영역별로 구분하여 코드로 관리하는 것
- 재사용성 증가 == 코드의 반복 감소

\
Vue 전역 컴포넌트와 지역 컴포넌트의 차이점
1. 지역 컴포넌트는 컴포넌트 하위에 어떤 컴포넌트가 등록되었는지 알 수 있다.
2. 서비스를 구현할 때, 대부분 components라는 속성을 사용
3. Vue.component() 같이 전역 컴포넌트는 plugin이나 라이브러리와 같이 전역으로 사용해야 할 필요가 있는 경우 사용
4. 일반적으로는 components에 등록하여 사용

\
컴포넌트 통신

\
Event emit
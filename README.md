# Context API와 Hooks를 이용한 전역 상태 관리

## 데이터를 Set하기

    contexts/AppStateContext.jsx
    providers/AppStateProviders.jsx

1. 일단 context를 생성한다.
1. context.provider를 사용한다.
1. value를 사용한다.

## 데이러를 Get하기 - functional

    hooks/usePrototypes.js
    hooks/useOrders.js
    hooks/useAction.js

1. useContext로 context를 인자로 호출한다.
2. useContext의 리턴이 value이다.

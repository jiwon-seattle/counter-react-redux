React Redux - Counter

## What's included

```bash 
|-- Actions
|   |-- index.js
|   |-- mainAction.js
|   |   |-- function actionIncrement() : increse amounts
|   |   |-- function actionDecrement() : decrese amounts
|-- components : handling views
|   |-- Count.js
|   |-- Button.js
|-- containers : handling views function
|   |-- App.js : Button Component & Count Component 
|   |   |-- const mapStateToProps(state)
|   |   |-- const mapDispatchToProps(dispatch)
|-- Actions
|   |-- index.js : report externally
|   |-- mainReducer.js : Redux reduce
|   |   |-- const reducerCount(state, actions)
|   |   |-- const reducer: conbineReducers()
```

Reducer -> mapStateToProps -> Store -> mapDispatchToProps

<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fk.kakaocdn.net%2Fdn%2FbjvQ8h%2FbtqxRuPdY3H%2FC9xqDGuPzXGo0h8V6LeeQ0%2Fimg.png" width="550px" />

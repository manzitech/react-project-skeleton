## Redux

React JS accept many state manegement libraries like [Recoil] (https://recoiljs.org/), [Jotai] (https://jotai.org/), [Redux] (https://redux.js.org/), and others. You can choose one that is suitable for you and write it here in this folder.

For this example we are going to use Redux and redux toolkit. But you can also choose to setup the redux in the old fashion way with reducers, and actions. Below is a tree example of this project structure in case you choose to use redux toolkit.

/redux
    │   ├── /authentication
    │   │   ├── /authentication.slice.js
    │   │   ├── /authentication.actions.js
    │   │   └── /authentication.test.js
    │   ├── /authors
    │   │   ├── /authors.slice.js
    │   │   ├── /authors.actions.js
    │   │   └── /authors.test.js
    │   └── /books
    │       ├── /books.slice.js
    │       ├── /books.actions.js
    │       └── /books.test.js
    ├── rootReducer.js
    └── index.js


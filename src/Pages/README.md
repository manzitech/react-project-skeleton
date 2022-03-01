## Pages

This folder can be named also views. This is an important part of any react js project. Let us use an example of a book store. 

Anything within a Pages is an item that will likely only be used within that specific page - a BookForm that will only be used at the /books route, and an AuthorBlurb that will only be used on the /authors route. It might include specific forms, modals, buttons, any component that won't be global.

The reward of keeping everything domain-focused instead of putting all your pages together in components/pages is that it makes it really easy to know the structure of the application and understand the top level tree. If there are nested routes, you can always add a nested pages folder within the main route.

Below is an example of how this folder might look

    /Pages
        ├── /Authors
        │   ├── /AuthorsPage
        │   │   ├── AuthorsPage.js
        │   │   └── AuthorsPage.test.js
        │   └── /AuthorBlurb
        │       ├── /AuthorBlurb.js
        │       └── /AuthorBlurb.test.js
        ├── /Books
        │   ├── /BooksPage
        │   │   ├── BooksPage.js
        │   │   └── BooksPage.test.js
        │   └── /BookForm
        │       ├── /BookForm.js
        │       └── /BookForm.test.js
        └── /Login
            ├── LoginPage
            │   ├── LoginPage.styles.js
            │   ├── LoginPage.js
            │   └── LoginPage.test.js
            └── LoginForm
                ├── LoginForm.js
                └── LoginForm.test.js

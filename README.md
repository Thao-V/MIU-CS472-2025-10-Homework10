# Homework 10: Library App with Context
## Refactor the homework 9 to have 3 components
* `App` – wraps everything with BooksProvider and lays out the page.
* `AddBook` – a form to create a book.
* `BookList` – displays the list of books.
## Add Context to share data
* Create a BooksContext for this app.
* Wrap the app in a BooksProvider.
* Fetch books from your Homework 8 backend (GET /books) and fills books.
* Expose `AddBook` that POSTs to /books and updates state.
* Track loading and error.
## Submit your source code

# Library Management System - MongoDB

This project is a MongoDB-based Library Management System. It includes collections for Books, Authors, and Patrons, supporting a range of CRUD operations. This system is designed to manage library resources, such as books and their authors, along with patron information.

## Database Structure

### Collections

#### 1. Books
Stores details about the books in the library.
- **_id**: Unique identifier for each book.
- **title**: Title of the book.
- **author_id**: References the author in the `Authors` collection.
- **genres**: Array of genres the book belongs to.
- **published_year**: Year the book was published.
- **available**: Boolean indicating if the book is available for borrowing.

#### 2. Authors
Stores details about the authors.
- **_id**: Unique identifier for each author.
- **name**: Name of the author.
- **nationality**: Author's nationality.
- **birth_year**: Year the author was born.
- **death_year**: Year the author died, if applicable.

#### 3. Patrons
Stores details about library patrons.
- **_id**: Unique identifier for each patron.
- **name**: Name of the patron.
- **email**: Email of the patron.
- **borrowed_books**: Array of book IDs borrowed by the patron.

## Initial Data Insertion

You can use the following commands to insert data into the collections.

### Conclusion
This Library Management System provides CRUD functionality to manage books, authors, and patrons using MongoDB. The system allows you to manage a library database with real-time data queries and updates. Feel free to extend the functionality as needed.



# LibManageX
This is a simple Library Management System implemented in C. It allows you to manage books, members, and book loans in a library. You can add, remove, and display books and members, as well as lend and return books.

## Features

- **Add Book**: Add a new book to the library.
- **Remove Book**: Remove an existing book from the library.
- **Show Books**: Display all the books available in the library.
- **Add Member**: Add a new member to the library.
- **Remove Member**: Remove an existing member from the library.
- **Show Members**: Display all the members of the library.
- **Lend Book**: Lend a book to a member.
- **Return Book**: Return a book from a member.
- **Show Loans**: Display all the current book loans.

## Data Structures

The system uses three main data structures:

1. `struct Book`:
   - `title` (string): The title of the book.
   - `copies` (int): The number of copies available.
   - `id` (int): The unique identifier for the book.
   - `author` (string): The author of the book.
   - `publicationYear` (int): The year the book was published.

2. `struct Member`:
   - `name` (string): The name of the member.
   - `id` (int): The unique identifier for the member.

3. `struct Loan`:
   - `bookId` (int): The ID of the book being loaned.
   - `memberId` (int): The ID of the member borrowing the book.
   - `lendDate` (string): The date the book was lent.
   - `returnDate` (string): The date the book is due to be returned.



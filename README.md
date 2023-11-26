<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Library Management System</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Library Management System</h1>
    </header>
    <main>
        <section id="book-list">
            <!-- Display book list here -->
        </section>
        <section id="add-book-form">
            <h2>Add a New Book</h2>
            <form id="book-form">
                <label for="title">Title:</label>
                <input type="text" id="title" required>
                <label for="author">Author:</label>
                <input type="text" id="author" required>
                <button type="button" onclick="addBook()">Add Book</button>
            </form>
        </section>
    </main>
    <script src="app.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em;
}

main {
    max-width: 800px;
    margin: 2em auto;
    padding: 0 1em;
}

form {
    display: flex;
    flex-direction: column;
    max-width: 300px;
    margin: auto;
}

label {
    margin-top: 1em;
}

button {
    margin-top: 1em;
    padding: 0.5em;
    cursor: pointer;
}

#book-list {
    margin-top: 2em;
}
// Dummy data
let books = [];

// Function to display books
function displayBooks() {
    const bookListSection = document.getElementById('book-list');
    bookListSection.innerHTML = '';

    books.forEach(book => {
        const bookElement = document.createElement('div');
        bookElement.innerHTML = `<strong>${book.title}</strong> by ${book.author}`;
        bookListSection.appendChild(bookElement);
    });
}

// Function to add a new book
function addBook() {
    const titleInput = document.getElementById('title');
    const authorInput = document.getElementById('author');

    const title = titleInput.value;
    const author = authorInput.value;

    if (title && author) {
        const newBook = { title, author };
        books.push(newBook);

        // Clear input fields
        titleInput.value = '';
        authorInput.value = '';

        // Update the displayed book list
        displayBooks();
    } else {
        alert('Please enter both title and author.');
    }
}

// Initial display
displayBooks();
npm init -y
npm install express
const express = require('express');
const app = express();
const port = 3000;

app.use(express.static('public'));

app.listen(port, () => {
    console.log(`Server is running at http://localhost:${port}`);
});
project-directory
|-- public
|   |-- index.html
|   |-- styles.css
|   |-- app.js
|-- server.js
|-- package.json
node server.js

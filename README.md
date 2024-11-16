# Book Explorer 📚

A mid-level project built with Next.js to manage and explore books. This project is designed as an interview task to evaluate your skills in API integration, state management, and frontend development.

---

## Features 🚀

1. **Home Page**:
   - Displays a list of books fetched from the API.
   - Includes a search bar to filter books by title or author.
   - Implements pagination (5 books per page).

2. **Book Details Page**:
   - Shows detailed information about a book (title, author, genre, description, and publication date).
   - Allows deleting a book.

3. **Add/Edit Book Page**:
   - A form to add a new book or edit an existing book with the following fields:
     - Title
     - Author
     - Genre
     - Description
     - Publication Date

4. **Responsive Design**:
   - Optimized for both desktop and mobile.

5. **Error Handling**:
   - Displays error messages when API calls fail.
   - Includes loading states for better user experience.

---

## API Endpoints 🛠️

This project uses a mock API (provided via JSON Server or custom Next.js API routes):

- **GET /api/books**: Fetch all books.
- **GET /api/books/:id**: Fetch details of a specific book.
- **POST /api/books**: Add a new book.
- **PUT /api/books/:id**: Update an existing book.
- **DELETE /api/books/:id**: Delete a book.

---

## Tech Stack 🖥️

- **Frontend**: Next.js, React, TypeScript
- **Styling**: Tailwind CSS / CSS Modules
- **API**: Mock API using JSON Server or Next.js API routes

---

## Getting Started 🔧

Follow these steps to set up the project locally:

### Prerequisites
- Node.js (v14 or later)
- npm or yarn

### Installation



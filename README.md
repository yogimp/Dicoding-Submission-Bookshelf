
# 📚 Bookshelf API

Bookshelf API Submission - Learning Class to Create Back-End Applications for Beginners

## 🚀 Description

Learn to Create Back-End Applications for Beginners <br>
Compiled by: Dicoding Indonesia

<div align="center">
  <img src="https://user-images.githubusercontent.com/95717485/225231893-e59de44d-0d3e-4e79-971b-a4d494565a74.png" alt="Dicoding AWS">
</div>

<br>

This class is intended for individuals who want to step up to become a Back-End Developer with AWS's international competency standards. At the end of the class, students can independently create simple RESTful APIs to support the functionality of an application.

---

## 🛠️ How to Use the Application

### 1. **Environment**
- **Node.js** (new version): [Download here](https://nodejs.org)
- **Postman** (optional): [Download here](https://www.postman.com/downloads)

### 2. **Clone Repository**
Clone repository :
```bash
https://github.com/ihsanuradib/Project-Dicoding-Bookshelf-API.git](https://github.com/yogimp/Dicoding-Submission-Bookshelf.git
```
Change directory:
```bash
cd Bookshelf-API
```

### 3. **Dependency Installation**
Run the following command to install all required dependencies :
```bash
npm install
```

### 4. **How to run the Server**
Run the application using the command :
```bash
npm start
```
Server will run at the default address : `http://localhost:5000`.

### 5. **API consumption**
Use tools like Postman or curl to access the following endpoints:
- **POST `/books`**: Adds a new book.
- **GET `/books`**: Retrieves a list of all books.
- **GET `/books/{id}`**: Retrieves book details by ID.
- **PUT `/books/{id}`**: Updates book information by ID.
- **DELETE `/books/{id}`**: Deletes books by ID.

### 6. **Request**
**Added New Books**
- Endpoint: `POST /books`
- Body (JSON):
  ```json
  {
    "name": "Belajar Node.js",
    "year": 2024,
    "author": "John Doe",
    "summary": "Panduan belajar Node.js untuk pemula",
    "publisher": "Dicoding Publisher",
    "pageCount": 300,
    "readPage": 50,
    "reading": true
  }
  ```

**Get a Book List**
- Endpoint: `GET /books`
- Response (example):
  ```json
  {
    "status": "success",
    "data": {
      "books": [
        {
          "id": "Qbax5Oy7L8WKf74l",
          "name": "Belajar Node.js",
          "publisher": "Dicoding Publisher"
        }
      ]
    }
  }
  ```

---

## 🧪 API Testing
1. Use **Postman** or **other tools** to send requests to the provided endpoints.
2. Make sure all operations (Create, Read, Update, Delete) run correctly according to the criteria.

---

## 📄 Learning Evaluation
This project is part of the final evaluation of the class "Learning to Create Back-End Applications for Beginners" by Dicoding Indonesia. This project includes creating a RESTful API with CRUD functionality.

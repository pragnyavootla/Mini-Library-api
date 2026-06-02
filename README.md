# Book Management REST API

## About the Project

For this task, I built a simple REST API using Node.js and Express to manage a collection of books. Instead of using a database, I stored the book data in an in-memory array, which allowed me to focus on understanding API routes and CRUD operations.

The server runs on port 3000 and each book is represented by an object containing an ID, title, and author.

## What I Implemented

I created four main endpoints:

* **GET /books** to retrieve all books currently stored in the array.
* **POST /books** to add new books to the collection.
* **PUT /books/:id** to update the details of an existing book.
* **DELETE /books/:id** to remove a book from the collection.

I also used Express middleware to handle JSON data sent in requests.

## Testing Process

To verify that the API was working correctly, I tested each endpoint individually.

I began by adding several books using the POST endpoint, including titles such as *The Alchemist* and *Atomic Habits*. After adding them, I used the GET endpoint to retrieve the complete list and confirm that the books had been stored successfully.

Next, I tested the PUT endpoint by replacing the details of one of the books and then used GET again to check that the updated information was reflected in the response.

Finally, I tested the DELETE endpoint by removing a book from the collection and verified through another GET request that it had been successfully deleted.

The screenshots included in this repository show the successful execution of each of these operations.

## Technologies Used

* Node.js
* Express.js
* JavaScript
* GitHub
* Thunder Client

## What I Learned

This project helped me understand how REST APIs work behind the scenes, how different HTTP methods are used for CRUD operations, and how Express simplifies the process of creating and managing routes in a Node.js application.

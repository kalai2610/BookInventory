Create a book :
POST http://localhost:8080/api/addBook 

Get a book :
GET http://localhost:8080/api/getBook/1000

Get all books :
GET http://localhost:8080/api/getBooks

Update a book :
PUT http://localhost:8080/api/updateBook/1000

Delete a book :
DELETE http://localhost:8080/api/deleteBook/1000

Create Token:
http://localhost:8080/user
- Each HTTP request requires token to access it.
If token is not generated and not given in Authorization part of request it throws 403 Access denied message.
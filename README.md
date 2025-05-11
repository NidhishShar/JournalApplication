# JournalApplication
Journal App – REST API
This is a simple Spring Boot REST API for managing journal entries. It supports basic CRUD operations using an in-memory HashMap as storage. The app is designed for educational or prototyping purposes.

Features
GET /journal
Retrieve all journal entries.

GET /journal/id/{myID}
Retrieve a specific journal entry by ID.

POST /journal
Create a new journal entry.
Request Body (JSON):

json
Copy
Edit
{
  "id": 1,
  "title": "My First Entry",
  "content": "Today I learned Spring Boot!"
}
PUT /journal/id/{id}
Update an existing journal entry.
Request Body (JSON): same format as POST.

DELETE /journal/id/{myID}
Delete a journal entry by ID.

Tech Stack
Java 17+

Spring Boot

RESTful APIs

No database (uses HashMap for simplicity)

Getting Started
Clone the repository.

Open the project in your IDE.

Run the application.

Use Postman to test the endpoints.

Notes
No persistent storage – data will reset each time the application restarts.

Ideal for learning the basics of REST APIs with Spring Boot.

Can be extended with database integration (e.g., JPA + MySQL/PostgreSQL).

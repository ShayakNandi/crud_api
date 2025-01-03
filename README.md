# Movie API - Golang CRUD Application

This is a simple RESTful API for managing movies, built using Golang and Gorilla Mux. It demonstrates basic CRUD (Create, Read, Update, Delete) operations without using a database. Currently, movie data is stored in-memory, but **PostgreSQL integration will be added soon** to persist the data.

## Features
- **Get all movies** – Retrieve the full list of movies.
- **Get a movie by ID** – Fetch details of a specific movie by providing its ID.
- **Create a new movie** – Add a new movie to the collection.
- **Update an existing movie** – Modify details of an existing movie.
- **Delete a movie** – Remove a movie from the collection by ID.

## Tech Stack
- **Golang** – Primary programming language.
- **Gorilla Mux** – Router and dispatcher for handling HTTP requests.

## Upcoming Enhancements
- **PostgreSQL Integration** – To store and manage movie data persistently.
- **Docker** – For containerized deployment.
- **Unit Testing** – Adding test coverage for all API endpoints.

## Endpoints
| Method | Endpoint               | Description                       |
|--------|------------------------|-----------------------------------|
| GET    | /movies                | Retrieve all movies               |
| GET    | /movies/{id}           | Get a specific movie by ID        |
| POST   | /movies                | Create a new movie                |
| PUT    | /movies/{id}           | Update an existing movie by ID    |
| DELETE | /movies/{id}           | Delete a movie by ID              |

## How to Run
1. Clone the repository.
   ```bash
   git clone <repository-url>
Navigate to the project directory.
bash
Copy code
cd <project-directory>
Install dependencies.
bash
Copy code
go mod tidy
Run the server.
bash
Copy code
go run main.go
Access the API at:
bash
Copy code
http://localhost:8000/movies
Project Structure
python
Copy code
.
├── main.go        # Main application file
├── go.mod         # Module dependencies
├── go.sum         # Dependency checksums
└── README.md      # Project documentation
Dependencies
Gorilla Mux – github.com/gorilla/mux
Install it by running:

bash
Copy code
go get -u github.com/gorilla/mux
Contributing
Feel free to fork the project and open pull requests for new features or improvements.

License
MIT License

vbnet
Copy code

Let me know if you'd like to include more about Docker, PostgreSQL setup, or deployment instructions!






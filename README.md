# Todo API

## Description
This is a simple API for task management (Todo) developed in .NET. The API allows creating, listing, updating, and deleting tasks.

## Technologies Used
- .NET 6
- SQLite

## Project Setup
### 1. Clone the Repository
```bash
git clone https://github.com/kevin-andrade/TodoAPI-simple.git
cd TodoAPI-simple.git
```

### 2. Apply Migrations
```bash
dotnet ef database update
```

### 3. Run the Project
```bash
dotnet run
```
The API will be running at `http://localhost:`.

### Example Endpoints
- `GET /` - Lists all tasks
- `GET /{id}` - Retrieves a task by ID
- `POST /` - Creates a new task
- `PUT /{id}` - Updates an existing task
- `DELETE /{id}` - Deletes a task

## Contribution
Feel free to open issues and pull requests for improvements to the project.

## License
This project is licensed under the MIT License.


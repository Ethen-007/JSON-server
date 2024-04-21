# JSON-SERVER 

## Introduction:
Welcome to the JSON Server repository! This project aims to provide a simple and lightweight solution for creating a mock REST API server using JSON files as data sources. With JSON Server, you can quickly set up a fully functional API server for your development or testing purposes without the need for a database.

## Getting Started:
To get started with JSON Server, follow these simple steps:

## Installation:
1.<strong>Install the JSON Server package globally via npm:</strong></br>

`npm install -g json-server`

2.<strong>Create a JSON file:</strong></br>

Create a JSON file containing your mock data. You can define different endpoints and data structures within this file to simulate various API routes and responses.Example JSON file (db.json):
```json
{
  "posts": [
    { "id": 1, "title": "Hello World", "author": "John Doe" }
  ]
}
```

3.<strong>Start the JSON Server by running the following command in your terminal, specifying the path to your JSON file:</strong></br>

`json-server --watch db.json` </br>
This command will start a local server at http://localhost:3000 serving your JSON data.

4.<strong>Accessing the API:</strong> </br>

Once the server is running, you can access your mock API endpoints using standard HTTP requests. For example:
```bash
GET http://localhost:3000/posts
```

This will return the list of posts from your JSON file.

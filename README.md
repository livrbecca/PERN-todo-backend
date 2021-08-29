# PERN-todo-backend

Backend server to the fullstack PERN application To-do list. 
View the full repo here: https://github.com/livrbecca/PERN

# Stack, frameworks and technologies used
- Express
- Node
- SQL
- Postgres
- Postman
- Beekeeper
- Pool

# To begin:
- ``npm install`` for dependencies
- ``node index.js`` to to run server

# Endpoints

**POST**
- localhost/todos
    - this adds a new todo to the SQL database, add a description.
    - to add via postman example:
    ``{"description": "new todo description goes here"}``
    - to add via SQL or Beekeeper Studio's query:
    ``INSERT INTO todo (description) 
      VALUES('new todo description goes here')``
    - To add via the frontend, type your new todo into the input box


**GET**
- localhost/todos
    - to view all todos in the database

- localhost/todos/:id
    - :id is a parameter, specify one to view a specific id
    - example:
    ``localhost/todos/14`` 
    
**PUT**
- localhost/todos/:id
    - :id is a parameter, specify one to view a update / edit a specific todo by id


**DELETE**
- localhost/todos/:id
    - :id is a parameter, specify one to delete a specific id




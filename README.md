# NEO4JCONNECT

GET & POST Employee

1) Prerequisites

Before starting, ensure you have the following installed on your system:

i) Python
ii) Flask
iii) Neo4j Python driver
You can install Flask and the Neo4j Python driver using pip:

code
pip install flask
pip install neo4j
Make sure to change the password in main.py to 'AdminGanesh' for the Bolt driver used to communicate with the Neo4j database.

2) Usage
To run the code, follow these steps:
Open the project in Visual Studio and run the project.
Download and Install Postman for testing API endpoints.

a) Creating an Employee Node
To create an employee node, send a POST request to http://localhost:5000/employees with JSON data in the request body containing name and emp_id fields.

Here's an example JSON body:

{
    "name": "ganesh",
    "emp_id": 125
}

b) Retrieving All Employee Nodes

To retrieve all employee nodes, send a GET request to http://localhost:5000/employees.
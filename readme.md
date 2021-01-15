# What is this repo?

Used as a local backend (fake-rest-api) for a project in the course Mobile computing and Internet of things.

Creating a real backend would be better, but I do not have the infrastructure nor do I want to spend money to host our api so I decided for a local one.

# How to install and run:

for a longer explanation on how it works: https://www.youtube.com/watch?v=1zkgdLZEdwM

1. install node-js
2. install json server: `npm install -g json-server`
3. download this repo and run with: `npm run json:server:students` to launch the students database

# How to use on the frontend:

Like you would use any rest API. The port (3000) may vary especially if a reactjs application is running locally as well.

GET ALL INDEX CARDS
http://localhost:3000/students

GET SINGLE INDEX CARD
http://localhost:3000/students/1

just try out how to access by going to http://localhost:3000/

# How to modify the database structure

if you want to add or remove an entry or rename an entry directly change the json file: `students.json`

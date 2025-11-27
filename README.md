TASK 1 — Student Record Manager
(In-Memory)
Objective
Build a mini student record manager with 3 routes.
Requirements
Maintain an array of students like:
let students = [
{ id: 1, name: "Amit", marks: 85 }
];
Routes to Build
1. GET /students → Return all students
2. POST /students → Add a new student
Request body example:
{
"name": "Rahul",
"marks": 92
}
3. GET /students/:id → Return student by ID
Expected Response Example
{
"id": 2,
"name": "Rahul",
"marks": 92
}

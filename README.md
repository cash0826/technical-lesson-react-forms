# Technical Lesson: New Employee Form

## Overview
In this lesson, you will practice implementing controlled forms and other controlled components within React.

## Scenario
You are working with a startup that wants to create an interface allowing the HR department to add employees to a list, including their roles within the company. To ensure the correct credentials, users must input and validate a password.

- Add a controlled search and a controlled form to the webpage.

#### Component Tree
```
└── App
    ├── Header
    ├── EmployeeForm
    └── EmployeeList
        └── Employee
```
- The `employees` state is stored in `App`, as `EmployeeList` needs it for rendering and `EmployeeForm` updates it.

#### : Setup
1. Fork and clone the repository.
2. Open the project in VSCode.
3. Run the following commands:
   ```sh
   npm install
   npm run dev
   ```
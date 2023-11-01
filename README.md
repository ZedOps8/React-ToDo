<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>React To-Do List App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
            background-color: #fff;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>React To-Do List App</h1>
    </header>
    <div class="container">
        <h2>About</h2>
        <p>This is a simple To-Do List app built with React. It allows you to add and delete tasks.</p>

  <h2>Usage</h2>
        <ul>
            <li>
                <strong>Add a Task:</strong> Enter a task in the input field and click the "Add Task" button.
            </li>
            <li>
                <strong>Delete a Task:</strong> Click the "Delete" button next to a task to remove it from the list.
            </li>
        </ul>

   <h2>Getting Started</h2>
        <ol>
            <li>Clone this repository to your local machine.</li>
            <li>Install dependencies using <code>npm install</code>.</li>
            <li>Start the development server using <code>npm start</code>.</li>
            <li>Access the app in your web browser at <code>http://localhost:3000</code>.</li>
        </ol>

  <h2>License</h2>
        <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>
    </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Management System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        form {
            max-width: 400px;
            margin: auto;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

    <h1>Employee Management System</h1>

    <form id="employeeForm">
        <label for="employeeName">Employee Name:</label>
        <input type="text" id="employeeName" name="employeeName" required>

        <label for="employeePosition">Position:</label>
        <input type="text" id="employeePosition" name="employeePosition" required>

        <label for="employeeSalary">Salary:</label>
        <input type="number" id="employeeSalary" name="employeeSalary" required>

        <button type="button" onclick="addEmployee()">Add Employee</button>
    </form>

    <h2>Employee List</h2>
    <table id="employeeTable">
        <thead>
            <tr>
                <th>Name</th>
                <th>Position</th>
                <th>Salary</th>
            </tr>
        </thead>
        <tbody id="employeeList">
            <!-- Employee data will be dynamically added here -->
        </tbody>
    </table>

    <script>
        function addEmployee() {
            var name = document.getElementById('employeeName').value;
            var position = document.getElementById('employeePosition').value;
            var salary = document.getElementById('employeeSalary').value;

            // Create a new row for the employee table
            var newRow = document.createElement('tr');

            // Add cells for name, position, and salary
            newRow.innerHTML = '<td>' + name + '</td><td>' + position + '</td><td>' + salary + '</td>';

            // Append the new row to the table body
            document.getElementById('employeeList').appendChild(newRow);

            // Clear the form fields
            document.getElementById('employeeForm').reset();
        }
    </script>

</body>
</html>

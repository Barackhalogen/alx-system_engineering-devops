0. Gather data from an API
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a Python script that, using this REST API, for a given employee ID, returns information about his/her TODO list progress.

Requirements:

You must use urllib or requests module
The script must accept an integer as a parameter, which is the employee ID
1. Export to CSV
mandatory
Score: 0.0% (Checks completed: 0.0%)
Using what you did in the task #0, extend your Python script to export data in the CSV format.
2. Export to JSON
mandatory
Score: 0.0% (Checks completed: 0.0%)
Using what you did in the task #0, extend your Python script to export data in the JSON format.

Requirements:

Records all tasks that are owned by this employee
Format must be: { "USER_ID": [{"task": "TASK_TITLE", "completed": TASK_COMPLETED_STATUS, "username": "USERNAME"}, {"task": "TASK_TITLE", "completed": TASK_COMPLETED_STATUS, "username": "USERNAME"}, ... ]}
File name must be: USER_ID.json
3. Dictionary of list of dictionaries
mandatory
Score: 0.0% (Checks completed: 0.0%)
Using what you did in the task #0, extend your Python script to export data in the JSON format.

Requirements:

Records all tasks from all employees
Format must be: { "USER_ID": [ {"username": "USERNAME", "task": "TASK_TITLE", "completed": TASK_COMPLETED_STATUS}, {"username": "USERNAME", "task": "TASK_TITLE", "completed": TASK_COMPLETED_STATUS}, ... ], "USER_ID": [ {"username": "USERNAME", "task": "TASK_TITLE", "completed": TASK_COMPLETED_STATUS}, {"username": "USERNAME", "task": "TASK_TITLE", "completed": TASK_COMPLETED_STATUS}, ... ]}
File name must be: todo_all_employees.json

# Employee Reviews

## Description

Allows the user to keep track of a department's staff, and the details of each employee within a department.

## Features

* Create new departments, each with their own empty "staff" array:
```
marketing = Department.new("Marketing")
```
* Create new employees:
```
new_employee = Employee.new(name, phone, email, salary )
```
* Add employees to a department:
```
marketing.add_employee(employee)
```
* Add text reviews to each employee using:
```
new_employee.add_employee_review(review)
```
* Give raises to an entire department.
* Give raises to specific employees in a department based upon criteria of the user's choosing.
* Scan employee review text and evaluate an employee's performance.
* Access an employees performance rating rating at any time.

Link to LucidChart ERD: https://www.lucidchart.com/invitations/accept/3c981a40-f421-4c9b-9616-028fa8349c6f

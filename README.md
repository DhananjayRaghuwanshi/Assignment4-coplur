# Assignment4-coplur
Basic Assignment: Employee Salary Management System
Objective: Design a basic Employee Salary Management System adhering to SOLID principles.
________________________________________
Use Case:
The system should calculate the salaries of different types of employees (e.g., permanent, contract, or interns). Each employee type has unique rules for calculating their salary.
________________________________________
Functional Requirements:
1.	Salary Calculation:
o	Implement salary calculation for permanent employees (basic pay + bonus).
o	Implement salary calculation for contract employees (hourly rate * hours worked).
2.	Payroll Generation:
o	Generate a detailed payroll report for each employee type.
3.	Extendable System:
o	Allow the addition of new employee types (e.g., freelancers) without modifying the existing salary calculation code.
4.	Adhere to SOLID Principles:
o	SRP: Separate responsibilities for salary calculation, employee details, and payroll generation.
o	OCP: Design the system to add new employee types without changing existing logic.
o	LSP: Ensure new employee types can replace existing ones without breaking functionality.
o	DIP: Depend on abstractions for salary calculations.
________________________________________
Example Entities:
1.	IEmployee interface:
o	Defines methods such as CalculateSalary() and GetDetails().
2.	Concrete Employee Types:
o	PermanentEmployee
o	ContractEmployee
3.	PayrollService:
o	Responsible for generating the payroll by invoking CalculateSalary() on all employees.


User Logger to log all the things on console.



Project Name: Payroll Management System

Description:
The Payroll Management System is a Java-based application designed to manage and process employee payrolls in an organization. This system supports different types of employees, including salaried employees, hourly employees, and commission-based employees, demonstrating object-oriented principles such as inheritance, polymorphism, and encapsulation. Key features of the system include:

Employee Hierarchy: The system defines an abstract Employee class and specific subclasses for different employee types (SalariedEmployee, HourlyEmployee, CommissionEmployee, and BasePlusCommissionEmployee). Each subclass implements the earning method to calculate the respective employee's earnings.

Polymorphic Processing: The system processes an array of Employee objects polymorphically, showcasing how different employee types can be treated uniformly yet respond appropriately to method calls.

Encapsulation and Validation: The classes ensure proper encapsulation with private fields and public getter/setter methods. They include validation to maintain data integrity, such as ensuring that wages are non-negative and hours worked are within a valid range.

Dynamic Behavior Adjustment: The system allows for dynamic changes to employee details, such as increasing the base salary of BasePlusCommissionEmployee instances, demonstrating runtime flexibility and extensibility.

Detailed Output: It provides detailed, formatted output for each employee, both individually and within the polymorphic processing loop, making the system's operation transparent and easy to understand.

This project exemplifies core Java programming skills, including inheritance, polymorphism, encapsulation, and exception handling, making it a robust solution for payroll management in any organization.

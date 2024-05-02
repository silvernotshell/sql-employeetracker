# sql-employeetracker

**Description:** A command-line application that can manage a company's employee database and utilizes Node.js, Inquirer, and MySQL.

**User Story:** As a business owner, I want to be able to view and manage the departments, roles, and employees in my company, so that I can organize and plan my business.

**Acceptance Criteria:**<br>
Given a command-line application that accepts user input<br>
<br>
When I start the application, then I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role<br>
<br>
When I choose to view all departments, then I am presented with a formatted table showing department names and department ids<br>
<br>
When I choose to view all roles, then I am presented with the job title, role id, the department that role belongs to, and the salary for that role<br>
<br>
When I choose to view all employees, then I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to<br>
<br>
When I choose to add a department, then I am prompted to enter the name of the department and that department is added to the database<br>
<br>
When I choose to add a role, then I am prompted to enter the name, salary, and department for the role and that role is added to the database<br>
<br>
When I choose to add an employee, then I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database<br>
<br>
When I choose to update an employee role, then I am prompted to select an employee to update and their new role and this information is updated in the database<br>

**Usage Instructions:**
1. Download the source code
2. Open in any code editor (VS CODE used in demo)
3. Open the terminal from the root folder
4. Type "node index.js" into the command line
5. Follow the prompts on screen to test and use the application

**Video Walkthrough:** https://youtu.be/75dX80ulsb4

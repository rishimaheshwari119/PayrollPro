<h1 align="center">
  <a style="text-decoration: none; color: white;" href="https://github.com/rishimaheshwari119/PayrollPro/" target="_blank" rel="noreferrer"> Human Resource Management System </a>ℹ️
  <br>
</h1>

<h4 align="center">A powerful HRMS built with React, Node.Js, Express, MySQL ...</h4>
<h6 align="center"><a href="https://github.com/rishimaheshwari119/PayrollPro/">https://github.com/rishimaheshwari119/PayrollPro</a></h6>

<p align="center">
  <!-- <img src="https://user-images.githubusercontent.com/56836643/105662731-c36f6c80-5ed0-11eb-8a96-4ec846675756.gif"> -->
</p>

## Description

This Human Resource Management System was made using [React](https://github.com/facebook/react#react-----) and [Bootstrap](https://getbootstrap.com/) amongst other libraries on the frontend and [Node.js](https://nodejs.org/en/) as well as [Express](https://expressjs.com/) on the backend. As for the database, I used [MySQL](https://www.mysql.com/) and [Sequelize](https://sequelize.org/) as the ORM.

### Features

- User authentication and authorization with [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) and personally developed [authentication middleware hoc](https://github.com/rishimaheshwari119/PayrollPro/blob/master/client/src/withAuth.js)
- User Password encryption using hashing with [bcrypt.js](https://www.npmjs.com/package/bcryptjs)
- Responsive design and use of [Bootstrap](https://getbootstrap.com/)
- Ability to Manage, Add, Update, Delete:
  - Users (Admin, Manager, Employee)
  - Departmens
  - Job positions
  - Applications (leave of absence...)
  - Payroll Management:
    - Salary details per Employee
    - Record payment history
  - Expense Management:
    - Add expenses
    - View sumamry of expenses
- Storage of environmental variables with [dotenv](https://www.npmjs.com/package/dotenv)


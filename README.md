
<h1>Employee_Review_System</h1>
<hr>
<p>A full stack, app used for reviewing employee.</p> 
<h3>Hoisted Link : <a href="https://ers-8w9y.onrender.com">ERS</a></h3>
<h2>Description</h2>
<p>Welcome to the Employee Review System. A full stack app, in which the admin, can assign the employees, to review each other on the basic of there work. The admin has special power, to make any other employee as the new admin. Admin can also make the new employee, and they can also assing, the reviewer and revieweee. The admin can see the current employee, and according to the review, the admin can remove the employee. The review given to the employee, is always going to be store in the database.</p>
<h2>Technologies Stack:</h2>
    <ul>
      <li><a href="https://code.visualstudio.com/">Vs Code </a>- awesome web-based text editor </li>
      <li><a href="https://nodejs.org/en//">node.js </a>- evented I/O for the backend </li>
      <li><a href="https://expressjs.com/">Express </a>- fast web framework for node.js </li>
      <li><a href="https://www.mongodb.com/">mongoDB </a>- the database for modern applications </li>
      <li><a href="http://www.passportjs.org/">Passport </a>- For Authentication purpose </li>
      <li>etc </li>
    </ul>

<h2>Features</h2>
    <ul>
      <li>Create and manage employee profiles</li>
      <li>Track employee performance</li>
      <li>Provide feedback to employees</li>
      <li>Generate performance reports</li>
    </ul>

<h2>Benefits</h2>
    <ul>
      <li>Improved employee performance</li>
      <li>Increased employee satisfaction</li>
      <li>Reduced turnover</li>
      <li>Improved communication between managers and employees</li>
    </ul>
<h2>How to setup the project on local system</h2>
<ul>
    <li>Clone this project</li>
    <li>Start by installing npm if you don't have it already.</li>
    <li>Navigate to Project Directory.</li>
</ul>
<p>After reaching the project directory you have to run the following the command.</p>
<p>
    
    npm install
    npm start || nodemon index.js
</p>

<p>If you want to make an employee as admin then use the secret key : ERS.<p>
<h2>Folder Structure</h2>

<pre>Employee Review System
    |
    |               |--->css
    |--->assets---->|--->images
    |             
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->admin_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->review_controller.js
    |                  |-->user_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->admin.js
    |--->routes---->|-->index.js
    |               |-->review.js
    |               |-->user.js
    |
    |              |--->_header.ejs
    |              |---> addEmployee.ejs
    |              |---> admin.ejs
    |              |---> employe.ejs
    |--->views---->|--->forget_password.ejs
    |              |--->home.ejs
    |              |--->layout.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    ````</pre>
    
<h2>Contact Us</h2>
<p>If you have any questions, please contact us at <a href="mailto:amansingh60046@gmail.com">amansingh60046@gmail.com</a>.</p>

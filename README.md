<h1>Task Manager Application</h1>
    <p>The Task Manager Application is a web-based task management system that utilizes Laravel as the back-end framework for implementing CRUD (Create, Read, Update, Delete) REST APIs, and Vue.js for the front-end interface to consume these APIs. This application allows users to manage their tasks in a convenient and organized manner.</p>
<h2>Features</h2>
<ul>
    <li>Create tasks: Users can create new tasks by providing a title and description.</li>
    <li>Read tasks: Users can view their existing tasks along with their details, such as title, description, and status.</li>
    <li>Update tasks: Users can edit the title, description, and status of their tasks.</li>
    <li>Delete tasks: Users can delete tasks that are no longer needed.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    
    <li>Laravel: Laravel is a PHP web application framework that provides a robust and scalable foundation for building web applications. It is used as the back-end framework in this application to implement REST APIs for task management.</li>
    <li>Vue.js: Vue.js is a JavaScript framework for building user interfaces. It is used as the front-end framework in this application to consume the REST APIs and provide a responsive and interactive user interface for managing tasks.</li>
</ul>

<h2>Installation</h2>
<ol>
    <li>Clone the repository to your local environment.</li>
    <li>Make sure you have PHP and Composer installed on your system.</li>
    <li>Run the following command to install the Laravel dependencies:</li>
    <pre><code>composer install</code></pre>
    <li>Copy the .env.example file to .env and configure your database settings.</li>
    <li>Run the following command to generate a key for your application:</li>
    <pre><code>php artisan key:generate</code></pre>
    <li>Run the following command to migrate the database:</li>
    <pre><code>php artisan migrate</code></pre>
    <li>Run the following command to seed the database with sample data:</li>
    <pre><code>php artisan db:seed</code></pre>
    <li>Run the following command to start the Laravel development server:</li>
    <pre><code>php artisan serve</code></pre>
    <li>Open your web browser and access the application at <code>http://localhost:8000</code>.</li>
</ol>
<h3>Registration</h3>
<p>To register a new account, follow these steps:</p>
<ol>
    <li>Click on the "Register" link in the top right corner of the application.</li>
    <li>Fill in the required information, including name, email, and password, in the registration form.</li>
    <li>Click on the "Register" button to submit the form and create a new account.</li>
</ol>
<h3>Login</h3>
<p>To login to an existing account, follow these steps:</p>
<ol>
    <li>Click on the "Login" link in the top right corner of the application.</li>
    <li>Enter your email and password in the login form.</li>
    <li>Click on the "Login" button to submit the form and log in to your account.</li>
</ol>

<h2>Usage</h2>
<p>Once the application is up and running, you can start managing tasks using the following actions:</p>
<ul>
    <li>Create a task: Click on the "Create Task" button and fill in the required details in the modal that appears. Click "Save" to create a new task.</li>
    <li>View tasks: All the tasks that you have created will be listed on the main page. You can view the details of a task by clicking on its title.</li>
    <li>Edit a task: To edit a task, click on the "Edit" button next to the task you want to modify. Update the details in the modal that appears and click "Save" to save the changes.</li>
    <li>Delete a task: To delete a task, click on the "Delete" button next to the task you

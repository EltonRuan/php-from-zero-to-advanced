<div align='center'>
 <img style="width:100%" src="https://capsule-render.vercel.app/api?type=soft&height=200&color=FFFFFF&text=PHP%20from%20zero%20to%20advanced&fontSize=50&fontAlign=50&strokeWidth=0&stroke=000000">
</div>

<div style="margin-bottom: 20px;">
  <h2>NAVIGATION </h2>

  <a href="#objective">OBJECTIVE</a> |
  <a href="#target-audience">TARGET AUDIENCE</a> |
  <a href="#learning-stages">LEARNING STAGES</a> |
  <a href="#how-to-run-the-projects">HOW TO RUN THE PROJECTS</a> |
  <a href="#final-considerations">FINAL CONSIDERATIONS</a>
</div>

## Objective

This repository was created with two main goals:

1. **To document my complete learning path** in PHP — from the very basics to advanced and complex topics — in a structured and practical way.
2. **To share knowledge with others** who are also interested in mastering PHP by providing open access to examples, explanations, and real-world projects.

Whether you're just starting out or looking to deepen your understanding of PHP, I hope this guide helps you learn effectively and build confidently.


## Target Audience

- Beginners who want a complete and practical roadmap.
- Developers looking to revisit PHP with updated practices.
- Anyone interested in building real projects with PHP.

## Learning Stages

This guide is organized by **stages**, not weeks — allowing you to learn at your own pace and dive deep into each area before moving forward.

### ✅ Stage 1: Language Fundamentals
- Syntax, variables, data types
- Operators and expressions
- Control structures (`if`, `else`, `switch`, loops)
- Superglobals (`$_GET`, `$_POST`, `$_SERVER`, etc.)
- Basic error handling

### ✅ Stage 2: Working with Forms and User Input
- Handling form data securely
- Validation and sanitization
- Dynamic form generation
- File uploads

### ✅ Stage 3: Arrays and Functions
- Indexed and associative arrays
- Array manipulation functions
- Creating reusable functions
- Scopes, parameters, and return types
- Anonymous functions and closures

### ✅ Stage 4: Files, Sessions, and State
- File reading/writing (`fopen`, `file_get_contents`)
- Sessions and cookies
- Login/logout systems
- Storing and retrieving data from JSON files

### ✅ Stage 5: Object-Oriented Programming (OOP)
- Classes, objects, methods, and properties
- Encapsulation, inheritance, polymorphism
- Interfaces and abstract classes
- Namespaces and autoloading
- Dependency management with Composer

### ✅ Stage 6: Working with Databases
- Connecting to MySQL using `PDO`
- CRUD operations (Create, Read, Update, Delete)
- Prepared statements and SQL injection prevention
- Relationships and foreign keys
- Basic database schema design

### ✅ Stage 7: APIs and Integration
- Consuming external APIs (using `cURL` and `file_get_contents`)
- Working with JSON and XML
- Building your own RESTful API with PHP
- Token-based authentication (JWT)

### ✅ Stage 8: Advanced Topics
- Error and exception handling
- Email sending (SMTP with PHPMailer)
- Pagination and filtering
- Regex in PHP
- Uploading and processing images
- Security best practices (XSS, CSRF, input filtering)

### ✅ Stage 9: Utilities and Integrations
- Sending emails with native `mail()` function and PHPMailer
- Email formatting (HTML content, attachments)
- Generating PDF files with libraries like FPDF or Dompdf
- Exporting data to CSV
- Logging and custom log files
- Building dynamic reports from a database
- Automating daily tasks (ex: send daily report via email)

### ✅ Stage 10: Modern PHP Without Frameworks
- Manual routing using $_SERVER['REQUEST_URI'] and a custom Router class
- Building a lightweight MVC structure from scratch
- Organizing the application into controllers, models, and views
- Creating a simple templating system using native PHP (include, require, output buffering)
- Managing environment settings with a basic .env file parser (no external libraries)
- Autoloading classes using spl_autoload_register() or Composer if needed

## How to Run the Projects

All projects and study materials are organized inside the root folder called php. The structure is designed to help you explore each learning stage separately, with dedicated folders for code, notes, and explanations.

### Project Folder Structure

<pre>
php/
├── steps/
│   ├── stage-01-fundamentals/
│   │   ├── code/       # PHP scripts and exercises
│   │   ├── notes/      # Markdown files with explanations and study notes
│   │   └── README.md   # Overview of this stage’s topics and projects
│   ├── stage-02-forms/
│   │   ├── code/
│   │   ├── notes/
│   │   └── README.md
│   └── ... (other stages)
└── README.md    # Main project readme (this file)
</pre>

### Running the Projects Locally

To run the PHP projects on your computer, follow these steps:

1.Install a local web server environment, if you haven't already:

- For Windows: XAMPP, Laragon
- For macOS: MAMP
- For Linux: Use your distro’s Apache/PHP/MySQL packages

2.Place the php folder inside your web server’s document root:

- For XAMPP: usually C:\xampp\htdocs\
- For MAMP: usually /Applications/MAMP/htdocs/
- For Laragon: usually C:\laragon\www\

3.Access the projects via browser:

- Open your browser and go to http://localhost/php/steps/stage-01-fundamentals/code/intro.php (or whichever file you want to test)
- Adjust the path based on the stage and file you want to run

4.For projects that require a database:

- Start your MySQL service from your server control panel
- Import any .sql files provided (if available)
- Configure database connection settings in the project’s config files or .env (if used)

### Tips

- Make sure your PHP version is 8.0 or higher for best compatibility.
- Use an editor like VS Code or PHPStorm for better coding experience.
- Always check each stage’s README.md inside the folders for detailed instructions or specific dependencies.
- Feel free to modify and experiment with the code to deepen your understanding.

## Final Considerations

This documentation was created to organize and summarize the essential concepts and practices of the PHP programming language, from the most basic syntax to advanced topics such as APIs, architecture, and security.

The goal is to provide a complete, hands-on learning path that makes PHP more accessible to developers who want to truly understand how it works under the hood — without relying exclusively on frameworks or external libraries.

Whether you're starting your journey in backend development or revisiting PHP to strengthen your skills, this guide is designed to support your growth through structured content, practical examples, and real-world project ideas.

Feel free to use, adapt, and contribute to this repository — both as a personal learning resource and a shared reference for the developer community. Let's build powerful applications with one of the most versatile and widely-used server-side languages in the world.


**© 2025 EltonRuan. All rights reserved.**



<footer align="center"> <img style="width:100%" src="https://capsule-render.vercel.app/api?type=soft&height=20&color=FFFFFF&fontSize=50&fontAlign=50&strokeWidth=0&descAlignY=80&stroke=000000&reversal=false&section=footer"> </footer>

# Group Project To-Do List App

This simple app was built using the MVC Architecture and by implementing "authorization" so users can sign up and log into the app. The idea came about as an app to delegate or assign tasks for group projects so other group members could see who was doing what and when it was complete. 

This app challenged us to keep our code as dry as possible, while adding complex functionality. 

We successfully created organized data schemas that enabled us to assign permissions to seperate users based on unique IDs. 

This model format was repeated and utilized for the organization of task items as well. The unique ID's were key itentifiers to seamlessly tie the functional logic together. 

The straight forward database schemas established a core for the complex functionality desired. And such, the code necessary for the controller logic was able to be much "dryer" than that of a multifaceted databse that creates endles parent and child nodes on every request. 

You can demo the site <a href="https://projectmanageapp.onrender.com">here</a>

![alt tag](https://github.com/BreaBang/todo-mvc-auth-local/blob/main/grouptodo.gif?raw=true)

# Objectives

- It's a beginner level app created to understand how MVC concept and logins are added

- This project also provided exposure to using EJS, Node.js, mongoose, mongoose schemas, passport, and other tools. 

- This was a group project that required 100devs developers to work together to understand the code and get it to run the way we wanted to.  
 
# What Did I Do On This Group Project?

The whole group started the project by walking through the code and learning how the to render items from the controller into the EJS file. 

My additonal task was to add the percentage of tasks complete line to the EJS todos view. To do this I added an new object to the getTodos asynch function begining on line 7 of todos.js in the controllers folder. I used some basic javascript store the total number of todo items left and the number complete int to seperate variables. I stored their remainder in a serpate variable and use parseFloat() and toFixed() to turn the remainder into a percentage. 

I also connected my local copy of the app to my own MongoDB database and installed the dependencies and got the server running. I was also able to deploy the application to Render. 

# Future optimizations

1) Add logic to percentage of tasks complete calculation to ensure the rendered value does not exceed 100% or fall under 0%. Right now it displays "NaN" or Not a NUmber if there are no todo items left and sometimes it display "infinity". 
2) Add a status bar or visual representation of project percent completeness.
3) Filter function to search "tasks" and "projects"
4) Create user roles and groups, that give users specific functionality, and limit access to other groups' projects.
5) Create a separate "projects" page, where the status of all projects can be seen.
6) Allow users to be assigned to specific projects and to roles within that project.
7) Add a password reset function.
8) Update the css to add a mobile view.
9) Ensure the fonts, color-schemes, alt-text and functionality are accessible.
10) Streamline the fonts and css styling accross all pages. 

# Packages/Dependencies Used 

- npm install bcrypt
- npm i connect-mongo, dotenv, ejs, express, express-flash, express-session, mongodb, mongoose, morgan, nodemon, passport, passport-local, validator

# Things to Add

- Create a `.env` file and add the following as `key: value` 
  - PORT: 2121 (can be any port example: 3000) 
  - DB_STRING: `your database URI` 
- Make sure your .env file is in your .gitignore before pushing to github. 
 ---

# Contributors

Robert Arroyo [@R0Bone]([https://github.com/...](https://github.com/R0Bone))
Breanna Bang [@breabang](https://github.com/breabang)
JP Canindo[@j...](https://github.com/...)
Aaron Clamp [@ronaldconn](https://github.com/ronaldconn)
Terrashawn Starks [@...](https://github.com/...)
Jacob Willkomm [@JacobWillkomm](https://github.com/JacobWillkomm)

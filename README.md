# Group Project To-Do List App

This simple app was built using the MVC Architecture and by implementing "authorization" so users can sign up and log into the app. The idea came about as an app to delegate or assign tasks for group projects so other group members could see who was doing what and when it was complete. 

![alt tag](https://github.com/BreaBang/todo-mvc-auth-local/blob/main/grouptodo.gif?raw=true)

# Objectives

- It's a beginner level app created to understand how MVC concept and logins are added

- This project also provided exposure to using EJS, Node.js, mongoose, mongoose schemas, passport, and other tools. 

- This was a group project that required 100devs developers to work together to understand the code and get it to run the way we wanted to.  

# Packages/Dependencies Used 

npm i bcrypt, connect-mongo, dotenv, ejs, express, express-flash, express-session, mongodb, mongoose, morgan, nodemon, passport, passport-local, validator

# Things to Add

- Create a `.env` file and add the following as `key: value` 
  - PORT: 2121 (can be any port example: 3000) 
  - DB_STRING: `your database URI` 
- Make sure your .env file is in your .gitignore before pushing to github. 
 ---
 
# What Did I Do On This Group Project?

The whole group started the project by walking through the code and learning how the to render items from the controller into the EJS file. 

My additonal task was to add the percentage of tasks complete line to the EJS todos view. To do this I added an new object to the getTodos asynch function begining on line 7 of todos.js in the controllers folder. I used some basic javascript store the total number of todo items left and the number complete int to seperate variables. I stored their remainder in a serpate variable and use parseFloat() and toFixed() to turn the remainder into a percentage. 

# If We Had More Time

We did not have much time to work on this project and there are functionalities that we would have added or changed if we had more time.

One thing I would do is add some logic to the percentage calculation so that 0 and 100% were the min and max values. Right now it displays "NaN" or Not a NUmber if there are no todo items left and sometimes it display "infinity". 

A second thing I would do is streamline the css on all four pages and use an easier to read font.

Third, I would make sure the color scheme and alt text on the app were more accessible. 



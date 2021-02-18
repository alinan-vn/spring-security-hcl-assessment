# Spring Security Authentication -- HCL ASSESSMENT

## Description
As a developer, build Authentication Provider in Spring Security.
Background of the problem statement:
You have been assigned a task by the team to add more flexibility rather than using the standard scenario in building Spring Security.

## Steps
1. You need to properly set up a database called "accountsample" with a table called "user" with the following columns: username (string), password (string), active (boolean), roles (string)
2. Insert an object into this table, ex. username: john, password: guest, active: 1, roles: USER
2. Run the SpringSecurityAuthenticationApplication.java file in the src/test/java/org.hcl.springsecurityauthentication folder
3. Go to http://localhost:8083/login
4. Put "john" in the username and "guest" in the password inputs
5. You will be redirected to a Welcome page!
5. If you put in wrong credentials, you will be told that they are wrong and to put new ones in.

## Requirements
- You should have a spring MVC web application as part of your submission. (JSP or Thymeleaf are both acceptable front-ends)
- User Password style in-memory storage is acceptable but variations on this (such as storing to database) are also acceptable.
- Users should be redirected to a login.html page if not authenticated before being redirected to the original page once authenticated.
- A few of the source code should be tracked on GitHub repositories. You need to document the tracked  files which are ignored during the final push to the GitHub repository.
- The submission of your GitHub repository link  is mandatory. In order to track your task, you need to share the link of the repository in the document. 
- The step-by-step process involved in completing this task should be documented.
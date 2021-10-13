
## Statement of Purpose :

 We have many applications like a canvas which would help students to view their courses, submit their assignments, view their grades. But this project Bearcat Study Buddy will be helpful for students to track their upcoming assignments,  helps in establishing strong communication between students and professors.
 
 
 ## Overview of Project :
 The overview of the project is to develop a web application that allows students to track their upcoming assignments or events related to a  specific Course.
 
* At first, we would have a login page where an existing user can log in or a new user can create an account.
* After they have created an account with their desired userID and password. They can upload their schedule.
* They can view courses they registered for, the to-do list, memo functionality of the assignments which will encourage them to complete a task on time.
* They would be provided with a chat option to ease the communication between students and professors.
* The users would be provided an option to customize the look of the application based on their choice.


## Benefits :

* This application would provide a single snapshot of the calendar to check the deadlines of upcoming tasks.
* This application would provide a feature with a memo functionality option which would help users to know about the details of the upcoming assignments.
* This application would provide a chat option to students to allow the interaction between students and professors.
* This application will provide a flexibility for users to customize the look of the application according to their choice as they would have better visualization  


## Epics / User Stories / Tasks :


Below would be the estimated user stories for this project.

1)As a student user, I want to login/Signup for the application.


#### Acceptance criteria checklist:

* Given that By opening the application  I would be able to login successfully into the application by providing valid credentials.
* Given that as a New users to the application we must be able to sign up for the application by providing all the required details.
* Given that when student users enters the invalid credentials I  must be restricted with login and provide the respective error message.

2)As a student User, I need to upload my course Schedule to visualise my courses in the home page of the application.

####  Acceptance criteria checklist:

* Given that student user, should be able to successfully upload my course schedule file without any issue.
* Given that student user must visualize the courses on the welcome page according to my schedule
* Given that student users who did not upload the schedule must be restricted for any access to the application and an option should be to upload the schedule to visualize their courses.

3)As a student User, I want to know about the upcoming to-do lists of the specific class to complete all the assignments on schedule.


####  Acceptance criteria checklist:

* Given that student user should be able to use the application efficiently to check  upcoming to-do lists of the specific course.

5) As a student user, I want the memo functionlity feature of the application to know about the details of upcoming assignments.

####  Acceptance criteria checklist:

* Given that student user should be able to use the application efficiently to check  memo functionality feature to check about the assigment details for the upcoming to-do lists of the specific course.

6)As a student user, I want to customize the theme of the application to have a better visualization.

####  Acceptance criteria checklist:

* Given that student user, should be able to use the application efficiently to check  memo functionality feature to check about the assigment details for the upcoming to-do lists of the specific course.


7)As a student user,I want an chat option to communicate with students and professors

####  Acceptance criteria checklist:

* Given that student user, should be able to able to communicate with other students by using the chat option.
* Given that student user, should be able to communicate with professors by using the chat option.


## Functional Requirements:

This tool would be a web application with with authentication and authorization. The following roles are suggested:

* Student User 


As a Student User, I want to create a user profile:

1) New student Users must create the user profile to use the application by sign-up option.
2) Existing student users must log in with a user id, password

As a Student User, I want to display my courses and to-do lists,memo functionality and my calender:

1) After successful login students will be directed to the page where they can view the list of courses enrolled.
2) They can view the to-do list for the upcoming tasks to complete tasks on time.
3) They can view the message of completing tasks by using the feature of memo functionality
4) Students can view their calender with the upcoming events,tasks they need to fulfill.

As a Student User,I want to Communicate with other students and Professors:

1) After login I will be able to use the chat option provided to communicate with other students.
2) Using the same chat option I would be able to communicate with my professors to retrieve any help required from them.

As a Student User,I want to choose different themes for my display:
1) I will be provided with an option to choose different themes based on the options available so I can choose my own choice of themes.


 The app must work on:

 * an iPhone SE
	
* an Android device
	
* a laptop computer
	
* an iPad

## Performance requirements:

* Use a computer 5 years old or newer when possible
* 2 GHz processor or faster
* 1GB RAM or greater
* 80 GB hard drive or larger
* Cable/DSL broadband connection or better
* 1024×768 or greater resolution monitor

## Other requirements:

* The student must have to remember their user credentials in order to login to the application.
* The student need to upload the course schedule to access the applcation.


## User Interface Sketches 


## Sign-in Page Layout
![HomePage (2)](https://user-images.githubusercontent.com/77635770/137050011-222de0e0-92b1-43fc-81b1-7764df2425a7.jpeg)


## Sign-up Page Layout
![signuppage](https://user-images.githubusercontent.com/77635770/133956002-9098930a-acdd-492f-a42d-938eb557acc6.jpeg)


## E-R diagram:

![Blank diagram](https://user-images.githubusercontent.com/77815724/137068116-68065add-301f-4e3c-9b3c-1465962cbfec.jpeg)

## Sample Data:

![Screenshot (72)](https://user-images.githubusercontent.com/77635770/136710070-3d2d7402-061e-41b7-bbc0-594f1a5963b0.png)

![image](https://user-images.githubusercontent.com/77593316/135742289-3aaf6943-d89d-4765-b39d-22d489b5cdf4.png)

![Screenshot (74)](https://user-images.githubusercontent.com/77635770/136712555-bb8dbef4-273e-4800-b5f7-dac379aacf55.png)

![scheduleID](https://user-images.githubusercontent.com/77635770/137074695-b5d14114-3090-46c6-9e0c-399757a49d3b.png)

![signUpDetails](https://user-images.githubusercontent.com/77635770/137078686-bcac2ab8-fbe5-429c-a40f-a2d0e62c542c.png)


## Stack description:

Below are the details for stack:

1)**Backend language + framework :** The backend language & framework  for this project would be  **Node.js / Express**


2)**Backend app host :** The backend app host would be **Heroku**


3)**Data host + type :** The Data host and type for this project would be  **Atlas MongoDB**


4)**Front-end page plan :** The Front-end page plan would be single-page application (SPA) is a web application or website that interacts with the user by dynamically rewriting the current web page with new data from the web server, instead of the default method of a web browser loading entire new pages. The goal is faster transitions that make the website feel more like a native app.


5)**Front-end responsive design :** The Front end responsive design would be **Bootstrap.**


6)**Static analysis tools :** The static analysis tools  used for this project is **Snyk.**


## Risks and assumptions:

* Student User should upload the schedule correctly by using a proper file format.
* The authentication must be properly verified.



## Deliverable artifacts:

* New student users successfully registering to the application
* Existing student users able to login sucessfully with their valid credentials.
* Existing student users able to upload the schedule properly.
* Upon logging in the users must be able to view the courses and the to-do notifications
* Student users can communciate with other students without difficulty.


## Scope:
We are building a web application that would have the following features like display the upcoming to-do lists on the home page of the application with memo functionality feature. The application would also provide a calendar option to view all the assignment's due dates in an organized and  Visualized way. The chat option inside the application would allow the communication between students in an efficient and better way.

This application does provide the functionality to submit their assignments, view their grades.


## Milestones:


## Schedule and Iteration Plan:
Below is the project schedule:
![image](https://user-images.githubusercontent.com/77593316/135742960-e4d0ed26-0e9f-4914-b147-8d3ac094288d.png)


## Budget :
![image](https://user-images.githubusercontent.com/77593316/135744040-e87f3b3c-5186-4554-9d72-5b6c03aecfec.png)


## Test plan with requirements:

1.The student user must be able login into the application by providing valid credentials

2.The student user must be restricted to access the application if they provide invalid credentials

3.The student user must be able to upload the schedule  properly as expected .

4.The student user must be able to verify the to-do list and memo functionality of the specific course in the application.

5.The student user must be able to customize the themes of the application.

















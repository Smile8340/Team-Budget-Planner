# Team-Budget-Planner
Project Objective :
As a developer, write a program using JavaScript to decide the budget of a specific team
Project Background:
As a developer, you are assigned to a project. You need to develop a website where program managers of a specific 
team will add details of professional deals they want to have with vendors. 
The finance team will check expenses of those teams and will decide their annual budget.

You must use the following:
● Visual Studio Code: An IDE to code for the application
● JavaScript: A programming language
● Git: To connect and push files from the local system to GitHub
● GitHub: To store the application code and track its versions
● JavaScript concepts: Functions, prototypes, primitives, objects, IIFEs, promises, async, and webpack


Following requirements should be met:

● Versions of the code should be tracked on GitHub repositories 
● Team Budget Planner should work properly
Step by Step Process :
First I created a React application by using the npx create react app function.
I then modified the index.js page to include a navbar from bootstrap.
I also used BrowserRouter to help navigate to the two pages of my application. 
Then I edited App.js to have 4 separated sections for each of the tasks: view, add, edit, delete.
The code in App.js serves as the Project Manager view. I created a json file called vendors and populated it with mock data for this project.
I added forms to the add section, edit section, and delete section to handle input.
Then I had each of these forms point to functions I wrote to modify the json object. 
Since I cannot directly save any changes to the object, I save an instance to local storage and update that instead. 
I then repeated these steps for the finance.js page and made changes so that the finance team can add, edit, and view the information necessary for their team.

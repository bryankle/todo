Application created on March 31, 2017
README written on June 5, 2017

This application was created independently as an exercise utilizing vanilla javascript along with the revealing modular pattern. 

User stories:
	- I can create, edit, and delete a task
	- I can view my tasks in categories for current tasks, completed, and all
	- I can assign a color to my task to represent the priority

Notes: The to do list is a commmon application, almost a rite of passage for any beginner programmer as I've noticed browsing portfolios, so I decided I'd join in! This application was created primarily with vanilla javascript and minimal jQuery (required for Material UI dropdown menu). At the time of building this, I was studying design patterns, and decided to implement the revealing module pattern inside the application to minimize the pollution of the global scope. The entire application was encased in an immediately invoked function expression assigned to the variable 'todoApp' with the function 'init' exposed to run the application.

A couple things I learned making this application: 
	- 'this'
		- I began using objects more frequently to organize my references and started to get a better grasp of what exactly 'this' referred to, especially when dealing with nested methods within objects and functions triggered by the DOM
	- Reusable code
		- Creating code that was reusable was essential here, especially when dealing with the process of creating DOM elements. I designed functions to group DOM creation of certain items which I could reuse (ie: creating more check boxes with functionality attached). I later discovered after this project when learning React that this was the similar premise behind the idea of a 'component', which I've been sold ever since!
	- Code organization
		- The code in this application was organized primarily into DOM references, events, and actions (functions). I also decided to approach the naming of variables and functions in a more precise manner which definitely helped while building the application, and even more so now, as I review my code from 2 months ago. I initially underestimated the importance of naming variables and functions correctly, but I've come to understand that with coherent naming, the code itself can communicate a significant amount of what it's doing with less reliance on commenting. 
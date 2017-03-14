# Homework #1

## Instructions
---
1. Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old.  Doing this will help you quickly discover any holes in your understanding.  Ask your questions on Slack.

	* Variables are "containers" for storing data.  Declaring a variable means you specify a name, and use the keyword var to declare it.  
	- You can declare an empty variable like this:
		var i; // make a variable called 'i'
	- You can make your variable refer to data when you declare it it like this:
		var i = 100 // number
		var i = 'Bob' // number
		var i = [] // empty list
		var i = {name: 'Betsy'} // object
		var i = ['flower', 'tree', 'ball', 63, true]
			// list of multi types
		var i = function() {console.log('Hello')}
			// function object
	- Variables are mutable.  This means you can change them. i = 0; i = 10 // i now = 10

	* Strings are a type of javascript object that can be any string of characters including numbers, letters, symbols, spaces etc.  
		- strings must be within '' or ""
		- strings are a type of js object that has its own special built in methods and properties

	* Functions (arguments, `return`)
		- functions are a type of js object that can hold reusable blocks of code and can be run over and over.  Each function is a program.  Functions can take parameters (arguments) or not.
		- functions can be run by "calling" the function.
		- example function:
				function functionName(name) {
					console.log('Hello ' + name);
				} // name is an argument
		- example function call: functionName('Harry');
		- functions can 'return' values and refer to the value:
			var a = function max(x, y) {
				if (x > y) {
					return x;
				} else {
					return y;
				}
			}
			max(342, 543) // returns 543

	* `if` statements are conditional statements that let you specify if 'this' then do 'that'.
	- the format is:
			if (condition is true) {
				do this
			} else { // if cond'n isn't true
				do this instead
			}

	* Boolean values (`true`, `false`)
		- every statement can be tested and return true or false.  
		- Variables can also refer to a boolean value of true or false.
		var x = 0;
		x === 0; //true
		x > 0; //false

		var likesPie = true;
		likesPie; // true
		var likesPie; // true by default
		i.e. does likePie exist?  true.


2. Install Node and NPM.  NPM comes packaged with Node. https://nodejs.org/en/download/


3. Install SublimeText3.  If you have another editor that you prefer then you can use that. https://www.sublimetext.com/3


4. Download this project folder from GitHub.


5. Navigate into the downloaded folder using Terminal(Mac) or Command Prompt(Windows).  `ls`(Mac), `pwd`(Windows) and `cd <directory_name>` are the commands you need to navigate around.


6. Once you are in the folder type the command `npm install`.  This will fetch all of the needed requirements for the project.


7. Run `npm test` to run the automated tests.  At first all of the tests will be broken.  You will fill out the functions in `exercises.js` to make the tests pass.


#### Congratulations on finishing Homework #1!
Apply to our full-time or part-time immersive program to learn cutting edge technologies that are used by top technology companies around the world.

Our part-time and full-time courses are 13 intense weeks of focused study on the most relevant technologies.  

Class sizes are small to ensure that each student gets individual attention from our world class instructors to help them succeed.  We also provide career support both during and after the course to help you succeed.  We are committed to your success.

For more information visit: https://www.lambdaschool.com

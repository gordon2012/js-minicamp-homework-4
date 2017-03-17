# Homework #4

## Instructions
---
1. Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old.  Doing this will help you quickly discover any holes in your understanding.  Ask your questions on Slack.
		
	* Callback Functions
		* In Javascript, functions are first class citizens, they can be stored in variables and called later. A callback is a function that is passed as an argument to another function.
	* Closure
		* A Closure is a wrapper around the scope of a function. Stuff inside can see outside variables, but the outside scope cannot see in. The entire scope of the inner function is saved for when it is later called.
	* arguments array
		* The arguments array is a simple array like object that contains a list of the arguments passed into a function. It can be turned into a genuine array using:
		``` js
		Array.from(arguments)
		```
	* recursion
		* Recursion is when a function calls itself, a base case is needed to avoid infinite recursion
	* prototype
		* The prototype is used to always give new instance objects created from an object certain properties and methods.
	* constructors
		* An object's constructor is what is initially called to generate default values when an instance variable is created with the new keyword.


2. Fork and clone this repo.  When you need to commit use the following commands.
		
	* git status
	* git add --all
	* git status
	* git commit -m "your commit message"
	* git push origin master

3. Install dependencies using `npm install`.  Run tests using `npm test`.

4. Make the tests pass!



#### Congratulations on finishing Homework #4!
Apply to our full-time or part-time immersive program to learn cutting edge technologies that are used by top technology companies around the world.

Our part-time and full-time courses are 13 intense weeks of focused study on the most relevant technologies.  

Class sizes are small to ensure that each student gets individual attention from our world class instructors to help them succeed.  We also provide career support both during and after the course to help you succeed.  We are committed to your success.

For more information visit: https://www.lambdaschool.com

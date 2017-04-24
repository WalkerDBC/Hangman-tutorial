# Step 01: Making the Game directory

## Previous build

## What we are doing
We are going to create the basic files required for a simple front-end game in four (4) simple steps:

1. Create a game folder
2. Make basic HTMl, CSS, and JS files
3. Add some simple functioning code
4. Connect the files to each other
5. Admire our progess

## Time estimate:  30 minutes

## Tools needed
- Sublime or other basic text editor
- Internet browser (e.g Chrome)

## Start building!

###1. Create a game folder

This is where we will hold the primary game files

a. Make a folder called `Hangman-Game`

####2. Make basic HTMl, CSS, and JS files
	
Inside of this folder, place the following files

a. `index.html`: this is the home page for the game
b.  `main.css`: this is the file used to create the look of the page
c. `main.js`: this is the file used for the game logic and behavior

#### 3. Add some simple code

Now lets add just a little code so that we can see how everything is linking and working

a. Create a very basic webpage:

`in index.html:`

```html
<!DOCTYPE html>
<html>

<head>
	<!-- 01. Provide a ti tle for your game -->
	<title>My-Hangman</title>
</head>

<body>
	<!-- 02. Add a little content... -->
	<div>
		<h1>Hello World!</h1>
	</div>
</body>

</html>
```
b. In `index.html`, add a`.game-outline` class to your `<div>` tag

```html
<!-- index.html -->
<div class="game-outline">
	<h1>Hello World!</h1>
</div>
```
c. In `main.css`, add simple styling for the `.game-outline` class:

`in main.css:`

```css
/*  OUTLINE STYLING */
/* Provide a visualization of divs during development */
.game-outline {
	outline: 1px solid orange;
}
```

d. In `main.js`, add simple js code

`in main.js:`

```javascript

// Add some code to trigger stronger error messages
"use strict()";

// Add at simple bit of code to verify the linkage

alert("javaScript is connected")

```


5. Admire our progress

Check out the web page in your browser

	a. Right click on the index.html page in Sublime, and 
	b. Select `Open in Browser`, OR, from your browser
	c. Go to `file`, `open file`, 
	d. Find the file, and open it
	e. "Hello World!" should be displayed front and center

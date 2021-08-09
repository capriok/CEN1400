# Portfolio

## What is this application?
A place where I can show off a little about myself such as:
- Biography
- Location
- Interests
- Favorites

## Features
- jQuery Mobile interactivity
- Random Fact generator
- Forms for user input
- Local storage data persistance

## Pages
- /Homepage
- /Arizona
- /Favorites
- ->/Dirtbikes
- ->/Surfing
- ->/Mythology
- /Form

#### /Homepage
"Bio panel" opens up on left side to display an overlay panel that renders an about me bio.
A link to my software developer portfolio can be found here.

#### /Arizona
This page is dedicated to my beautiful state, Arizona. You will find the state flag and a random fact that is generated on page load. Refresh for a new one!

#### /Favorites
Mine section:
A list view that routes to the specific "favorite" of mine. Each favorite route has details about how they play into my life.

Yours section:
You can enter some favorites of your own here. The names of said favorites will be diplayed in this section, as well as persisted through page refresh via browser local storage.
- Click the "Add Favorite" button to: Opens the add favorite panel
- Click the "Clear Storage" button to: Clears the "yours" favorites local storage

#### /Form
This is a feature that lets you save details about yourself in the browser local storage. The form includes field to describe you first and last name, your state, age, and sex.
- Click the "Submit Form" button to: Submit the form
- Click the "Clear Storage" button to: Clears the forms local storage


### Highlighted Feature
Random Fact Genertator
```js
function GenerateRandomFact () {
	const arizonaFacts = ['...', '...']
	const randomFact = arizonaFacts[Math.floor(Math.random() * 10)]
	document.getElementById('fact-target').innerText = randomFact
}
```

## Course

Professor: Gary Tanner
Course: SD140/CEN1400
Content: Mobile Application Development




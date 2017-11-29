# burger
Burger Eating App

## Live Link (If relevant)
 - www.example.com

## Description on how to use the app

- Enter your favorite burger (or as many of your favorites as you want) into the text field
- Click the 'add' button
- Once you have devoured the burger, click 'Devour Me' button

## Requirements

- Create an app that takes in a users input on a web page
- Input must be stored persistantly using mySQL 
- Must run through Node
- Must be deployed via Heroku and utilize Handlebars


## Technologies Used

- Javascript
- Express
- Node
- Heroku
- Handlebars
- MySQL

## Code Explaination
- Here, you can either provide a brief summary about your code and perhaps what you learned or you can go into specif detail about how you tackled certain tasks.
- Use code snippets for placing example code and then describing it
- Use subheaders to organize your thoughts
- This is the most important part as it will show other what your code does with out having to download the code. 
- In essense, this will also be a form of notes that you may later reference weeks later

-------------

##Here is an example of what a Readme could look like:

### AJAX Request to Giphy (Example)
I created a function that allowed me to make an AJAX request to the Giphy API and then allowed me to pass through a callback function in order to further process the JSON object that was returned. 

```
var settings = {
  "url": "http://api.giphy.com/v1/gifs/search?q=funny%20cat&api_key=dc6zaTOxFJmzC",
  "method": "GET"
  }
}
function getGiphyList(cb){
	$.ajax(settings).done(function (response) {
	  cb(response)
	});
}
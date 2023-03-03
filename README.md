# SuperheroHunter
This is a web application that allows users to search for their favorite Marvel superheroes and get detailed information about them. The app also allows users to mark their favorite superheroes.

Technologies used
This app is built using the following technologies:

HTML5
CSS3
JavaScript

How to use the app
Clone this repository to your local machine using git clone https://github.com/praveenkumarkece/SuperheroHunter.git
Open the project folder in your favorite text editor.
Open the index.html file in your web browser.
Use the search bar to search for your favorite Marvel superheroes.
To mark a superhero as your favorite, click on the star icon next to their name.
To view details about a superhero, click on their name in the search results.
To go back to the home page, click on the app logo or the back button.

Code overview
The app consists of two pages: index.html and singleCharacter.html.

index.html
The index.html file contains the main page of the app. It has a search bar and a list of search results. The app loads data from the Marvel API and saves it in the browser's localStorage. The app also uses localStorage to save the user's favorite superheroes.

The superHero.js file contains the JavaScript code that is used to build the search functionality of the app. It listens for user input in the search bar and filters the list of superheroes accordingly. It also listens for user clicks on the star icon and saves the user's favorite superheroes in localStorage.

singleCharacter.html
The singleCharacter.html file contains a page that displays detailed information about a single superhero. It loads the superhero data from localStorage and displays it on the page.

The singleCharacter.js file contains the JavaScript code that is used to build the functionality of the single superhero page. It listens for user clicks on the back button and the app logo and takes the user back to the home page.

Conclusion
This app is a simple and fun way to search for your favorite Marvel superheroes. It uses the Marvel API to load superhero data and localStorage to save user data. The app is easy to use and can be easily customized to fit your needs.

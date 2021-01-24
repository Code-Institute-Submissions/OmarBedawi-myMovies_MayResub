# Tiffany's Films Archive


![screens](https://raw.githubusercontent.com/OmarBedawi/myMovies/master/static/readMe_files/screenshots/tiff_responsive.png?raw=true)



This is the source code of the Tiffany's Films Archive. 

To see it in action just click this [link](http://my-first-heroku-for-movies.herokuapp.com/get_films).


## Goals
### Tiffany's Films Archive goals

The goal of this website is to easily display the collection and facilitate the user to add, edit and delete films from the collection in the home page.

### Target audience is:

* Tiffany: a films collector who is looking for an application to storage and have fast and easy access to her films informations.


### Business goals

* Interactive web-app
* Fully functional web app
* Intuitive design
* Easy to navigate


### Customer goals

* Find easy to access the collection and localize the desired films, typing in the search bar the film title or only one word of it. 
* Find easy to add a new film to the collection and eventually modify its information or delete the title from the collecion .


## Installation

In the head of the project I have installed the links to have access to different libraries. In the picture, the links are wrapped in red.

1. Materialize: a library with templates for buttons, forms, sidenav and so many other components. For this project for example I used it to build the navigation bar, the 
search bar and the buttons.
1. Font Awesome: is an icon library. 
1. Cdnjs is a is an ultra-fast, reliable, globally available content delivery network for open-source libraries.
1. The last link below is showing where the style.css file is located.

This project has been built using jinja template engine. 
Jinja allows us to write an html code and be able to reproduce that code in all the other html page where we want to use it again.
Jinja is very useful for header, navbar and footers because I don't have to code them again.
The jinja parenthesis are wrapped in blue lines in the picture.

![header](https://raw.githubusercontent.com/OmarBedawi/myMovies/master/static/readMe_files/screenshots/1_header.png?raw=true)
  
  
* Scripts and JavaScript files are located at the end of the page to be loaded for last.
  
![scripts](https://raw.githubusercontent.com/OmarBedawi/myMovies/master/static/readMe_files/screenshots/2_scripts.png?raw=true)


## User Stories

I built this website using the Materialize library.
All the componenets I used like the top NavBar, the side Bar, forms, buttons, collapsibles come from that library that is very helpful with the responsivity on every screen size.

The homepage is where the list of films are located, because the user wish to have a direct access to the collection when he open the application.

On the top of the list there is a search bar to locate the desire film among a collection of more than 500 films.
Every film is stored and displayed in a collapsible that showing only the film title, but when you click on the collapsible it expands the area and showing the information that the user needs.
The buttons "delete" and "edit" next to the film title are available only for the users who have added that specific film.
In case of films added by other users the buttons are not displayed.
In the expandable area you can find information as the genre of the film, the year, the ID of the user, a wikipedia link and the username of who has added the film.

foto collezione
foto tiff id


The "add film" page is composed by a form with 5 labels to fill with the information desired by the user: 

* the title
* the genre
* the year
* the Tiffany ID
* a wikipedia link

The user (Tiffany) has numbered every movie and attached a label on it. The numeration is sorted by 
That number is what is called Tiffany ID in the expandable area.

![Tiffany ID](https://raw.githubusercontent.com/OmarBedawi/myMovies/master/static/readMe_files/screenshots/tiff_films3.jpg?raw=true)


The "edit film" page is identical to the "add film" page but you edit informations instead to add it.

![add page](https://raw.githubusercontent.com/OmarBedawi/myMovies/master/static/readMe_files/screenshots/add_film.png?raw=true)
![edit page](https://raw.githubusercontent.com/OmarBedawi/myMovies/master/static/readMe_files/screenshots/edit_film.png?raw=true)



The "register" page allows you to create your username and password.

The "log in" page allows you to access (with your username and password) the functions of the app.

If you are not logged in, you can only view the list of films an open the expandable area in the homepage.
When you are logged in you can add films to the collection and they will be labeled as films added by you.
You can edit or delete only the films added by your username.


The "profile" page is telling you which profile is logged in.

All the films and the relative informations in the homepage are stored in a database called Mongo DB, and thanks to Flask and Python I have been able to import and connect
them all to my Github repository and create the desired functions inside the app.py file.

The CSS file is divided by comments, that I used as title to separate the html pages or the screen size sections. 
This make any future correction or class/id research much easier.



![python file](https://raw.githubusercontent.com/OmarBedawi/myMovies/master/static/readMe_files/screenshots/python_file.png?raw=true)

![css](https://raw.githubusercontent.com/OmarBedawi/myMovies/master/static/readMe_files/screenshots/css.png?raw=true)





### WIREFRAMES


The wireframes information can be found [here](static/readMe_files/wireframes/wireframe.md).




## Technologies Used
### Languages
This project makes use of:
* [HTML] - base language for this project.
* [CSS] - Used for Styling the HTML code
* [JavaScript] - Used to make the web app interactive.
* [Python] - Used to 
* [Mongo DB] -
* [Flask] -
* [Heroku] - 


### Libraries    
* [Materialize](https://materializecss.com/) - Used for responsive navbar, for the menu page and the form.
* [JQuery](https://jquery.com/) - The project uses **JQuery** to simplify DOM manipulation.
* [FontAwseome](https://fontawesome.com/) - Used for all the icons on the site.



### TOOLS

* [Google Chrome] - Used for browser and dev tools
* [Mozilla Firefox] - Used for browser and dev tools
* [Microsoft Edge] - Used for browser and dev tools
* [Google] - **Google** was used for research.
* [Balsamiq Cloud](https://balsamiq.cloud/) - Used for creation of wireframes.
* [Gitpod](https://www.gitpod.io/) - Used as IDE for this project.
* [Git](https://git-scm.com/) - Used for Version Control
* [GitHub](https://github.com/) - Used to host repository and live website.
* [Github Pages](https://pattern-projects.github.io/oireachtas-ifd-project/) - Website hosted on **Github Pages**
* [Am I Responsive](http://ami.responsivedesign.is/) - Used for testing purposes as well as creating the image to display the web pages on different devices.
* [W3 Html validator](https://validator.w3.org/) - Used to test and validate my html code.
* [W3 Css validator](https://jigsaw.w3.org/) - Used to test and validate my css code.
* [JSHint](https://jshint.com/) - Used to validate my Javascript code.
* [Color Scheme Designer](http://colorschemedesigner.com/) - Used to test colour combinations.
* [Free Formatter](https://www.freeformatter.com/) - Used to format my html, css and javascript code.
* [PageSpeed insights](https://developers.google.com/speed/pagespeed/insights/) - Used for testing the loading speed of the site.


![speedtest](https://raw.githubusercontent.com/OmarBedawi/myMovies/master/static/readMe_files/screenshots/speed_test.png?raw=true)
###### A caption of a speed test on PageSpeed insights.

## Testing

Testing information can be found [here](static/readMe_files/testing/testing.md).

Navbar:
1. Go to any html page.
1. Try to reduce the screen size to any size below 991px and verify that a toggle menu appears on the top right angle of the screen.
1. Try to click on the toggle menu and verify that a list with all the pages of the website appears to you.
1. Try to click on every page provided by the toggle menu and verify that the pages are all connected between each other and reachable from any other page.
1. Try to hover the mouse over the Menu, Ourstory and Gallery links in the navbar and verify that their color text change to yellow and back to white when you move the mouse out.
1. Try to hover the mouse over the social media icons in the footer and verify that the icons color change to yellow and back to white when you move the mouse out.
1. Try to click on the social media icons and verify that they are correctly linked.
1. Try to click on the logo and verify that it redirect you to the "index" page.
1. Try to scroll any html page and verify that the navbar is fixed.


Carousel:
1. Go to the "index" page.
1. Click on the right arrow of the carousel and verify that the second image slide to the center of the carousel.
1. Click on the right arrow of the carousel and verify that the left arrow appears.
1. After the first click on the right arrow, click on left arrow to go back to the first picture, and verify that the left arrow disappears.
1. Click on the right arrow until you reach the last picture, and verify that the right arrow disappears.
1. Click on the dots right below the carousel and verify that every dot matches a picture.



Menu:
1. Go to the "menu" page.
1. Click on any button and verify that an image of the relative pizza or dessert will appear on  the page.
1. Click on any button and verify that the text "Show" on the button change in "Hide".

![menu1](https://raw.githubusercontent.com/OmarBedawi/PizzeriaVecchiaMilano/master/assets/images/readMe_files/menu1.png?raw=true)
![menu2](https://raw.githubusercontent.com/OmarBedawi/PizzeriaVecchiaMilano/master/assets/images/readMe_files/menu2.png?raw=true)




Video:
1. Go to the "our story" page.
1. Scroll to the end of the page where the video is placed, try to click on the "play" command and verify that the video is starting.


Gallery:
1. Go to the "gallery" page.
1. Set the size of the screen to at least 992px and verify that every raw has 4 columns of pictures.
1. Set the size of the screen between 576px and 992px and verify that every raw has 3 columns of pictures.
1. Set the size of the screen to less than 576px and verify that every raw has 2 columns of pictures.

![gall1](https://raw.githubusercontent.com/OmarBedawi/PizzeriaVecchiaMilano/master/assets/images/readMe_files/gall1.png?raw=true)
![gall2](https://raw.githubusercontent.com/OmarBedawi/PizzeriaVecchiaMilano/master/assets/images/readMe_files/gall2.png?raw=true)
![gall3](https://raw.githubusercontent.com/OmarBedawi/PizzeriaVecchiaMilano/master/assets/images/readMe_files/gall3.png?raw=true)


Contact form:
1. Go to the "Order on-line" page.
1. Try to submit the form with empty fields and verify that an error message about the required fields appears.
1. Try to submit the form with an invalid email address and verify that a relevant error message appears.
1. Try to submit the form with all inputs valid (and a valid email ) and verify that a confirmation email is sent to the email address provided.
1. Try to submit the form and verify that all the fields are cleared.


![email](https://raw.githubusercontent.com/OmarBedawi/PizzeriaVecchiaMilano/master/assets/images/readMe_files/email.png?raw=true)
###### Verify that the contact form information has been sent to my Gmail account by emailjs.


## Code Validation
* I used the [W3 Html validator](https://validator.w3.org/) service to validate my html code.

* I used the [W3 Css validator](https://jigsaw.w3.org/) service to validate my css code.

* I used the [JSHint](https://jshint.com/) service to validate my javascript code.




# Bugs

The project presents two little bugs that I still need to correct:

1. When the carousel is at last picture, the right arrow suppose to disappear but it doesn't.
1. Can't make the submit button to submit and clear the form at the same time. The two funtions for now, work only alternatively.























## Deployment

This web app was developed in Gitpod and pushed to the remote repository, GitHub. The live page is hosted on GitHub Pages.

### Used commands during deployment:

* git add -A - to add the files to the staging area.
* git commit -m "text message here" - to commit the files.
* git push - to push to origin master branch on to GitHub.
* git status - to see the current status of the files.

### Hosting on GitHub Pages

* Log into GitHub.
* From the list of repositories choose [PizzeriaVecchiaMilano](https://github.com/OmarBedawi/PizzeriaVecchiaMilano).
* Go to settings.
* Scroll down to GitHub Pages section.
* Select as a source master branch.
* The page is now automatically refreshed and the project is deployed.
* To access the project scroll down again to GitHub Pages section and click on the provided link.

For more detailed information regarding deployment to GitHub Pages click [here](https://pages.github.com/).

### How to run this project locally
#### Clone this project from GitHub:

* Go to [PizzeriaVecchiaMilano](https://github.com/OmarBedawi/PizzeriaVecchiaMilano) GitHub repository.
* Click on "Clone or download" green button.
* Copy the URL to the repository.
* Open the terminal in your IDE.
* Choose the working directory where you would like to have the cloned repository.
* Type git clone, and add the URL you copied from Github: git clone https://github.com/OmarBedawi/PizzeriaVecchiaMilano-Web-App.git
* Press Enter and your local clone will be created.

For more information regarding cloning of a repository click here.

### Acknowledgements
Thank you to the following for inspiration, motivation and the direction I needed:

- Seun Owonikoko   (my mentor)
- Code Institute staff

## Disclaimer

This web page was created for educational purposes only.

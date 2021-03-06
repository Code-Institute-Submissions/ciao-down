# Milestone Project 3 - Ciao Down
View live project <a href=“https://ciao-down.herokuapp.com/”>here</a>

![Ciao Down Am I Responsive image](static/readme_images/responsive-image.png)

Ciao Down is a free to use online cookbook app focused on Italian cuisine, that presents the user with recipes that have been shared on the
site. The user is able to create a free account. Doing so give them the ability to add their own recipes to the site, edit those
recipes, and delete those recipes if wanted.

***
## Table of Contents:
* [What does it do and what does it need to fulfill?](#what-does-it-do-and-what-does-it-need-to-fulfill)
* [User Experience](#user-experience)
   * [User Stories](#user-stories)
* [Design](#design)
    * [Research](#research)
    * [The Five Planes of UX](#the-five-planes-of-ux)
        * [Wireframes](#wireframes)
        * [The Colour Scheme](#the-colour-scheme)
        * [Font](#font)
        * [The Logo](#the-logo)
    * [Conclusion](#conclusion)
* [Technologies Used](#technologies-used)
* [Database Structure](#database-structure)
* [Features](#features)
   * [Features Across All Pages](#features-across-all-pages)
   * [Other Features](#other-features)
   * [Future Features](#future-features)
* [Testing](#testing)
* [Deployment](#deployment)
    * [Local Deployment](#local-deployment)
    * [Deployment to Heroku](#deployment-to-heroku)
* [Credits](#credits)
    * [Content](#content)
    * [Code](#code)
    * [Media](#media)
* [Acknowledgements](#acknowledgements)
* [Special Thanks](#special-thanks)
* [Disclaimer](#disclaimer)
***

![Ciao Down Logo](static/images/logo.png)

### Ciao Down Logo

<details>
<summary>Fun Fact?!</summary>
Ciao Down originated from a pun. 'Chow Down', means to eat down and enjoy one's food. This was morphed with the Italian word 'Ciao' to give the site the feel of Italian cuisine.
</details>

***

## **What does it do and what does it need to fulfill?**
This is my third milestone project where I have designed, created and built a fully Mobile Responsive CRUD Web Application for users to
store and share recipes. The project was built  with HTML, CSS, JavaScript, jQuery, Python, Flask, and MongoDB. The Materialize Framework was
used along side these programming languages to help give the site a clear strucutre and ensure the site is as responsive as possible for use
across various screen sizes, including desktop, tablet and mobile.
Users will be able to register, see their profile, log out and log back in again. Registered users will be able to add new recipes, and use
a toggle switch to show if a recipe is Gluten Free or Vegetarian. Registered users will be able to edit and delete their own recipes.<br>

My goal was to create a recipe site where users could easily browse Italian cuisine and access clear and concise recipes. Many of the
recipe websites that I came across during my research required the user to scroll through lots of content before finding their desired
recipe. I felt this kind of design was too busy and could easily overwhelm the user. In order to enhance user experience, it was important
to me that the recipe pages on 'Ciao Down' displayed information (e.g: ingredients, method and dietary requirements) in a simple and
easy-to-digest manner. The target audience for this application is anyone who has an interest or passion for Italian food, not matter what
their age or experience.

***

## **User Experience**

### User Stories:

* Generic User:

    * As a user, I want to be able to navigate through the entire site, comfortably and securely.
    * As a user, I want to be able to easily search for recipes by name or ingredients.
    * As a user, I want to view the contents of recipes on the site.
    * As a user, I want to be able to register/sign-up and create my own account on the site.

* Registered User:

    * As a registered user, I want to be able to easily log in to my account.
    * As a registered user, I want to be able to create and submit my own recipes to the site.
    * As a registered user, I want to be able to see my own recipes in one place.
    * As a registered user, I want to be able to easily edit my own recipes.
    * As a registered user, I want to be able to easily delete my own recipes.
    * As a registered user, I want to be able to add ingredients from a recipe to my shopping list in my profile.
    * As a registered user, I want to be able to easily edit my shopping list.
    * As a registered user, I want to be able to print my own shopping list.
    * As a registered user, I want to be able to easily log out of my account.

* Site admin:

    * As the site admin, I want to be able to do all that is possible for a generic user and registered user.
    * As the site admin, I want to be able to access ALL recipes on the site, having the abilitly to edit any errors found, and delete
    recipes in case of unsuitable content.
    * As the site admin, I want to be able to add new categories to the site as the site expands.
    * As the site admin, I want to be able to edit and remove categories as I see fit for user experience.

[Back to Top](#table-of-contents)

***
## **Design**

### Research

Researching other recipe and food websites, I discovered a trend in the designs for these sites. Basic colours were used, and lots of content filled the pages. I wanted to design a clear and concise website that cared for the users experience.I wanted the user to be notified when taking action ont he site, and keeping the flow of the site going.

Sites I used for inspiration were:

* [Food Network](https://foodnetwork.co.uk/?utm_source=foodnetwork.com&utm_medium=domestic)
* [BBC Good Food](https://www.bbcgoodfood.com/)
* [allrecipes](https://www.allrecipes.com/)
* [epicurious](https://www.epicurious.com/)
* [tasty](https://tasty.co/)

### The Five Planes of UX

#### The Strategy Plane
After researching other recipe websites live on the web, it became apparent that there was a lot of competition in this field. However, there were a few things I noticed that I could improve on. Most sites were very busy when it came to content, and simply accessing an actual recipe felt long winded. I decided that my site needed to be easy to use and display recipes clearly. I wanted each user to have the ability to create their own account, and store their own added recipes in a complete collection, with the simple option to edit and delete them.

#### The Scope Plane
This stage was where I really considered what features would be beneficial to the user. This led me into further thought about the users account, where having a profile page cleary displaying their own recipes was a must. I wanted a user to have the abilitly to create, read, update and delete their recipes, utilising the CRUD functions. I also wanted as user to be able to easily search the entire database using keywords. I wanted to incorporate flash messages that would notify users of any successful or unsuccessful actions.

#### The Structure Plane
The presentation of the site had to be clean. I wanted good margins and to avoid ay content being lost of the screen across the pages. Navbars can get very messy, so I wanted to make use of a side nav that would hold the majority of page links. I wanted all users to easily search for keywords of a recipe, being redirected to a search results page that showcased recipes clearly. Also I wanted the option to search by category, from within the side nav.
I decided to have certain pages not display until a user was registered and logged in, and also the login and regester options not display once a user was signed in. This would make for a more comforting experience and better overall feel.

#### The Skeleton Plane
At this level, I really thought about how a user would navigate around the site. I wanted a clear structure throughout the site. Each page would have a fixed navbar and footer that was consistent and the ease of navigation across the site was enhanced further with back buttons and call to action buttons. The idea of a sidenav would be the main point of call, to keep the site clean and keep the user interacting with the site but not to the point of confusing the user. I still wanted to display some things on the navbar. A user always needed an easy way to return home, so a home icon would serve best. I also wanted users to log in or register first, so links to these pages would be displayed here too. Upon signing in, these buttons would turn to logout, for an easy way to leave the site. All of these options would be discoverable within the sidenav too. I wanted content hinting on the home page to encourage the user to scroll down the page, accessing featured recipes.A back to top button would also appear, aiding ease of use for the user once they had scrolled down, to avoid having to scroll all the way back to the top to find the navigation.
When a user had signed in, I wanted them to be directed to their own profile page. I wanted to make use of an accordion on the users profile page to keep text nicely bundled together in their own compartments. I wanted an easy option to add a recipe, in the form of a button. And once recipes were submitted, for the user to easily edit and delete each recipe, as well as view the recipe in it's entirety.
Considering users may move to a page and then change their minds, I wanted a back button to take the user back to their last page visit. This would be useful when a user searches for recipes and then views recipes, giving them the option to go back to the page of their search results. As well as the user having the abilitly to implement the CRUD functions from their profile page, I wanted to make sure they had more than one option when it came to adding and editing recipes. If a user was viewing a recipe that was their own, and say they came across a typo, or just wanted to delete the recipe completely, then they would have buttons provided to execute these options.

#### The Surface Plane
From the beginning of my research, I had discovered that recipes sites would be very colourful, no matter what, due to the colurful content of recipe images. Because of this I wanted to keep the design simple, and not have overpowering colours that would clutter the site. It was also apparent about the business of recipe sites, so this site had to be designed so that a user could effortlessly navigate the site. Having researched and thought over the design process thoroughly, I created a workspace on [Figma](https://www.figma.com/). I had initially sketched ideas onto paper, so now I could start to bring them to life. I created all the pages I had planned for desktop and mobile screen sizes, clearly showing how the structure of the content would mould together on the different sizes, creating more enhanced wireframes.

Find the links to these wireframes below.

<details>
<summary>Wireframes</summary>

* Home Page
    * [Desktop View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/home-wire.png)
    * [Mobile View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/mob-home-wire.png)
* Recipe Page
    * [Desktop View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/recipe-wire.png)
    * [Mobile View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/mob-recipe-wire.png)
* Profile Page
    * [Desktop View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/profile-wire.png)
    * [Mobile View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/mob-profile-wire.png)
* Add Recipe Page
    * [Desktop View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/add-wire.png)
    * [Mobile View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/mob-add-wire.png)
* Edit Recipe Page
    * [Desktop View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/edit-wire.png)
    * [Mobile View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/mob-edit-wire.png)
* Login Page
    * [Desktop View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/login-wire.png)
    * [Mobile View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/mob-login-wire.png)
* Registration Page
    * [Desktop View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/register-wire.png)
    * [Mobile View](https://github.com/Gregory4321/ciao-down/blob/master/static/readme_images/wireframes/mob-register-wire.png)
</details>

[Back to Top](#table-of-contents)

##### The Colour Scheme

The colour scheme used for this site was to be colourful and eyecatching, but also not overwhelming to the user. In order to keep the theme of my site clear, I decided to base my colour scheme on the Italian flag. I used [Coolors](https://coolors.co/) to start playing with
variations of green and red. It was important to me that the colour scheme didn't make the page feel to busy and cluttered, as the content of the site would be very colourful.

The colours I used are:

![Colour scheme](static/readme_images/colours.png)

The primary colour, Russian Green, was used for the navigation bar, buttons of forms and the back to top button, and some text on the recipe page for clearer contrast. I toned down the green to a slightly more muted shade that wasnt too garish, and easy on the eye and comforting for the user. It also worked well as the content of the page was going to be predominently colourful. Using the colour tool that appears when hovering over a colour set in the style.css page, I made the green a bit more bold for use as the colour of success flash messages, so it stood out clear to the user from the navbar. This colour was the GO Green.

I chose the background colour to be White, so that the colourful content of the page would be easily seen, and gave a clean break between areas of the pages. I was hesitant of using a white background as feedback from my Milestone Project 1 was about having text on a white background. I chose the white as I was wanting to use the Italian flag as my colour scheme, but also a lot of the sites I found when researching for this project used white backgrounds. 

The hamburger and home icons as well as the Log In/Sign Up/Logout text in the navbar looked cleaner as white text.

The red, International Orange Engineering was a bright colour and picked as an accent to contrast well with the white and green, breaking the page up, clearly defining the different sections of the page. Also completing my Italian flag design. It was used as the footer colour, and incorporated with the social icons that turned white on hover and the icon itself red, giving a very clear contrast for user experience. I also used the method of the colour tool mentioned above to get a brighter red to use as the error colour of flash messages, to really indicate the error to the user. This colour was the Imperial Red.

As mentioned above, receiving critcism of text on a white background, I gave the forms the background colour of Cultured. This gave a clear definition of the form itself, making it clear that this was the content, and keeping it user friendly. I discovered this colour using the tool as mentioned before, getting the right shade I wanted.

For text across the site, for the most part I used Black, to make sure all the words were clear and easy to read.

##### Font

I found fonts from researching online cookbook reccomendations, and scouring [Google Fonts](https://fonts.google.com/), using their inbuilt compare tool. I decided to use two fonts throughout my site. I wanted the main and secondary fonts to complement each other well throughout the site.
The font for the body text was 'Source Sans Pro', which was a clean and easy to read font across all areas it was presented. I found this font bold and to the point, and stood out clearly when used as an overlay to images.The second font I used was 'Average'. This was not average as it's name may suggest. It was a Serif font that gave a bold statement when being used for headers and titles, that this was a statement. 
These fonts were included in the site by inserting an _import_ link of the Google Fonts API into the top of my style.css file. Both of the fonts had a fall back of 'Sans-serif', should the site not load the import correctly.

##### The Logo

The logo was created using an online design tool called [Canva](https://www.canva.com/en_gb/). I started by creating a custom canvas to suit my required dimensions, and then set the background to the colour, Russian Green, so it would blend with the nav bar. I played with several combinations of hand written and block fonts until I found a combiation I was happy with. I wanted the two words to be in contrasting fonts. I then played with positioning to make it look more exciting, and then completed it with an underlying Italian flag. 

#### Conclusion

The final pages I ended up with did not vary too much from the wireframes I made during the planning stages. There were some basic design choices I decided whilst constructing the pages that differ slightly from these wireframes. Any changes I made along the way all had teh users experience in mind, focusing on the flow of the entire site.

[Back to Top](#table-of-contents)

***

## **Technologies Used**

### Languages

* [HTML5](https://en.wikipedia.org/wiki/HTML5) - Language used to create the structure of the pages.

* [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - Language used to add styling across all pages.

* [JavaScript](https://en.wikipedia.org/wiki/JavaScript) - Language used to create interactivity across the pages.

* [Python](https://en.wikipedia.org/wiki/Python_(programming_language)) - Language used to create the back-end functionality of the app.

* [Jinja](https://jinja.palletsprojects.com/en/2.11.x/) - this templating language was used with the Flask Framework across the HTML pages. It extended the base.html page across all pages, sharing the header and footer, along with all the meta data and links needed for the page creations, especially the crucial !DOCTYPE html.

### Libraries, Frameworks and Editors

* [Materialize 1.0.0](https://materializecss.com/) - used as the base structure and layout of the site, using its grid system to aid responsiveness across screen sizes. Many components such as the navbar, footer and cards were used. Materialize jQuery was used for initialization of many components such as the sidenav, dropdown and modal

* [Flask](https://flask.palletsprojects.com/en/1.1.x/) - a micro-framework used to help with writing the Python code.

* [MongoDB](https://www.mongodb.com/) - the non-relational database used to store my data on it's cloud servers.

* [Werkzeug](https://werkzeug.palletsprojects.com/en/1.0.x/) - used their WSGI toolkit for utilities to add security to user's passwords.

* [Google Fonts](https://fonts.google.com/) - used to import the 'Source Sans Pro' and 'Average' fonts, that were used across all pages.

* [Font Awesome](https://fontawesome.com/) - used for their free range of icons.

* [PyMongo](https://pypi.org/project/pymongo/) - used as Python's API for MongoDB, to enable data links from the back-end to front-end.

* [Favicon.io](https://favicon.io/) - was used to generate the favicon image.

* [Gitpod](https://www.gitpod.io/) - used as preferred choice of IDE for writing my code.

* [Git](https://git-scm.com/) - used for version control by making use of the Gitpod terminal to add, commit and push to Github.

* [Github](https://github.com) - used to host the project's repository and store the code, and linked to Heroku to push latest changes to the deployed build version.

* [Heroku](https://www.heroku.com/) - used as a hosting platform for deploying my live version of this CRUD application.

* [Unsplash](https://unsplash.com/) - used to find images for use across the site.

* [Pexels](https://www.pexels.com/) - used to find images for use across the site.

* [Pixbay](https://pixabay.com/) - used to find images for use across the site.

* [Google Images](https://google.com) - used to find images for use across the site.

### Tools

* [Google](https://www.google.co.uk/) - used for researching various techniques, styles and information.

* [Google Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) - used for testing and debugging.

* [Figma](https://www.figma.com/) - used for creating the wireframes in the design stage.

* [Coolors](https://coolors.co/) - used to find and compare colours that complimented one another, retrieve names of colours, and showcase
the colours on the README.md file as an image.

* [Canva](https://www.canva.com/) - used to design and create the logo and favicon logo.

* [Picresize](https://picresize.com/) - used to resize and crop images for better implementation, such as 25% or 50% smaller.

* [Am I Responsive](http://ami.responsivedesign.is/) - used for showing the responsiveness of the site across different screen sizes and providing the image at the top of this document.

* [Free Online HTML Formatter](https://www.freeformatter.com/html-formatter.html#ad-output) - used to format the HTML code in a neater and more organised fashion.

* [Free Online CSS Formatter](https://www.freeformatter.com/css-beautifier.html) - used to format the CSS code in a neater and more organised fashion.

* [Free Online JS Formatter](https://www.freeformatter.com/javascript-beautifier.html) - used to format the JavaScript code in a neater and more organised fashion.

[Back to Top](#table-of-contents)

***

## **Database Structure**

For this project I chose to use [MongoDB](https://www.mongodb.com/) to store my data. MongoDB is non-relational database management system and works on document based data. It was the perfect type of database structure for what I wanted to achieve with this project. 
In a database I called 'recipe_cookbook', I created three collections.
* Categories - This collection stored the three categories that the recipes in the database fell into:
    * Starters
    * Mains
    * Desserts
* Recipes - This was the main collection of the database, where the majority of the data would be stored. When a user adds a recipe to the application, adding it to this collection, it stored a multitute of data, form the category, title and description of the recipe, to the details of the cooking times, ingredients list and method, as well as the data it was added and by which user.
* Users - This collection held the details entered by a user when registering to the site. The password and confirm password were encrypted before being stored on to the database, so their entry to the site is secure. This was done using the [Werkzeug](https://werkzeug.palletsprojects.com/en/1.0.x/) security helpers found in it's utilities section. A password can hashed and salted with a string for sufficient secuirty of a users password.

Each document inserted into the database was given its own unique id, stored as an ObjectId. All of the data in each of the documents has been stored as strings. This was more than sufficient for the needs of this site using a database.

***

## **Features**

### Features Across All Pages

All pages consist of a fixed navbar and footer, appropriate flash messages and back to top button. All pages other than the log in and sign up pages also contain a back button the previous URL.

#### Navbar

The nav is consistent across all pages, designed to be responsive to the different screen sizes. It is also fixed so always visible to the user.

* The logo is set to the center of the page, and also at the top of the sidenav. It is a link back to the home page.
* A home icon is displayed also for ease of navigation.
* Log in / Sign up is presented to a user, taking them to the corresponding pages.
* A hamburger icon reveals a sidenav, containing links to home, login, sign up pages, and a categories dropdown of 'All, Starters, Mains and Desserts'. This is the main navigation of the site.
* Once a user is signed in, the login / sign up of the navbar and sidenav menu are replaced with logout.
* In the side nav, a logged in user is also displayed with a profile and add recipe link.

#### Footer

* Users will find clickable social icons linking to the corresponding social media pages.

#### Flash messages

* Flash messages are displayed to the user depending on what action they have undertaken.
* The message will be displayed on the pages where it is obvious for the user to see that they are being notified of their actions
* If it is a successful action, such as adding recipe or logging in, the flash message will be displayed in green.
* If the action is unsuccessful, then an error color of red will be displayed, and/or for deletion of a recipe.

#### Back to Top button

* A back to top button is displayed to the user across all pages when the user scrolls down past 200px.

[Back to Top](#table-of-contents)

***

### Other Features

#### Home Page

The home page offers the user a few features.

* A user is firstly presented with a colourful hero image, an overlapping search bar, and content hinting below.
* A user can use the search bar to search for a recipe by name, or a key word from the recipe, taking them to a search result page.
* Below the hero image is a hoverable grid, displaying featured recipes randomly generated from the database, all clickable taking them to each recipe.

#### Log in

The log in page displayes a slider of images at the top, and a log in form.

* The slider of images contains colourful images to inspire the user.
* Encouraging taglines welcome the user back, and to continue their story.
* If a user tries to submit an incorrect details, they are given an error flash message.
* If this visit is the users first time, they are provided with a link below the form to sign up.

#### Sign Up

Similar to the login page design, just a more complex form and different taglines.

* Taglines of encouragment to start their journey.
* Required fields will stop the user inputting empty or incorrect fields.
* If a user enters a username that already exists on the databse, then they are given an error flash message.
* If this visit is of a returning user, they are provided with a link below the form to log in.

#### Profile

This page is provided for the user to clearly see their submitted recipes. Only registered users can see this page

* Upon signing up or logging in, a user is taken to this page with a welcome flash message.
* If no recipes have been added, a user is offered the option to add a recipe.
* If there are submitted recipes, an accordion is displayed to the user.
* The accordion title provides the recipes title, a link to go to the recipe, and edit/delete buttons.
* The accordion body gives the category name, recipe description, and the date it was added.
* Being made responsive, when the screen size hits a certain breakpoint the edit/delete buttons move into the accordion body, to east with the transition of the changing screen size.

#### Add Recipe

* This page contains a form for the user to complete, adding a recipe to the database.
* All fields are required, and helper text is placed for advice.
* A user also has the ability to use toggle switches if a recipe is vegetarian or gluten free.
* If the user has changed their mind, they can hit the canel button, taking them back to their profile page.
* Once a user submits their recipe, they are directed to that recipes page, and a flash message confirming a successful add.

#### Edit Recipe
* This page is very similar to the add recipe page, same layout and buttons.
* The form os prefilld with the data of the recipe the user has chosen to edit.
* As like when adding a recipe, the user can either cancel this decision to edit, or submit.
* Upon submission they are taken to that recipes page with a success flash message.

#### Recipes Category Pages

* This page has a similar layour to the home page.
* A slider of images presents mouth watering images and the title of the selected category is displayed beneath.
* All images are displayed in a grid format as cards, responsive to the different screen sizes.
* Upon hovering over the cards, the recipe title is displayed.
 Upon clicking the card, the user is directed to that recipe.

#### Recipe Page

* This page displays all the information in a clean and clear format of an added recipe.
* On desktops the recipes are displayed stacked as full width columns, showing some of the recipes details, but then on tablet screen sizes and less they are displayed as grid images that are dispaly the name as an overlay at the bottom of the image.
* If a user is viewing their own recipe, they are given the option to edit or delete the recipe.
* This option is very handy for when a user first submits their recipe, and are taken to this page, they may discover a typo mistake.
* Provide the option for a user to print a recipe.

***

### Future Features

#### Hompe Page

* Once a user is signed in, it would be nice for them to have a floating action button visible from the home screen to add a recipe to their profile. This could be useful if they have directed off from their profile page, and want a quick way to add a recipe, even if the option is in the side nav

#### Profile Page

* I initially had designed for a shopping list hosted on their profile page. This shopping list would be a styled accordion where the body would contain the user's shopping list of ingredients. There were to be buttons where the user could edit or delete each ingredient. This would of demonstrated further the knowledge and use of CRUD operations. From the recipe page, a user would have had the abilitly to add the ingreditns list to their own shopping list, where they could then tailor quanities to their own preferences. The user would have been able to manually add more ingredients to their list too from the accordion in their profile.
* Perhaps an extension of the users profile page, in the form of a my account section, where the user has the abilitly to change their username and password, email account associated with the account, and delete their profile if wanted.
* Having a more personalised feeling with the users profile page. Allowing a user to upload an image as a profile picture. A 

#### Other

* A communtiy page where users can communicate with one another, creating friendships and sharing cooking tips directly.
* A way of following other users if their recipes are the ones you like the most.
* A newsletter that any user can sign up to.
* Implementing emailJS so after a user has created an account, they get an email confirming this action.
* More detailed footer, containing navigation and call to action links.
* Create and allow the admin access to create new categories for the site.

Some of these features I wanted to implement for deployment of this project but unfortuantely time was not on my side and I was not able to complete all of the features that potentially could have been implemtented at this time. There is a lot of potential for this site for further development.

[Back to Top](#table-of-contents)

***

## Testing

Testing can be found via this [link](https://github.com/Gregory4321/ciao-down/blob/master/testing.md)

***

## **Deployment**

This multi-page website was developed in Gitpod and pushed to the remote repository on Github. I have deployed this project to Heroku 

The live site of this project can be viewed <a href=“https://ciao-down.herokuapp.com/”>here</a>

The repository of this project can be viewed on Github <a href=“https://github.com/Gregory4321/ciao-down”>here</a>

***

### Local Deployment

To run your own version of this project, it can be cloned or downloaded from Github

To clone this project:

1. At the top the repository, click the code button at the top of the screen.
2. Click the clipboard icon to copy the URL.
3. Open a new terminal window in the IDE you have chosen, and make sure the current working directory is the location where you want your cloned directory.
4. In the command line, paste the copied link mentioned above after 'git clone', to create your own local repository
```
git clone https://github.com/Gregory4321/ciao-down.git
```
5. Using [MongoDB](https://www.mongodb.com/), create a database that you will use for this project.
6. In the terminal window, install the required dependencies needed to successfully run the app.
```
pip3 install -r requirements.txt
```
7. At the root level of your application, create a file called env.py to contain your environmental variables. They are as follows:
```
import os

os.environ.setdefault("IP", "0.0.0.0")
os.environ.setdefault("PORT", "5000")
os.environ.setdefault("SECRET_KEY", "SECRET_KEY")
os.environ.setdefault("MONGO_URI", "MONGO_URI")
os.environ.setdefault("MONGO_DBNAME", "MONGO_DBNAME")
```

You will need to update the **MONGO_URI** and **MONGO_DBNAME** variables to those provided by MongoDB. Make sure you replace the necessary fields of 'username', 'password', 'cluste_name' and 'database_name' in the URI. You will also need to update the **SECRET_KEY**. You could use this site to generate this and keep it unique - [RandomKeygen](https://randomkeygen.com/)

8. If you plan for this project to be public, make sure that your env.py file is added to the .gitignore file. This will keep your database information safe from others, no one will be able to see it.
9. You can now run the application locally, by typing in the terminal window: 
```
python3 app.py
```

***

### Deployment to Heroku

To deploy this project to Heroku:

1. Sign in to your Heroku account and create a new app. Make sure you set the region closet to you.
2. Once created, navigate to the 'Settings' tab, and click the 'Reveal Config Vars' button.
3. Enter the key value pairs that you entered in your env.py file:
```
IP = 0.0.0.0
PORT = 5000
SECRET_KEY = SECRET_KEY
MONGO_URI = MONGO_URI
MONGO_DBNAME = MONGO_DBNAME
```
4. In your local repository, create the requirements.txt if not already created:
```
pip3 freeze --local > requirements.txt
```
5. Then create a Procfile, including the content in the creation:
```
echo web: python app.py > Procfile
```

The Procfile might create a blank line at the bootom of the file. Make sure to remove this to avoid any problems when running the app on Heroku.
6. Back within the Heroku app, navigate to the 'Deploy' tab, and under the 'Deployment method' section, select 'Connect to Github'.
7. Make sure your Github profile is displayed, and add your repository name and click 'Search'.
8. Once Heroku finds your repo, click the 'Connect' button to connect to this app.
9. Below this, click the 'Enable Automatic Deploys' button, and then below this, makig sure your branch is correct, click 'Deploy Branch'.
10. Heroku will now start building the app, receiving the code from Github.
11. When the build is complete, you should see that 'Your app was successfully deployed'. Click the 'View' button to to launch the app.
The deployed site will now automatically update whenever changes are pushed to the Github repository.

[Back to Top](#table-of-contents)

***

## **Credits**

#### Content

All content on the website was written by me, the developer, with inspiration taken from other food and recipe sites.

#### Code

* The code throughout the project used [Materialize](https://materializecss.com/getting-started.html) as its base to create a
responsive site, utilising the Materialize grid system.

* Inspiration on how to place and style the hero images, was taken from my previous Milestone 1 Project.

* Tutor support provided me with pointers and curve balls that helped me with certain functions in my Python code. They helped me to understand what needed to be done to achieve what I was trying to achieve, and directed me to documentation sites to find the answers I needed.

* The code for the EmailJS was a mixture of using the documentation found on the website, following the CI tutorial videos on EmailJS, and my own
knowledge and practice put into place.

* The back-to-top button code was taken from my Milestone 2 Project, which was originally found on 'Codepen', and then tailored to my sites needs.

* The code that ensured the dropdown section of the forms  was a required field was taken from the Code Institute lesson 'Materialize Form Validation'.

* The code that made sure that the passwords matched when a user was creating an account was found on 'Codepen'.

* The code to enable the back button across pages was found using W3Schools.

* All other code was written by me, the developer.

#### Media

The images used on the website were taken from various different image libraries:

* [Unsplash](https://unsplash.com/)

* [Pexels](https://www.pexels.com/)

* [Pixbay](https://pixabay.com/)

* [Google Images](https://google.com)

These images were then resized to suit the wants of me, the developer, using these two sites:

* [Canva](https://www.canva.com/)

* [Picresize](https://picresize.com/)

The logo image was created and exported to my computer using the site [Canva](https://www.canva.com/)

The favicon image was created and exported to my computer using the site [Canva](https://www.canva.com/), and then uploaded to the site [Favicon.io]
(https://favicon.io/) to be generated as an ico image, to then be exported back to my computer and then added to my root directory on gitpod.

***

## **Acknowledgements**

#### Pages used for inspiration

* [BBC Good Food](https://www.bbcgoodfood.com/)

* [Jamie Oliver](https://www.jamieoliver.com/)

* [epicurious](https://www.epicurious.com/)

#### Pages used for information

* [Stack overflow](https://stackoverflow.com/)

* [W3schools](https://www.w3schools.com/)

* [CSS-Tricks](https://css-tricks.com/)

* [Code Institute](https://codeinstitute.net/)

* [Code Institute Sample README](https://github.com/Code-Institute-Solutions/SampleREADME)

* [Slack](https://slack.com/intl/en-gb/)

* [YouTube](https://www.youtube.com/)

* [Code Pen](https://codepen.io/)

* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

* [Tripadvisor](https://www.tripadvisor.co.uk/)

* [Werkzeug](https://werkzeug.palletsprojects.com/en/1.0.x/)

* [MDN web docs](https://developer.mozilla.org/en-US/)

* [Codepen](https://codepen.io/)

* [Python](https://www.python.org/)

* [MongoDB](https://www.mongodb.com/)

* [Jinja](https://flask.palletsprojects.com/en/1.1.x/)

#### Special thanks

* Seun Owonikoko @seun_mentor, my mentor, for the support and guidance she gave thoughout the build of this project.

* All of the tutors at Code Institute that helped me from tutor support, your advice and guidance helped me more than I think you know. 

* Code Institute for the informative lessons and teachings they provided.

* My family and friends for their feedback during the build and testing stages.

* Everyone from the Slack community for their response to questions and advice towards a solution.

[Back to Top](#table-of-contents)

## **Disclaimer**

This project was created for educational use only. It has been part of studying at the Code Institute as part of their Full Stack Web Developer Course.

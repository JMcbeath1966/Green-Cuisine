# [Green Cusinse](https://green-cuisine.herokuapp.com/)

- Mockup Design ![Here](https://github.com/JMcbeath1966/Green-Cuisine/blob/main/static/images/mock-up-design/all-devices-white.png)

Looking for something delicious for vegetarians or vegans? You've come to the right place! [Green Cusine](https://green-cuisine.herokuapp.com/) 
Vegetarian and Vegan recipes for 'Green' lovers! You'll find a variety of tasty dishes from other veggie fanatics, be able to create your own profile, add your own recipes and update these recipes if you need to!

---

## Table of Contents
1. [**UX**](#ux)
    - [**User Stories**](#user-stories)
    - [**Design**](#design)
        - [**Framework**](#framework)
        - [**Color Scheme**](#color-scheme)
        - [**Icons**](#icons)
        - [**Typography**](#typography)
    - [**Wireframes**](#wireframes)

2. [**Features**](#features)
    - [**Existing Features**](#existing-features)
    - [**Features Left to Implement**](#features-left-to-implement)

3. [**Technologies Used**](#technologies-used)
    - [**Front-End Technologies**](#front-end-technologies)
    - [**Back-End Technologies**](#back-end-technologies)

4. [**Testing**](#testing)
    - [**Validators**](#validators)
    - [**Compatibility**](#compatibility)
    - [**Known Issues**](#known-issues)

5. [**Deployment**](#deployment)
    - [**Local Deployment**](#local-deployment)
    - [**Remote Deployment**](#remote-deployment)

6. [**Credits**](#credits)
    - [**Content**](#content)
    - [**Media**](#media)
    - [**Code**](#code)
    - [**Acknowledgements**](#acknowledgements)

---

## UX

This project is part of my [Code Institute](https://codeinstitute.net/) Full Stack Software Development course (Level 5 Diploma in Web Application Development), specifically the **Data Centric Development** module. The objective for this milestone project is to "*Create a web application that allows users to store and easily access cooking recipes*", using the **CRUD** operations of **C**reate, **R**ead, **U**pdate, and **D**elete for their recipes.

Although I'm not a vegetarian or vegan, I try to eat vegetable dishes whenever possible. I researched with friends and family who are either vegan or vegetarian to understand what their thoughts and needs for a website were.
Whilst not an exclusive list there key requirements were:
- Simple design with minimal images
- Ability to add dishes with clear indication as to whether the recipe is vegan or vegetarian
- Simple, quick register and login/logout process
- Key elements of the recipe to be clearly marked and kept to 'need to know' only, e.g. images not a high priority

I recognise that this is not extensive market research but it the discussions have, in conjunction with reviewing similar websites myself, has give me confidence that the key areas of their requirements are universal themes.


### User Stories

"**_As a user, I would like to_** _____________________________"

:white_check_mark: *denotes items that have been successfully implemented*

- :white_check_mark: *view the site* from **any device** *(mobile, tablet, desktop)*.
- :white_check_mark: *view all recipes* as a **Guest**.
- :white_check_mark: *search all recipes* as a **Guest**.
- :white_check_mark: *filter recipes* by **recipe type - vegan/vegetarian**.
- :white_check_mark: *sort/order recipes* by **recipe title, description, ingredients, cooking time, and cuisine**.
- :white_check_mark: *create* my **own profile**.
- :white_check_mark: *add* my **own recipes**.
- :white_check_mark: *edit* my **own recipes**.
- :white_check_mark: *delete* my **own recipes**.
- :white_check_mark: be able to **log out**.
- :white_check_mark: be able to **change my password**.

### Design

On the basis of user requirements being minimal on images and superflous information, I've created a clean, simple design with some icons and use of the color green as its appropriate to the sites theme of vegetables.

#### Framework

- [Materialize 1.0.0](https://materializecss.com/)
    - I really like the modern and clean layout of Materialize as a framework, with its simple-to-understand documentation.
- [jQuery 3.4.0](https://code.jquery.com/jquery/)
    - In an effort to keep the JavaScript minimal, I have decided to use jQuery as foundation to my scripts framework.
- [Flask 1.0.2](http://flask.pocoo.org/)
    - Flask is a microframework that I've used to render the back-end Python with the front-end Materialize.

#### Color Scheme

In keeping with the overall vegetable theme, I have opted for a green theme. These standard [Materialize Colors](https://materializecss.com/color.html) work quite well for my project.

- #558b2f light-green darken-3 (Primary)
- #ccff90 light-green accent-1 (Secondary)
- #76ff03 light-green accent-3 (Spare Color)
- #ff1744 red accent-3 (Buttons-Prominent)
- #00bcd4 cyan (Buttons-Updates)

#### Icons

- [Materialize Icons](https://materializecss.com/icons.html)
    - I've retained only a select few of the standard Materialize Icons, as these are built-in to some of their components. 
- [Font Awesome 5.8.1](https://fontawesome.com/)
    - I prefer the look of Font Awesome's icons, and they have more to suit my specific needs for this project. I have used a kit to use the newest icons available (version 6.4.0)

#### Typography

- I have incorporated [Google Fonts](https://fonts.google.com/) throughout the entire application. The font I have selected for all recipe names is called [Roboto](https://fonts.google.com/specimen/Roboto), because it fits perfectly as a clean, modern font.


### Wireframes

For my wireframes, I have used [Balsamiq Wireframes](https://balsamiq.com/) for a the reason that the simplicity and ease of use. I actually found Balsamiq much easier and quicker to use than Adobe XD.

 - All of my wireframes for this project can be found [here](https://github.com/JMcbeath1966/Green-Cuisine/blob/main/static/images/wireframes/green-cuisine-wireframe.pdf).


##### back to [top](#table-of-contents)

---

### Existing Features

**Register Account**
- Anybody can register for free and create their own unique account. I have built-in authentication and authorization to check certain criteria is met before an account is validated. All passwords are hashed for security purposes!

**Log In to Account**
- For existing users, I have more authentication and authorization incorporated to check that the hashed passwords and username match the database.

**Change Password**
- Users can update their passwords from their profile page, after first validating their existing password.

**Log Out of Account**
- Users can easily log out of their account with the click of a button.

**Delete Account**
- Users can delete their entire account

**View All Recipes**
- On the *All Recipes* page, all recipes are initially displayed in an alphabetical order, using an accordion dropdown.

**Search Recipes**
- If a user would like to search for something specific, whether it's a particular recipe, then the search button is perfect!

**Add a Recipe**
- [**C**RUD] Create or 'add' a new recipe. Defensive programming in place means users must adhere to minimal requirements when adding a new recipe. 

**View a Recipe**
- [C**R**UD] Read or 'review' recipes, either from the main page, or the user profile.

**Update a Recipe**
- [CR**U**D] Update or 'edit' their own user recipes on this page.

**Delete a Recipe**
- [CRU**D**] Delete or 'remove' a user's own recipes.

**Remove a Recipe from Favorites**
- If a user no longer likes a recipe, or simply wants to remove it from their favorites, a single click can remove a recipe.

**Admin Superuser**
- My ***'Admin'*** profile has several extra features, which currently include:
    - Edit / Delete any recipe from the database.

### Features Left to Implement

**Admin Superuser**

-  I would like a  ***'Admin'*** profile has several extra features, which currently include:
    - Edit / Delete any recipe from the database.

##### back to [top](#table-of-contents)

---

## Technologies Used

- [VS Code](https://code.visualstudio.com/) - Used as my primary IDE for coding.
- [GitHub](https://github.com/) - Used as remote storage of my code online.
- [Gitpod] (https://www.gitpod.io/) - Developer platform for on-demand code.

### Front-End Technologies

- [HTML](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) - Used as the base for markup text.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3) - Used as the base for cascading styles.
- [jQuery 3.4.0](https://code.jquery.com/jquery/) - Used as the primary JavaScript functionality.
- [Materialize 1.0.0](https://materializecss.com/) - Used as the overall design framework.


### Back-End Technologies

- **Flask**. 
    - [Flask 2.3.2](http://flask.pocoo.org/) - Used as a microframework.
    - [Jinja 2.10](http://jinja.pocoo.org/docs/2.10/) - Used for templating with Flask.
    - [Werkzeug 0.16](https://werkzeug.palletsprojects.com/en/0.16.x/) - Used for password hashing, authentication, and authorization.
- **Heroku**
    - [Heroku](https://www.heroku.com) - Used for app hosting.
- **Python**    
    - [Python 3.6.7](https://www.python.org/) - Used as the back-end programming language.
    - [MongoDB Atlas](https://www.mongodb.com/) - Used to store my database in the 'cloud'.
    - [PyMongo 3.8.0](https://api.mongodb.com/python/current/) - Used as the Python API for MongoDB.
    - [Itsdangerous 2.1.2](https://itsdangerous.palletsprojects.com/) - The itsdangerous library provides various ways to work with JSON Web Signatures (JWS), which are a way of signing a data structure in a way that cannot be easily tampered with.
    - [click==8.1.3](https://click.palletsprojects.com/) - Click is a Python package for creating command-line interfaces (CLIs).
    - [blinker==1.6.2](https://pypi.org/project/blinker/) - Blinker is a Python module that provides a fast dispatching system that allows code to subscribe to be notified when certain events occur
    - [dnspython==2.3.0](https://www.dnspython.org/) - The itsdangerous library provides various ways to work with JSON Web Signatures (JWS), which are a way of signing a data structure in a way that cannot be easily tampered with.

##### back to [top](#table-of-contents)

---

## Testing

**Creating an Account**

I've created my own personal account. In addition to these two primary accounts, I've tested with about 15 fake accounts in order to confirm authentication and validation worked as expected.

**Add | Edit | Delete a Recipe**

In addition to a few choosen recipes, I've created about 10 test recipes, mostly *Test*, *Test123* etc in order to prepare for pagination building. These recipes were created using my actual account, the admin account, and several test accounts.

For several recipes, I've edited minor things like the recipe description, adding additional ingredients or directions, to test the functionality of updating a recipe to the database.


**Pagination**

When implementing pagination, I had a lot of manual tests to undergo, in order to make pagination work for multiple scenarios. I needed to test that all aspects of pagination worked with and without the option for searching the database. These included:

**Sort, Order, and Limit**

With the Search function, the user has the option to sort, order, and limit the number of results. This required some manual testing as well.

- **Sorting + Ordering**
    - Sorting by *Author* or *Recipe Name* works accordingly:
        - ascending (alphabetical A-Z)
        - descending (alphabetical Z-A)
### Validators

**HTML**
- [W3C HTML Validator](https://validator.w3.org) - I removed all Jinja coding from the html files and tested on that basis. The errors seen from the W3C checker all relate to erros caused by removing the Jinja code, e.g. expecting to see a doctype first, the head element is missing - all related to html elements that do not appear in any of the files apart from the base.html. Otherwise there were no errors in the html. Results [here](https://github.com/JMcbeath1966/Green-Cuisine/tree/main/static/images/html-css-test-results)

**CSS**
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - 
- CSS code passed first time with no errors.Results [here](https://github.com/JMcbeath1966/Green-Cuisine/blob/main/static/images/html-css-test-results/css-stylesheet-testpass.png)

**JavaScript**
- [JShint](https://jshint.com/)
- JShint code passed first time, with 2 warnings.Results [here](https://github.com/JMcbeath1966/Green-Cuisine/blob/main/static/images/html-css-test-results/jshint-test.png)
   

**Python**
- [PEP8 Online](http://pep8online.com/)
    - pycodestyle was used in the CLI to test compliance to pep8 and the file test 'threw' no errors

### Compatibility

To ensure a broad range of users can successfully use this site, I tested it across the 6 major browsers in both desktop and mobile configuration.

- Chrome *v.74*
- Edge *v.18*
- Firefox *v.67*
- Safari *v.12*
- Internet Explorer *v.11*

For testing compatibility, I created a testing matrix to test across multiple devices and browsers. The test matrix can be found [here](app/testing/test-matrix.png). A brief overview:


### Known Issues

None


### Local Deployment

Please note - in order to run this project locally on your own system, you will need the following installed:
- [Python3](https://www.python.org/downloads) to run the application.
- [PIP](https://pip.pypa.io/en/stable/installing) to install all app requirements.
- Any IDE such as [Microsoft Visual Studio Code](https://code.visualstudio.com).
- [GIT](https://www.atlassian.com/git/tutorials/install-git) for cloning and version control.
- [MongoDB](https://www.mongodb.com) to develop your own database either locally or remotely on MongoDB Atlas.

Next, there's a series of steps to take in order to proceed with local deployment:

- Clone this GitHub repository by either clicking the green *Clone or download* button and downloading the project as a zip-file (remember to unzip it first), or by entering the following into the Git CLI terminal:
    - `git clone https://github.com/TravelTimN/ci-milestone04-dcd.git`.
- Navigate to the correct file location after unpacking the files.
    - `cd <path to folder>`
- Create a `.env` file with your credentials. An example can be found [here](.env_sample). Be sure to include your *MONGO_URI* and *SECRET_KEY* values.
- Create a `.flaskenv` file and add the following entries:
    - `FLASK_APP=run.py`
    - `FLASK_ENV=development`
- Install all requirements from the [requirements.txt](requirements.txt) file using this command:
    - `sudo -H pip3 -r requirements.txt`
- Sign up for a free account on [MongoDB](https://www.mongodb.com) and create a new Database called **Green-Cusine**. The *Collections* in that database should be as follows:

**CATEGORIES**
```
_id: <ObjectId>
recipe_type: <array>
```

**RECIPES**
```
_id: <ObjectId>
recipe_title: <string>
recipe_description: <string>
recipe_ingredients: <string>
cooking_instructions: <string>
cooking_time: <string>
recipe_type: <string>
```

**USER**
```
username:  <string>
```


- You should now be able to launch your app using the following command in your terminal:
    - `flask run`
- The app should now be running on *localhost* on an address similar to `http://127.0.0.1:5000`. Simply copy/paste this into the browser of your choice!

### Remote Deployment

This site is currently deployed on [Heroku](https://www.heroku.com/) using the **main** branch on GitHub. To implement this project on Heroku, the following steps were taken:

1. Create a **requirements.txt** file so Heroku can install the required dependencies to run the app.
    - `sudo pip3 freeze --local > requirements.txt`
    - My file can be found [here](requirements.txt).
2. Create a **Procfile** to tell Heroku what type of application is being deployed, and how to run it.
    - `echo web: python run.py > Procfile`
    - My file can be found [here](Procfile).
3. Sign up for a free Heroku account, create your project app, and click the **Deploy** tab, at which point you can *Connect GitHub* as the Deployment Method, and select *Enable Automatic Deployment*.
4. In the Heroku **Settings** tab, click on the *Reveal Config Vars* button to configure environmental variables as follows:
    - **IP** : `0.0.0.0`
    - **PORT** : `8080`
    - **MONGO_URI** : `<link to your Mongo DB>`
    - **SECRET_KEY** : `<your own secret key>`
    - **MY_ADDRESS** : `<your own email address>`
    - **SEND_TO** : `<recipient email address>`
    - **PASSWORD** : `<you own email password>`
5. Your app should be successfully deployed to Heroku at this point. :tada:

**NOTE** : You might receive errors sending emails if you have your Google Account setup with **2-Factor Authentication**, **Less Secure Apps** disabled, or **DisplayUnlockCaptcha** disabled.

**Plausible Fix** *(which has worked for me)*
- Turn Off [2-Factor Authentication](https://myaccount.google.com/signinoptions/two-step-verification/enroll-welcome)
- Turn On [Less Secure Apps](https://myaccount.google.com/lesssecureapps)
- Turn On [DisplayUnlockCaptcha](https://accounts.google.com/DisplayUnlockCaptcha)

I would recommend to create a secondary Google account for this purpose, instead of using your actual account (keep your actual account secure!). This is purely used for sending emails as a backup when new recipes are created or updated, in case the database somehow accidentally has an item deleted.


##### back to [top](#table-of-contents)

## Code
Code Insitute tutorials for the Milestone 3 project. 
Chat GPT was used to support learning and to test code, but no code was direclty copied
### Acknowledgements
 Thanks for the support of the Code Institute tutor support, my indvidual tutor (Rachel Furlong) and my mentor (Jubrill Akolade)

##### back to [top](#table-of-contents)
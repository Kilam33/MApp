#Instructions
Download code or fork repo
Navigate to folder containing manage.py on console
Run command python manage.py runserver to start the environment
Paste the host address on browser.



# MusicApp
Then run the following to install the required packages:

pip install django
pip install pillow
The pillow package is a Python image handling library which we’ll use to save cover images for the music in the database.

# Django ORM
Object-Relational Mapping (ORM) is a method that helps you question and control statistics from a database, the use of an object-orientated paradigm.

When speaking about ORM, we are referring to a library that implements the Object-Relational Mapping technique, the phrase “an ORM”.

An ORM library is an everyday library written in your language of choice that encapsulates the code required to control the data so that you do not use raw SQL queries anymore. You engage with an object immediately within the same language you are utilizing.

MVT Architecture
MVT (Model View Template) is a software program layout sample that’s a group of 3 elements: Model, View, and Template. The Model allows dealing with the database. It is a data access layer that handles the information in the database.

The Template is a presentation layer that handles all the User Interface parts. The View executes the logic and interact with the model to carry data and renders the template.

Although Django follows the MVC pattern, it still continues its conventions, so control is taken care of through the framework itself.

There isn’t any separate controller and the entire framework is primarily based on Model, View, and Template. That’s why it’s largely known as the MVT framework.

In the MVC architecture, a user sends a request for a resource to Django, Django works as a controller and checks for the available resource in the URL.

If a URL is mapped, a view is called that interact with the model and template, it renders a template.

Django responds to the user and sends a template as a response.

The main distinction among the 2 styles is that Django itself looks after the Controller part (Software Code that controls the interactions among the Model and View), leaving us with the template. The template is an HTML record combined with Django Template Language (DTL).

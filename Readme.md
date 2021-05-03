># Django Web Framework Tutorials
* Started by Adrian Holovaty and Simon Willison in the year 2003
* It released July 2005
* Django is now an open source web framework with contributors across the world.
* It enables to build rich web applications with minimal time and effort.
* To develop web based applications using django framework, we need some language. Python is best language for developing web applications by using Django. since it is written in Python.
># Advantages of Django
* **Loosely Coupled:** Django makes each element independent of the others.
* **Less Coding:** Less code, so application development is very easy and Quick
* **Don't Repeat Yourself (DRY):** Allows developer to reuse modules of one project in another project.
* **Object-Relational Mapping (ORM) Support:** Django provides a bridge between the data model and the database engine, and supports a large set of database systems including MySQL, Oracle, Postgre sql, etc. Django also supports NoSQL databases like MongoDB and google app engine.
* **Multilingual Support:** Django supports multilingual websites through its built-in internationalization system. So you can develop your website, which would support multiple languages.
* **Framework Support:** Django has built-in support for Ajax(Asynchronous JavaScript And XML), Caching and various other frameworks.
* **Note:** AJAX is a new technique for creating better, faster, and more interactive web applications with the help of XML, HTML, CSS, and Java Script.
* **Administration GUI:** Django provides a nice ready-to-use user interface for administrative activities. Like most modern frameworks, Django supports the MVC pattern(Model-View-Controller), and Model-View-Template (MVT) pattern.
># Architecture of the Django(Model View Template):
* Whenever end user sends the URL request, which is received by the URL Dispatcher.
* URL dispatcher is a program which is used to compare requested URL with list of urls present urls.py(it is created by django automatically at the time of creating project), 
if there is matching url, the function which is configured with the url is executed. Otherwise result will be runtime error.
* Every url pattern of urls.py file should be registered with a view function/view classs .
*  A view is a python function or class which receives client request and process that request and sends response to the client request.
* All views functions (or) view classes ,should be defined in the views.py file
*  The views.py file will be automatically created at the time of creating an app’s
* At the time of processing the client request ,we can communicate With database through the model
* A model is a python class which represents tables in database.
* In order to store the data into db or retrieve data from db, then we need to create/write a model query.
* The model queries are similar to the SQL queries and we can write model queries by using API’s. the model queries are database independent queries.
* All model classes are created in models.py file.
* The models.py class will be automatically created at the time of creating an app’s.
* After processing the client request by the view, view will transfer the result to the template (template is text file which contains html + python code). Template will be
rendered into html which is forwarded to the browser for presentation.

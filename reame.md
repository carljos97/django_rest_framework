DJANGO REST API Project

In this project we create an API using Django REST Framework. We develop student resources to make available and learn to work with key CRUD actions. We carry out this process for courses and for enrollments, linking the two models.

We create the models, serialize them, prepare our viewsets and register URLs to serve our requests. We also set up more details about students and courses so that we can see all enrollments for a person and all enrollments in a given course.

Finally, we include basic authentication. Even running the project locally, we don't want any application to have access to the API.

Main points for practical work:

Whenever you need to create a path in your API to access a model's data, you need to create the viewset (in views.py) and a serializer (in serializer.py). [Inside the project]. In addition, it is necessary to create a url for the new serializer, in urls.py, inside the project setup file.

Cases were also implemented for when we want to request data and compare them with data from other models. Create the desired list in the serializer, and then create the view.
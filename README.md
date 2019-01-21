# Food Delivery App called Foodtasker


#### A user can sign in as a new restaurant.
#### A user can create meals and submit order status.
#### A user can communicate with drivers when order status is cooking, done, ready, out for delivery, and delivered.
#### A user can view report and see revenue for the week and the most popular meal.



### Setting up


Fork the project to your personal account and get a local copy on your machine.
Change into the project folder.


```sh
$ python manage.py runserver
```

Make sure to create migrations, create tables in db, and create a superuser to have an admin dashboard.

```sh
$ python manage.py makemigrations (creates migration files based on your models)
$ python manage.py migrate (creates the tables in your db based on the migration files)
$ python manage.py createsuperuser (creates a superuser for your application in the db)
$ python manage.py runserver (run server)
```

Now you should be able to view your app at http://127.0.0.1:8000 and to view your admin dashboard use 
http://127.0.0.1:8000/admin/.

# replica
its an applicationthat allows me to post images for viewers and allows them to view them.

## Author

* **HAMIDA MSTAFA**

## Features


As a user of the application you will be able to:


1. View different photos that interest you.
2. Click on a single photo to expand it and also view the details of the photo. The photo details will appear      on a modal within the same route as the main page.
3. Search for different categories of photos. (ie. Travel, Food)
4. Click on share icon to share the image with any of your social account or alternatively Copy a link to the       photo and share with your friends.
5. View photos based on the location they were taken or category.


### Installing

1. Clone this repo: git clone https://github.com/hamida-mstafa/replica.git
2. The repo comes in a zipped or compressed format. Extract to your preferred location and open it.
3. open your terminal and navigate to replica then create a virtual environment.  
4. To run the app, you'll have to run the following commands in your terminal
       pip install -r requirements.txt
5. On your terminal,Create database replica using the command below.
       CREATE DATABASE replica;
6. Migrate the database using the command below
       python3.6 manage.py migrate
7. Then serve the app, so that the app will be available on localhost:8000, to do this run the command below
       python manage.py runserver
8. Use the navigation bar/navbar/navigation pane/menu to navigate and explore the app.

## Running the tests

Use the command given below to run automated tests.


        python manage.py test replica




## Built With

* [Django](https://www.djangoproject.com/) - web framework used
* Javascript - For DOM(Document Object Manipulation) scripts
* HTML - For building Mark Up pages/User Interface
* CSS - For Styling User Interface


## License

This project is licensed under the MIT License

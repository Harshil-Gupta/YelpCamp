## YelpCamp

YelpCamp is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account. This project was part of [Colt Steele's Web Dev course on udemy.](https://www.udemy.com/share/101W9CBksfd1lRRng=/)

![YelpCamp1](https://user-images.githubusercontent.com/53968071/131266459-190a9125-a9af-412b-83f7-fa3e9bd5a3c5.png)

![YelpCamp2](https://user-images.githubusercontent.com/53968071/131266468-25dfbe3e-e696-47df-b344-62cc9e5436b9.png)

![YelpCamp3](https://user-images.githubusercontent.com/53968071/131266473-fbce2d57-b782-4237-80e0-5133343c6422.png)

![YelpCamp4](https://user-images.githubusercontent.com/53968071/131266477-e11b9498-d518-45b4-88d0-148480de78bc.png)


This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.  

## Features
* Users can create, edit, and remove campgrounds
* Users can review campgrounds once, and edit or remove their review
* User profiles include more information on the user (full name, email, phone, join date), their campgrounds, and the option to edit their profile or delete their account
* Search campground by name or location
* Sort campgrounds by highest rating, most reviewed, lowest price, or highest price

## Run it locally
1. Install [mongodb](https://www.mongodb.com/)
2. Create a cloudinary account to get an API key and secret code

```
git clone https://github.com/Harshil-Gupta/YelpCamp.git
cd yelpcamp
npm install
```

Create a .env file (or just export manually in the terminal) in the root of the project and add the following:  

```
DATABASEURL='<url>'
API_KEY=''<key>
API_SECRET='<secret>'
```

Run ```mongod``` in another terminal and ```node app.js``` in the terminal with the project.  

Then go to [localhost:3000](http://localhost:3000/).

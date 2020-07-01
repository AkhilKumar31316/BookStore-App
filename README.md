# BookStore-App
"Steps : The project consists of backend and frontend. First we will get the backend up and running and then front end Backend".
Backend
-------
As the files are too large to upload on to the github, i have uploaded on to Google drive for you to access. Please download from the below  link
https://drive.google.com/file/d/1PY8dsfbph5A-nnL-deYnqYUWt5KJ1Kkj/view?usp=sharing

1.) Unzip springworkspace.zip and please copy to the C drive

2.) go to c:\springworkspace\bookstore-master path in the command prompt.

3.) run the command "mvn clean install".

4.) You will see after sometime Build Success.

5.) run the command "mvn spring-boot:run". This will start up the server.

# bookstore

# Get all books : GET : http://localhost:8081/api/v1/books

# Get book based on Id : GET : http://localhost:8081/api/v1/books/1

# Post a book : POST : http://localhost:8081/api/v1/books
{
    "category": "cooking",
    "title": "Awesome Chowmein",
    "language": "en",
    "year": "2005",
    "price": 25.0,
    "authors": [
        {
            "name": "Sam T. Bruce"
        },
        {
            "name": "Giada De Laurentiis"
        }
    ]
}

# update a book : PUT : http://localhost:8081/api/v1/books/4
{
    "category": "cooking",
    "title": "Awesome Chowmein",
    "language": "en",
    "year": "2005",
    "price": 50.0,
    "authors": [
        {
            "name": "Sam T. Bruce"
        },
        {
            "name": "Giada De Laurentiis"
        }
    ]
}

# Delete a book : DELETE :http://localhost:8081/api/v1/books/4

# Get all authors : GET : http://localhost:8081/api/v1/authors

# Get author based on Id : GET : http://localhost:8081/api/v1/authors/1

# Post a author : POST : http://localhost:8081/api/v1/authors
 {
    "name": "Akhil"
 }

# update and author : PUT : http://localhost:8081/api/v1/authors/5
 {
    "name": "Akhil katakam"
 }

# delete an author : DELETE : http://localhost:8081/api/v1/authors/5


Frontend
---------
As the files are too large to upload on to the github, i have uploaded on to Google drive for you to access. Please download from the below link
https://drive.google.com/file/d/1HtgVeEp0UJksh4XQQuJaIZ7qy-yPeEGP/view?usp=sharing

Once you extract the folder ,go to command prompt and Run the following commands
- npm install -g @angular/cli
- npm install
- npm install -g bootstrap@3.3.7 --save
- once the above has been installed
- In C:\bookstore\book-app\angular.json add  "node_modules/bootstrap/dist/css/bootstrap.css" so it should look like below
  "styles": [
              "src/styles.css",
              "node_modules/bootstrap/dist/css/bootstrap.css"
            ],

Snapshots
-----------

Please note that i have also attached snapshots for Frontend app,Rest API services and Database on Google drive. Here is the linke to access

https://drive.google.com/file/d/1WhfleJ53G94Ehi3dG9vybJwmb8G0pW_4/view?usp=sharing


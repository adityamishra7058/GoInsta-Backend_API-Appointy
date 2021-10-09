# GoInsta-Backend_API-Appointy
## NOTE: Passwords stored in the database are also encrypted by using Hash Functions that makes it more secure.
=================================================================================================================================================================================
## Steps to be followed to run the uploaded files.

1)	Open “main.go”, “login.gtpl”, “post.gtpl”  file in Visual Studio Code and just run “main.go” file.

2)	Meanwhile just enter “localhost:9090/users” in the search bar of your browser to enter the details of the user.

3)	Similarly, “localhost:9090/users/”, “localhost:9090/posts”, “localhost:9090/posts/” and “localhost:9090/posts/users/” to view the functioning of Users, New posts, Post By ID and All Post By Users respectively.

4)	All the data that is entered in the forms will be stored in the Database present in the MongoDB Cloud as shown below.

5)	The output will also be shown in the Terminal section of VSCode.
=================================================================================================================================================================================

### This Backend API includes the following functions:

Create an User
 -Should be a POST request
 -Use JSON request body
 -URL should be ‘/users'
Get a user using id
 -Should be a GET request
 -Id should be in the url parameter
 -URL should be ‘/users/<id here>’
Create a Post
 -Should be a POST request
 -Use JSON request body
 -URL should be ‘/posts'
Get a post using id
 -Should be a GET request
 -Id should be in the url parameter
 -URL should be ‘/posts/<id here>’
List all posts of a user
 -Should be a GET request
 -URL should be ‘/posts/users/<Id here>'

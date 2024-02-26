# Business-on-Bot-backend
SERVER SIDE:
In the server-side code, I have implemented essential functionalities using Express.js. The "users.js" file handles user-related routes, including updating  accounts, retrieving user information, managing user relationships, and searching for users. The "auth.js" file takes care of user registration and login, ensuring secure password handling. The "post.js" file deals with post-related operations, such as creating, updating, deleting, liking, and fetching posts. These routes collectively provide a robust backend structure for a social media platform, offering user management, authentication, and post handling.

Database Schema Summary:
The MongoDB database schema, defined in "users.js" and "post.js," captures the structure of user and post data. In the "User" schema, various attributes such as username, email, password, profile and cover pictures, followers, followings, and additional details like city, from, and relationship status are stored. The "Post" schema focuses on posts, storing details like userId, post description, image, and an array to track post likes. Both schemas include timestamps to record when entries are created or modified. 

I have used Mongodb For database and Express.js for server side framework.






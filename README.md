Project Title
URL Shortener

Project Description
The URL Shortener project is a web application that allows users to shorten long URLs into more manageable, compact links. The application generates a unique, shorter URL that redirects to the original long URL when accessed. This service is useful for sharing long links in a more convenient format, especially on social media platforms, in emails, and in other places where space is limited.

Technologies Used
Programming Languages: JavaScript
Frameworks: Node.js, Express.js
Libraries: Mongoose (for MongoDB interaction), shortid (for generating short URLs)
Database: MongoDB
Features
URL Shortening: Generate a shorter URL for a given long URL.
Redirection: Redirect users to the original URL when the short URL is accessed.
Analytics: Track the number of clicks on each short URL.
Installation Instructions
Prerequisites
Node.js
MongoDB
Steps
Clone the Repository:

sh
Copy code
git clone [URL to your repository]
cd url-shortener
Set Up Environment Variables:
Create a .env file in the root directory and add your MongoDB connection string:

perl
Copy code
MONGODB_URI=mongodb+srv://jothivel:jo123@cluster0.8gilg3b.mongodb.net
Install Dependencies:

sh
Copy code
npm install
Start the Application:

sh
Copy code
npm start
The application will be running on http://localhost:5000.

Usage Instructions
Access the Application:
Open your web browser and navigate to http://localhost:5000.

Shorten a URL:

Enter the long URL in the input field.
Click the "Shorten" button.
View Shortened URLs:

The table displayed on the homepage will show the full URL, the shortened URL, and the number of clicks for each shortened URL.
Libraries Used
Mongoose
Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment. It provides a straight-forward, schema-based solution to model your application data. It includes built-in type casting, validation, query building, and business logic hooks for seamless interaction with MongoDB databases.

shortid
Shortid is a library for generating concise, unambiguous, and URL-friendly IDs. It is used in the URL Shortener project to generate unique short URLs for the long URLs provided by users.

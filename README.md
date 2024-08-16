# My-Portfolio-Web-Server
Hi! I'm Antonio Urdaneta, and this is a simple Flask-based web server I created to host my personal portfolio webpage. The server is defined in the server.py file, and it renders the index.html template when you visit the site. This page showcases my professional information, including links to my LinkedIn, GitHub, and email.

Features

    Flask Framework: I used the Flask framework to build this server, which handles routing and template rendering.
    Responsive Design: The webpage is designed using the Aerial theme by HTML5 UP, ensuring it's mobile-friendly and visually appealing.
    Social Media Links: You'll find links to my LinkedIn, GitHub, and a mailto link for direct contact via email.
    Custom Favicon: I included a custom favicon to represent my personal brand.

Prerequisites

Before you can run the server, make sure you have the following installed:

    Python 3.x: This is needed to run the Flask application.
    Flask: If you don't have Flask installed yet, you can do so with:

bash

pip install Flask

Project Structure

Here's how the project is structured:

.
├── server.py                        # Main server file
├── templates/
│   └── index.html                   # HTML template served by the server
└── static/
    └── assets/
        ├── css/
        │   ├── main.css             # Main CSS file for styling
        │   ├── noscript.css         # Fallback CSS for no JavaScript
        └── images/
            └── favicon.ico          # Custom favicon for the website


Running the Server

To get the server up and running, just navigate to the project directory and run:

bash

python server.py

Once the server is running, open your web browser and go to:

arduino

http://127.0.0.1:5000/

There you'll see my portfolio page.
Customization

    HTML Content: Feel free to customize the index.html file in the templates/ directory if you'd like to update the content or design of the webpage.
    CSS Styling: You can modify the CSS files in the static/assets/css/ directory to change the look and feel.
    Adding More Pages: If you want to add more pages, just create additional HTML files in the templates/ directory and define new routes in the server.py file.

License

This project uses the Aerial theme by HTML5 UP, which is free for personal and commercial use under the CCA 3.0 license.

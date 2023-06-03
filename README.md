# UrlShortenerService

This repository contains the code for a simple URL shortener built using Golang. It provides a lightweight and efficient solution to shorten long URLs and redirect users to their intended destination.

##Features
URL shortening: Converts long URLs into short and compact forms.
Redirects: Automatically redirects users to the original long URL when they access the shortened URL.
Customizable short URLs: Allows users to specify a custom alias for their shortened URL.
Click tracking: Tracks the number of clicks and provides statistics on the usage of shortened URLs.
Getting Started
To get started with the URL shortener, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/jrstupka/url-shortener.git
Install Golang: Make sure you have Golang installed on your machine. You can download it from the official Golang website.
Build and run the application:
bash
Copy code
go build .
./url-shortener
Access the application: Open your web browser and go to http://localhost:8080 to access the URL shortener.
Configuration
The URL shortener can be customized by modifying the configuration file (config.yaml). You can specify the desired port, database connection settings, and other options according to your environment and requirements.

Technologies Used
Golang: The main programming language used for building the URL shortener.
Gorilla Mux: A powerful HTTP router used for handling routing and request handling.
SQLite: A lightweight and embedded database used for storing shortened URLs and click statistics.
Contributing
Contributions to the URL shortener project are welcome! If you find any bugs, have suggestions for improvements, or would like to add new features, please feel free to open an issue or submit a pull request.

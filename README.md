# bar_chart_server
This project is a simple web server built using Flask to serve an HTML page displaying a bar chart. The chart represents some example data (e.g., monthly sales data) and is created using basic HTML and CSS for styling.

Project Structure



bar_chart_server/
│
├── server.py              # Python Flask server file
└── templates/
    └── index.html         # HTML file with the bar chart

Prerequisites

Before running the server, make sure you have Python 3.x installed. You also need to install Flask.

Install Flask
To install Flask, run the following command:



pip install flask




cd bar_chart_server
Install the dependencies:



pip install -r requirements.txt
Run the Flask server:


python server.py
Open your browser and navigate to:


http://127.0.0.1:5000/

You should see a webpage displaying a bar chart.

Project Details
HTML: The chart is created using a simple div layout styled with CSS. Each bar represents a different month of sales data.

CSS: Basic styling is used to arrange the bars and display the chart in a clean and simple format.

Flask: Flask is used to serve the index.html file and render it on the web browser.

How It Works
Flask Server (server.py):
The Flask app runs a web server that listens on the default 5000 port. When you access the home route (/), it renders the index.html file from the templates folder.

HTML File (index.html):
This file contains the HTML structure for the page, including a simple bar chart that uses inline styles to adjust the height of each bar.


                                                                 E-Commerce Website with Sentiment Analysis Integration
This project demonstrates the integration of a simple E-Commerce website with sentiment analysis using Flask and the Hugging Face Transformers library. The website allows users to view product details, read and submit reviews, and provides a sentiment analysis summary based on customer reviews.

Table of Contents
•	Getting Started
•	Prerequisites
•	Installation
•	Project Structure
•	Usage
•	Running the Flask App
•	Accessing the Website
•	Sentiment Analysis
•	Acknowledgements
Prerequisites
Before running the project, make sure you have the following installed:
Python 3.x
Pip
Flask
Transformers library (pip install transformers)
Installation
git clone <repository-url>
pip install -r requirements.txt
Project Structure
The project is divided into three main parts:
Frontend (HTML, CSS, JavaScript):
The index.html file contains the structure of the E-Commerce website, including product details and customer reviews.
JavaScript functions are included to handle user interactions, such as showing/hiding the review form and adding reviews dynamically.
Backend (Flask):
The Flask app is defined in app.py, which includes routes for rendering the HTML templates and handling the storage of customer reviews.
The store_comment endpoint performs sentiment analysis on the submitted review using the Hugging Face Transformers library.

Sentiment Analysis Results (HTML):
The summary_output.html file displays the sentiment analysis results, including individual comments and the majority sentiment.
Usage
Running the Flask App
Navigate to the project directory:
cd <project-directory>
Run the Flask app:
python app.py

Accessing the Website
Open a web browser and go to http://127.0.0.1:5000/ to access the E-Commerce website. Navigate through the different sections, view product details, and submit reviews.
Sentiment Analysis
The sentiment analysis is performed on customer reviews using the Hugging Face Transformers library. The majority sentiment is calculated based on the predicted labels (positive, negative, or neutral) of individual reviews. The results are displayed in the summary section of the website.
Acknowledgements
This project uses the Flask framework for building the web application.
Sentiment analysis is performed using the Hugging Face Transformers library.
Feel free to explore, modify, and enhance this project based on your requirements!

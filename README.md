Flask Data Visualization App
Overview
This application provides interactive data visualization using Flask as the backend framework. It allows users to upload datasets and view various visualizations, making data analysis more intuitive and accessible.

Features
Upload CSV or JSON datasets
View a selection of interactive charts (e.g., bar charts, line charts, scatter plots)
Filter data based on user-selected criteria
Export visualizations as image files
Installation
Prerequisites
Python 3.7+
Flask
Additional dependencies (e.g., pandas, matplotlib, Plotly)
Setup
Clone this repository:

bash
Copy code
git clone <(https://github.com/crimsonantmk/Datavisualisation)>
Navigate into the project directory:

bash
Copy code
cd flask-data-visualization-app
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Start the application:

bash
Copy code
export FLASK_APP=app.py
flask run
Alternatively, to run in debug mode:

bash
Copy code
flask run --debug
Open your browser and navigate to http://127.0.0.1:5000.

Uploading Data: Upload your dataset on the home page.

Visualize Data: Choose from the visualization options to create different charts. You can select columns to plot and apply filters to tailor the data display.

Exporting Charts: After creating a chart, click the export button to download the chart as an image file.

Directory Structure
php
Copy code
flask-data-visualization-app/
│
├── app.py                # Main application file
├── templates/            # HTML templates
├── static/               # CSS, JS, and image assets
├── uploads/              # Folder for storing uploaded data files
├── requirements.txt      # Package dependencies
└── README.md             # This file
Contributing
Feel free to fork the repository, make enhancements, and submit a pull request!

License
This project is licensed under the MIT License.

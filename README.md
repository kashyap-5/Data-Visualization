# Data-Visualization
 Welcome to the Data Visualization Projects repository! This collection showcases projects that use various tools and techniques to transform raw data into insightful, interactive, and visually engaging visualizations. Explore different approaches to simplify complex datasets and tell compelling data stories.

Multi-Page Dash-Plotly Web App
This project is a multi-page web application built using Dash and Plotly. The application showcases various datasets and visualizations, providing an interactive user experience.

Features
Multi-page navigation
Interactive data tables
Dynamic visualizations using Plotly
Responsive design with Bootstrap styling

Project Structure
.
├── app.py
├── pages
│   ├── home.py
│   ├── dataset.py
│   └── visualization.py
├── assets
│   └── styles.css
├── titanic.csv
└── README.md

app.py: The main entry point of the application.
pages/: Directory containing the different pages of the application.
home.py: Home page of the application.
dataset.py: Page displaying the Titanic dataset.
visualization.py: Page with various visualizations.
assets/: Directory for static assets like CSS files.
titanic.csv: Sample dataset used in the application.
README.md: Project documentation.

Installation
1.Clone the repository:
    git clone https://github.com/kashyap-5/multi-page-dash-plotly-app.git
    cd multi-page-dash-plotly-app
2.Create a virtual environment:
    python -m venv venv
3.Activate the virtual environment:
    .\venv\Scripts\activate
4.Install the dependencies:
    pip install -r requirements.txt
Usage
Run the application:
  python app.py
Open your web browser and navigate to http://127.0.0.1:8050/ to view the application

Acknowledgements
Dash
Plotly
Bootstrap

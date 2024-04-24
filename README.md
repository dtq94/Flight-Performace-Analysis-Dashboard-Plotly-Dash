## Flight Performance Analysis Dashboard

The Flight Performance Analysis Dashboard is an interactive web-based tool built using Plotly and Dash, designed to analyze and report US domestic airline flight performance. This dashboard enables users to explore various performance metrics, including flight cancellations, average flight times, diverted airport landings, and more, over a specified time period.

### Overview

The dashboard provides two main types of reports:

1. **Yearly Airline Performance Report:**
   - Users can select a specific year to view detailed performance metrics for that year. The report includes:
     - Number of flights under different cancellation categories
     - Average flight time by reporting airline
     - Percentage of diverted airport landings per reporting airline
     - Number of flights flying from each state

2. **Yearly Airline Delay Report:**
   - Users can select a specific year to view delay statistics for that year. The report includes:
     - Monthly average carrier delay by reporting airline
     - Monthly average weather delay by reporting airline
     - Monthly average NAS delay by reporting airline
     - Monthly average security delay by reporting airline
     - Monthly average late aircraft delay by reporting airline
    
### Key Features
- Interactive dropdowns to select report type and year
- Real-time visualization updates based on user inputs
- Detailed insights into airline performance metrics
- User-friendly interface for exploring and analyzing flight data

### Deployment
1. Run the dashboard locally on your machine using the provided Python code.
2.  Deploy the dashboard on a web server to make it accessible to a wider audience.
3. Customize and extend the dashboard as needed to meet specific analytical requirements.

### How the App is Built

The Flight Performance Analysis Dashboard is built using the following steps:

1. **Import Required Libraries:** Necessary libraries like Pandas, Dash, Plotly, etc., are imported.
2. **Read and Preprocess Data:** The airline data is read into a Pandas DataFrame and preprocessed as needed.
3. **Create Dash Application:** A Dash application is created to host the dashboard.
4. **Define Callback Functions:** Callback functions are defined to update the dashboard based on user inputs.
5. **Define Layout:** The layout of the dashboard is defined using HTML and Dash components.
6. **Run the App:** The Dash application is run, and the dashboard is displayed in a Jupyter Notebook.

### Dashboard Components

The dashboard consists of the following components:

- Dropdowns to select the report type and year.
- Graphs to visualize the performance metrics based on user selections.

### Tech Stack
- Python (Pandas, Dash)
- Plotly (Plotly Graph Objects, Plotly Express)
- Jupyter Notebook

# Overview
This web application displays a report of product sales using data from a CSV file. It utilizes Bootstrap for styling and includes a dynamically generated table that lists each product alongside its total sales.

# Setup
1. Download or clone the repository.
2. Ensure you have a local server to serve the HTML file and the `data.csv` file.
3. Place `data.csv` in the same directory as the `index.html` file.

# Usage
Open the `index.html` file in a web browser. The application will load the product sales data from `data.csv` and display it in a Bootstrap-styled table. The total sales will be calculated and displayed at the bottom.

# Improvements
In this version, the application dynamically fetches and processes the `data.csv` file using the `fetch()` API, ensuring that the displayed data is always up to date. The total sales calculation is now more accurate, reflecting the sum of all sales values directly from the table during rendering. Additionally, the code structure has been improved for better readability and maintainability.
```
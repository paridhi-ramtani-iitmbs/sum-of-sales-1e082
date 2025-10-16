# Overview
This web application displays a report of product sales using data from a CSV file. It utilizes Bootstrap for styling and includes a dynamically generated table that lists each product alongside its total sales. The application now features seamless updates upon changes in the data.

# Setup
1. Download or clone the repository.
2. Ensure you have a local server to serve the HTML file and the `data.csv` file.
3. Place `data.csv` in the same directory as the `index.html` file.

# Usage
Open the `index.html` file in a web browser. The application will load the product sales data from `data.csv` and display it in a Bootstrap-styled table with an ID of `#product-sales`. The total sales will be calculated and accurately displayed at the bottom with the ID `#total-sales`, reflecting the sum of all sales values directly from the table during rendering.

# Improvements
In this version, the application dynamically fetches and processes the `data.csv` file using the `fetch()` API, ensuring that displayed data is always up to date. The total sales calculation is seamlessly integrated within the table rendering, accurately updating the `#total-sales` element. The code structure has been improved for better readability and maintainability, and the table specifically utilizes a Bootstrap layout for a polished appearance.
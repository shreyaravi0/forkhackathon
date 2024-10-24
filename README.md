# forkhackathon
Food Compliance Checker
The Food Compliance Checker is a web-based application that allows users to scan product barcodes or search for products by name to retrieve detailed information about the product. It checks for FDA compliance and displays nutritional content, ingredients, allergens, and other relevant data from Open Food Facts. The app includes a real-time barcode scanning feature using the device’s camera, making it easy to input barcodes.

Features-
Real-time Barcode Scanning: Use your device’s camera to scan product barcodes with the help of QuaggaJS.
Manual Barcode Entry: Alternatively, enter a barcode manually to retrieve product details.
Product Search: Search for products by name if the barcode is not available.
Detailed Product Information: Displays detailed product information including ingredients, nutritional info, brands, packaging, and more.
FDA Compliance Check: Automatically checks ingredients against the OpenFDA API to determine if they are FDA-approved.
Allergen Information: Provides a list of known allergens present in the product.

Tech Stack
Backend:
Flask: The primary web framework for building the application logic.
Requests: To make HTTP requests to external APIs like Open Food Facts and OpenFDA.

Frontend:
HTML: For structuring the content of the web page.
CSS (Twitter Dark Theme): For styling the application with a dark mode theme.
JavaScript (QuaggaJS): For barcode scanning functionality using the device’s camera.
Jinja2: To dynamically render HTML templates based on the backend logic.

APIs:
Open Food Facts API: Retrieves detailed product information based on barcode or product name.
OpenFDA API: Checks if the ingredients in the product comply with FDA regulations.

PROJECT BY RVCE COLLEGE STUDENTS:
ADITYA K (1RV23ME011)
ANSH RAVI KASHYAP (1RV23CS040)
SHREYA RAVI (1RV23CD051)
POORVI BELLUR (1RV23CD037)


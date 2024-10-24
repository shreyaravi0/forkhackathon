
team name : FORK FOOD TRACKER
# 🍏 **Food Compliance Checker** 🍎
Welcome to the **Food Compliance Checker**, a web-based application designed to make food label transparency and compliance easy! This tool enables users to scan barcodes or search for products by name, providing detailed insights into ingredients, allergens, FDA compliance, and nutritional content in real-time.


- **🎥 Real-Time Barcode Scanning**: Use your device's camera to quickly scan product barcodes, powered by the smooth **QuaggaJS** library.
- **🔢 Manual Barcode Entry**: No barcode scanner? No problem! Enter a barcode manually to fetch product details instantly.
- **🔍 Product Search**: Search by product name if the barcode is unavailable, pulling results directly from **Open Food Facts**.
- **📊 Detailed Product Information**: Get insights into ingredients, nutritional value, brands, packaging, eco-scores, and certifications.
- **✔️ FDA Compliance Check**: Automatically verifies the product ingredients against the **OpenFDA API** to ensure regulatory approval.
- **⚠️ Allergen Information**: Identifies common allergens present in the product for enhanced user safety.

---

## 🎨 **Tech Stack**

### **Backend**
- **Flask**: The robust Python web framework driving the backend logic.
- **Requests**: For making lightning-fast HTTP requests to external APIs like Open Food Facts and OpenFDA.

### **Frontend**
- **HTML**: Clean and structured web page design.
- **CSS (Twitter Dark Theme)**: A sleek, modern look with a dark mode twist.
- **JavaScript (QuaggaJS)**: Barcode scanning functionality to access your device’s camera.
- **Jinja2**: Dynamic rendering of HTML templates with Python-powered logic.

### **APIs**
- **Open Food Facts API**: Provides detailed product information such as ingredients, nutritional content, and packaging based on the product barcode or name.
- **OpenFDA API**: Validates product ingredients against FDA regulations for food safety compliance.

---

## 🚀 **How to Use**

1. **Scan or Enter a Barcode**: Use the camera for a quick scan or manually enter the barcode to retrieve product details.
2. **Search by Product Name**: No barcode? Simply type the product name into the search bar for results.
3. **View Detailed Info**: Get instant access to nutritional content, allergen information, eco-scores, and more.
4. **Check FDA Compliance**: The app will automatically check if the ingredients comply with FDA regulations.

---

## 📚 **Installation Instructions**

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/food-compliance-checker.git
   cd food-compliance-checker
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask server:
   ```bash
   python app.py
   ```

4. Open your web browser and navigate to:
   ```
   http://127.0.0.1:5000/
   ```

---

## 👨‍💻 **Team Members**  
We are a group of passionate RVCE students driven by our love for tech and making a positive impact through innovation!

- **Aditya K** (1RV23ME011)  
- **Ansh Ravi Kashyap** (1RV23CS040)  
- **Shreya Ravi** (1RV23CD051)  
- **Poorvi Bellur** (1RV23CD037)

---

## 💡 **Future Plans**

- Integrate voice search for hands-free product lookup.
- Improve allergen detection with AI-based ingredient analysis.
- Add more comprehensive compliance checks (non-FDA approved additives, country-specific regulations).

---

Our **Food Compliance Checker** goes beyond the typical food labeling app by combining real-time barcode scanning, FDA regulatory checks, and user-friendly design with dark mode. It’s perfect for those who want to make informed food choices instantly, all while delivering a top-notch user experience. 🚀

---

Let’s make **food safety** as simple as scanning a barcode! 💚

---

# 🚀 Shopify XPOREFY
# 🚀 Shopify Export Script

## 📌 Overview
This script exports Shopify store data, including Products, Orders, Blogs, and more. It allows you to export data in **CSV, JSON, or XML** formats and migrate/import data between Shopify stores.

## 📂 Features
- 📦 **Export Data** (Products, Orders, Blogs, Customers, etc.)
- 🔄 **Import & Migrate Data** between Shopify stores
- 📑 **Supports CSV, JSON, and XML formats**
- 🚀 **Auto-fetches data without manual input**
- 📝 **Logs errors and API responses**

## 🛠️ Installation
### **1️⃣ Clone the Repository**
```sh
 git clone https://github.com/<your-username>/Shopify-Export.git
 cd Shopify-Export
```

### **2️⃣ Install Dependencies**
Ensure you have Python installed. Then, install required dependencies:
```sh
pip install requests pandas beautifulsoup4
```

## 🎯 Usage
### **1️⃣ Run the Script**
```sh
python export_shopify.py
```

### **2️⃣ Connect Your Store**
- Select a saved store or add a new one by entering API credentials.
- The script will validate and save your credentials.

### **3️⃣ Choose an Action**
- 🔹 **Export Data** → Save Shopify store data
- 🔹 **Import Data** → Import/migrate Shopify data

### **4️⃣ Select Data Type**
- Choose **Products, Orders, Blogs, Customers, etc.**

### **5️⃣ Select File Format**
- CSV
- JSON
- XML

## 📂 Output Files
- Exported data is saved in the `exported_YYYY-MM-DD` folder.
- Blog articles are stored **individually** per category.

## 🛑 Error Logging
Errors are logged in `error_log.txt` for debugging.

## 📜 License
This project is open-source. Feel free to modify and use it.

## 🤝 Contributing
Pull requests are welcome! Fork the repo and submit your improvements.

---
**Maintained by:** BASH & Z

[https://github.com/CSR2HUB](https://github.com/CSR2HUB)


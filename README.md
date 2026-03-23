🛍️ La Julie — Point of Sale System
A desktop Point of Sale (POS) application built with Python and PyQt6, designed for retail shops. It features a clean dark-gold UI, full sales management, inventory tracking, customer records, and detailed reporting — all stored locally with SQLite.

✨ Features

Sales & Checkout — Fast product lookup by code or name, support for cash & visa payments, discounts (fixed or percentage), and receipt printing
Product Management — Add, edit, and delete products with category, size, price, and stock quantity
Customer Management — Save customer profiles, track visit history and total spending
Inventory Alerts — Dashboard warnings for low-stock items (below 5 units)
Sales Reports — Daily/weekly charts, revenue breakdown, top-selling products, and Excel export
Barcode & QR Support — Generate barcodes and QR codes for products
Employee Roles — Manager and cashier accounts with login authentication
PDF Receipts — Auto-generated receipts via fpdf
Offline & Portable — Runs fully offline; all data stored in a local pos.db SQLite file


🖥️ Tech Stack
LayerTechnologyLanguagePython 3.10+UI FrameworkPyQt6DatabaseSQLite (WAL mode)ChartsMatplotlibReportsopenpyxl, fpdfBarcodespython-barcode, qrcodeImagesPillow

🚀 Getting Started
1. Clone the repository
bashgit clone https://github.com/your-username/la-julie-pos.git
cd la-julie-pos
2. Install dependencies
bashpip install -r requirements.txt
3. Run the app
bashpython main.py
Default Login
FieldValueUsernameadminPasswordadmin

⚠️ Change the default password after first login.


📁 Project Structure
la-julie-pos/
├── main.py          # Main application & UI
├── database.py      # Database setup & migrations
├── pos.db           # SQLite database (auto-created)
├── logo.png         # App logo (optional)
├── icon.ico         # App icon (optional)
└── sales_report.xlsx # Exported reports

📦 Requirements
PyQt6
matplotlib
fpdf2
openpyxl
python-barcode
qrcode
Pillow
pyserial

👨‍💻 Developer
George Adel
📞 +201507591817

📄 License
This project is proprietary software. All rights reserved.

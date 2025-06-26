# 🛒 Category & Product Management Web Application

This is a simple web-based CRUD (Create, Read, Update, Delete) application to manage **Product Categories** and **Products**, including an option to **upload product data from Excel files**.

> **Frontend Only Project** – Fully functional using **HTML + Tailwind CSS + JavaScript** with `localStorage`.

---

## 📁 Files Included

- `Category.html` – Manage product categories.
- `Product.html` – Manage products and Excel uploads.
- `test-description(06-2025).md` – Problem statement and requirements from the hiring test.

---

## 🚀 Features

### ✅ Category Management
- Add/Edit/Delete categories.
- Fields: `Category Name`, `Description`.
- Validation for unique category names.
- Data stored in browser's `localStorage`.

### ✅ Product Management
- Add/Edit/Delete products.
- Fields: `Product Name`, `Category`, `Price`, `Stock`.
- Validation for empty fields, valid price/stock values.

### ✅ Excel Upload (Product.html)
- Upload `.xlsx` Excel file to add/update products.
- Format:
  - Sheet name: **Products**
  - Columns: `product_name`, `category_name`, `price`, `stock`
- If product already exists → updates price and stock.
- Shows clear error messages for invalid rows.

---

## 📦 How to Use

1. Open `Category.html` in a browser to add/manage categories.
2. Open `Product.html` in a browser to add/manage products or upload from Excel.
3. Use the navigation buttons to switch between pages.

> **Note**: Data is saved in your browser using `localStorage`. No backend is required.

---

## 📂 Excel File Format

Make sure your Excel file:
- Contains a sheet named `Products`.
- Follows this column order (first row as header):

# 🧾 Persian Invoice Generator

A simple, terminal-based Python project that generates **Persian-language invoices** using user input, an HTML template with Jinja2, and PDF generation via `pdfkit`.

---

## 📌 Features

- 🧑‍💼 Takes customer and product info via CLI
- 🧾 Calculates product totals, tax, and discounts automatically
- 🌐 Uses `Jinja2` to render a Persian invoice (RTL)
- 📅 Includes Jalali (Persian) date via `jdatetime`
- 📄 Exports result as a clean, printable **PDF invoice**

---

## 📁 Project Structure

invoice-generator/

│   
├── invoice.py # Main script (you run this)   
├── templates/   
│ ├── template.html # Jinja2 HTML template (Persian format)  
├── inv.pdf # Final generated invoice  
├── README.md # You're here  


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


---

## 🔧 Requirements

- Python 3.6+
- [wkhtmltopdf](https://wkhtmltopdf.org/downloads.html) (must be installed separately)
- Python libraries:
  - jinja2
  - pdfkit
  - jdatetime

- Make sure wkhtmltopdf is installed and its path is correctly set in the script:

```bash
wkhtmltopdf = r"C:\Program Files\wkhtmltopdf\bin\wkhtmltopdf.exe"
```
  ---

  ## ▶️ How to Use
1- Clone the repo:

```bash
git clone https://github.com/bardiw/invoice.git
cd invoice-generator
```

2- Run the script:

```bash
python invoice.py
```
3- Fill in all requested fields:
- Customer info
- Product details (code, name, quantity, unit, unit price, discount, tax)
- Terms and notes

4- Your invoice will be saved as: inv.pdf

---

## 📋 Example Input
```
order number: 1254
customer name: علی مرادی
economical number: 123456
national code: 0042158735
...
number of products: 2
  → product 1: code, name, number, unit, price, discount, tax
  → product 2: ...
```

---

## 🖨️ Output Preview
The final output (inv.pdf) is a printable, styled invoice in Persian, supporting:

- Table of products with pricing, discounts, and tax

- Buyer & seller information

- Payment terms and description

- Auto date (based on Jalali calendar)

---
  
👨‍💻 Author

 Bardia Javadi   
 GitHub: [@bardiw](https://github.com/bardiw)
 Email: bardia.javadi.2003@email.com  


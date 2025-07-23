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

👨‍💻 Author
Bardia Javadi  
GitHub: @bardiw  
Email: bardia.javadi.2003@email.com  


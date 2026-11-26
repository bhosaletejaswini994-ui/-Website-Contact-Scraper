# 🌐 Website Contact Scraper

## 📌 Project Overview

Website Contact Scraper is a Python-based desktop application developed using CustomTkinter. It automatically extracts publicly available contact information from websites, including email addresses, mobile numbers, landline numbers, and other phone numbers.

The application allows users to enter multiple website URLs, scrape contact details, view the results, and export the collected information into an Excel file.

## ✨ Features

- **Multiple Website Scraping:** Extract contact information from multiple websites at once.
- **Email Extraction:** Automatically identifies email addresses.
- **Mobile Number Detection:** Extracts and identifies valid mobile numbers.
- **Landline Detection:** Separates landline numbers from mobile numbers.
- **Contact Page Scanning:** Searches Contact, About, Support, and Company pages.
- **Live Results:** Displays extracted information in real time.
- **Progress Bar:** Shows the scraping progress.
- **Excel Export:** Saves collected information into an Excel workbook.
- **User-Friendly GUI:** Simple and attractive interface built with CustomTkinter.
- **Multi-threading:** Uses threading to keep the application responsive during scraping.

## 🛠️ Technologies Used

- **Python** – Main programming language.
- **CustomTkinter** – Graphical User Interface (GUI).
- **BeautifulSoup** – Extracts information from HTML pages.
- **Requests** – Sends HTTP requests to websites.
- **Regular Expressions (Regex)** – Identifies email addresses.
- **PhoneNumbers** – Validates and identifies phone numbers.
- **OpenPyXL** – Exports contact information into Excel.
- **Threading** – Performs scraping in the background.

## 📦 Required Libraries

Install the required libraries using:

```bash
pip install customtkinter beautifulsoup4 requests openpyxl phonenumbers
```

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Open the project folder in VS Code.
3. Install all required libraries.
4. Run the Python file:

```bash
python ScrappingApp.py
```

5. Enter one or more website URLs.
6. Click **Start Scraping**.
7. View the extracted contact information.
8. Click **Save Results** to export the data into Excel.

## 📊 Excel Output

The application exports the collected information into an Excel file named:

`Company Contact Data.xlsx`

The Excel sheet contains the following columns:

| Column | Description |
|---|---|
| Sr. No. | Serial number |
| Company Website | Website URL |
| Email Addresses | Extracted email addresses |
| Mobile Numbers | Detected mobile numbers |
| Landline Numbers | Detected landline numbers |
| Other Phone Numbers | Other valid phone numbers |

## 💡 Real-World Applications

- Business contact information collection.
- Company research and analysis.
- Lead generation.
- Market research.
- Data collection for business analytics.
- Building business contact databases.

## ⚠️ Limitations

- Extracts publicly available information only.
- Some websites may block automated requests.
- JavaScript-rendered contact information may not be detected.
- Results depend on the website's HTML structure.
- Not every website publishes contact information.

## 🔮 Future Improvements

- Add CSV export functionality.
- Add website scraping history.
- Improve support for JavaScript-based websites.
- Add duplicate contact detection across websites.
- Add advanced filtering and search options.

## 👩‍💻 Author

**Tejaswini Bhosale**

## ⭐ Support

If you find this project useful, please give this repository a star on GitHub!

---

*This project was developed for learning Python, web scraping, GUI development, and data extraction.*

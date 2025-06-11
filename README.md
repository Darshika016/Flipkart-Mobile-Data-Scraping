# 📱 Flipkart Mobile Data Scraping using BeautifulSoup

## 🔍 Overview
This project focuses on extracting mobile phone data from [Flipkart.com](https://www.flipkart.com) using Python automation with Selenium. The goal is to collect product details such as name, price, rating, and specifications to enable market analysis or comparison.

## 🎯 Objective
To automate the process of scraping mobile listings from Flipkart and organize the extracted data into a structured format for further analysis.

## 🛠️ Tech Stack
- Python  
- BeautifulSoup  
- Pandas  
- ChromeDriver  
- Git & GitHub

## 📄 Data Collected
- Product Name  
- Price  

## 🧰 Features
- Collects structured data across multiple pages  
- Skips or handles missing product data  
- Make a data frame of output

## 🖼️ Sample Output
```
| Product Name       | Price   |
| ------------------ | ------- | 
| Redmi 12 5G        | ₹11,999 | 
| Samsung Galaxy M14 | ₹13,490 | 
```

## 🗂️ Folder Structure
```
Flipkart-Mobile-Scraping/
├── flipkart_scraper.py
├── output.csv
├── requirements.txt
└── README.md
```

## ▶️ How to Run

1. **Clone the repo**:
   ```bash
   git clone https://github.com/Darshi
   ka016/flipkart-mobile-scraping.git
   cd flipkart-mobile-scraping

2. Install dependencies:
   ```
   pip install -r requirements.txt

3. Run the scraper:
   ```
   python flipkart_scraper.py
   ```

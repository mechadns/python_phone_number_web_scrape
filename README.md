# Phone Number Scraper

This repository contains a Python-based scraper designed to collect **publicly available** phone numbers from **Google Search** results. The tool automates queries, extracts visible phone numbers, and populates them into a structured CSV file for easy enrichment and further use.

> ⚡️ **Disclaimer**: This tool is designed to strictly scrape publicly available phone numbers. Ensure your usage complies with Google's Terms of Service and local data privacy regulations.

---

## 🚀 Features

- Automated querying via Google Search.
- Extraction of publicly visible phone numbers from result pages.
- CSV output (`Enriched_Dataset.csv`) with cleaned and enriched data.
- Built-in basic error handling for common scraping issues.
- Written in Jupyter Notebook (`Scrapping_script.ipynb`).

---

## 📂 Files in this Repository

| File | Description |
|:-----|:------------|
| `Scrapping_script.ipynb` | Jupyter Notebook containing the scraping script and all processing logic. |
| `Enriched_Dataset.csv` | Output CSV containing the extracted and enriched phone number data. |

---

## 🛠️ Requirements

- Python 3.7+
- Jupyter Notebook
- Key Libraries:
  - `requests`
  - `beautifulsoup4`
  - `pandas`
  - `re` (regular expressions)

Install the required packages using:

```bash
pip install -r requirements.txt
```

---

## 🧹 How to Use

1. **Clone this repository**:

   ```bash
   git clone https://github.com/your-username/phone-number-scraper.git
   cd phone-number-scraper
   ```

2. **Install dependencies**.

3. **Run the Notebook**:

   Open `Scrapping_script.ipynb` using Jupyter Notebook or JupyterLab, and execute the cells sequentially.

4. **Customize Search Terms** (Optional):

   Modify the query section inside the notebook to change the search keywords according to your needs.

5. **View Results**:

   After execution, the enriched phone numbers will be saved in `Enriched_Dataset.csv`.

---

## ⚠️ Important Notes

- **Respect Robots.txt**: Always check and respect the `robots.txt` file of any site you scrape.
- **Rate Limiting**: Add delays between requests to avoid being IP-banned.
- **Legal Compliance**: Scrape responsibly and ensure you adhere to all applicable data privacy laws.

---

## 🧺 Future Improvements

- Integrate proxy support.
- Implement CAPTCHA handling.
- Add multi-threaded scraping for faster data collection.
- Deploy as a Python package or CLI tool.

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

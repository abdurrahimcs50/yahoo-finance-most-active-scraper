# Yahoo Finance Most Active Stocks Scraper

A Python-based web scraper to extract the most actively traded stocks data from Yahoo Finance. This tool collects key financial data such as stock symbols, names, prices, changes, volumes, and market caps, and saves the data in a structured Excel file.

---

## Features

- **Automated Data Extraction**: Fetches the most active stocks from Yahoo Finance.
- **Pagination Handling**: Scrapes data across multiple pages for comprehensive coverage.
- **Structured Output**: Saves data in an Excel file for easy analysis.
- **Customizable**: Easily extendable to scrape additional data points or integrate with other tools.

---

## Technologies Used

- **Python**: Core programming language.
- **Selenium**: For browser automation and web scraping.
- **Pandas**: For data manipulation and cleaning.
- **OpenPyXL**: For saving data to Excel files.

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/abdurrahimcs50/yahoo-finance-most-active-scraper.git
   cd yahoo-finance-most-active-scraper
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download ChromeDriver**:
   - Download the ChromeDriver version compatible with your Chrome browser from [here](https://sites.google.com/chromium.org/driver/).
   - Place the `chromedriver` executable in the project directory or add its path to your system's PATH environment variable.

---

## Usage

1. **Run the Scraper**:
   ```bash
   python scraper.py
   ```

2. **Output**:
   - The scraped data will be saved in an Excel file named `yahoo_finance_stocks.xlsx` in the project directory.
   - The file contains the following columns:
     - `name`: Stock name.
     - `symbol`: Stock symbol.
     - `price_usd`: Current price in USD.
     - `change`: Price change in USD.
     - `volume_M`: Trading volume in millions.
     - `market_cap_B`: Market capitalization in billions.
     - `pe_ratio`: Price-to-earnings ratio.

---

## Code Structure

- **`scraper.py`**: Main script containing the scraper logic.
- **`requirements.txt`**: Lists all the required Python libraries.
- **`README.md`**: Project documentation.

---

## Contributing

Contributions are welcome! If you'd like to improve this project, follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [Selenium](https://www.selenium.dev/) for browser automation.
- [Pandas](https://pandas.pydata.org/) for data manipulation.
- [Yahoo Finance](https://finance.yahoo.com/) for providing the data.

---

## Contact

For questions or feedback, feel free to reach out:

- **Your Name** : MD Abdur Rahim
- **Email**: abdur.rahimcs50@gmail.com
- **GitHub**: [your-username](https://github.com/abdurrahimcs50)
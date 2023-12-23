# StockSavvy 💹

**StockSavvy: Streamlined Stock Trading and Finance**
Welcome to StockSavvy, your streamlined Python and Flask-based web app for stock trading and finance management.

## Overview
StockSavvy allows users to easily create an account, manage their portfolio, and trade stocks with intuitive features. 

## Features 🚀
- **Account Management**: Users can create accounts or log in securely.
- **Portfolio Overview**: View the current valuation of owned stocks alongside the cash balance.
- **Stock Quoting**: Easily search for stock prices using symbols via an intuitive API request.
- **Buying and Selling**: Seamlessly execute stock trades - buy or sell stocks effortlessly.
- **Transaction History**: Keep track of all transactions, displaying date, time, and price at that moment.
- **Error Handling**: Ensures a smooth experience by handling various errors:
  - Wrong stock symbols
  - Buying more stocks than the cash balance
  - Selling stocks in excess of what's owned
  - Incorrect login credentials
  - Registration with an existing username

## Folder Structure
- 📁 `static`: Contains icons and CSS file
- 📁 `templates`: HTML files for different pages
   - `apology.html`: Error handling
   - `buy.html`: Stock buying page
   - `history.html`: Transaction history page
   - `layout.html`: Main home page
   - `login.html`: User login page
   - `quote.html`: Stock quote page
   - `quoted.html`: Display stock price after search
   - `register.html`: User registration page
   - `sell.html`: Stock selling page
- 📄 `app.py`: Flask app with sessions and routes
   - Uses session and database
   - Contains routes for HTML templates
- 📄 `finance.db`: Main database with tables for users, transactions, and portfolios
- 📄 `helpers.py`: Python module with functions and decorators
   - `apology()`, `login_required()`, `lookup()`, `usd()`

## Requirements
- CS50
- Flask
- Flask_Session
- Requests
- Urllib
- UUID
- Pytz
- Functools
- CSV
- Datetime
- Werkzeug.security

## Technology Used
`Python` `Flask` `HTML` `CSS` `Bootstrap` `SQLite3` `API`

## Screenshots
![Portfolio Overview](/path/to/portfolio.png)
*Portfolio Overview: Visual representation of owned stocks and cash balance.*

![Transaction History](/path/to/transactions.png)
*Transaction History: Track all past transactions with date, time, and prices.*

## Usage
1. Clone the repository.
2. Install required dependencies: `pip install cs50 Flask Flask_Session requests pytz`
3. Execute `flask run`.
4. Access the app through the provided localhost URL.

Feel free to contribute and enhance StockSavvy! 🚀📈💼

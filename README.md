# StockFetcher

StockFetcher is a tool designed to retrieve and manage stock data from various exchanges, including AMEX, NASDAQ, and NYSE. It compiles comprehensive lists of stock tickers and associated metadata for analysis and application development.

## Features

- **Exchange Data Compilation**: Gathers stock information from AMEX, NASDAQ, and NYSE.
- **Comprehensive Ticker Lists**: Provides JSON files containing detailed ticker data for each exchange.
- **Centralized Data Access**: Offers an `all_full_tickers.json` file consolidating ticker information across all exchanges.

## Repository Structure

- `amex/`: Contains data files specific to AMEX-listed stocks.
- `nasdaq/`: Contains data files specific to NASDAQ-listed stocks.
- `nyse/`: Contains data files specific to NYSE-listed stocks.
- `all/`: Aggregates data from all exchanges for unified access.
- `icons/`: Stores relevant icons or logos associated with the stocks or exchanges.
- `all_full_tickers.json`: A comprehensive JSON file listing all tickers with detailed information across all exchanges.

## Usage

To utilize the data:

1. Clone the repository:

   git clone https://github.com/atikp/stockFetcher.git

2. Access the desired exchange directory or the `all` directory for combined data.

3. Parse the JSON files as needed for your application or analysis.

## Contributing

Contributions are welcome! If you have updates or additional data to include:

1. Fork the repository.

2. Create a new branch:

   git checkout -b feature/your-feature-name

3. Commit your changes:

   git commit -m "Add some feature"

4. Push to the branch:

   git push origin feature/your-feature-name

5. Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

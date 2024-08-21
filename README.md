# U.S. Bank Financial Metrics Dashboard

This interactive dashboard provides a comprehensive view of U.S. Bank's financial metrics compared to its peer institutions. It allows users to explore various financial indicators, track performance over time, and gain insights into U.S. Bank's position in the banking industry.

## Live Demo

Check out the live dashboard here: [U.S. Bank Dashboard](https://us-bank-dashboard-26a66a4eaf00.herokuapp.com/)

## Features

- Interactive visualization of U.S. Bank's financial metrics compared to peer institutions
- Historical trend analysis for selected metrics
- Detailed statistical overview including percentile ranks, growth rates, and volatility measures
- Customizable peer group selection
- Responsive design for various screen sizes

## Technologies Used

- Python
- Dash (Plotly)
- Pandas
- NumPy
- SciPy
- Dash Bootstrap Components
- Heroku (for deployment)

## Installation and Setup

To run this dashboard locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/your-username/us-bank-dashboard.git
   cd us-bank-dashboard
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Run the application:
   ```
   python app.py
   ```

5. Open a web browser and navigate to `http://localhost:8050` to view the dashboard.

## Usage

1. Select a financial metric from the dropdown menu to display its comparison across banks.
2. Use the date selector to choose a specific date for the comparison.
3. Add or remove peer institutions using the multi-select dropdown.
4. Click on individual bars in the chart to view detailed information for each bank.
5. Explore the trend analysis and statistical overview for deeper insights.

## Data Source

All financial data is sourced from the FDIC (Federal Deposit Insurance Corporation) API. The dashboard fetches the most recent available data for each query.

## Contributing

Contributions to improve the dashboard are welcome! Here's how you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
5. Push to the branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request

Please ensure your code adheres to the existing style and that you've tested your changes thoroughly.

## Acknowledgments

- FDIC for providing the financial data through their API
- Dash and Plotly teams for their excellent data visualization libraries
- The open-source community for various Python packages used in this project

---

For any questions or issues, please open an issue in the GitHub repository or contact the maintainer.

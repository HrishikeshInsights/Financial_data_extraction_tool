

# Financial Data Extraction Tool Using OpenAI API

A powerful and user-friendly tool designed to extract critical financial data from news articles. Leveraging the OpenAI API, this app helps streamline financial data analysis by identifying key information like company names, stock symbols, revenue, net income, and more, directly from a company's financial report news.

This project is built with **Streamlit** for a quick, interactive interface that simplifies the financial data extraction process, making it accessible even to those without technical knowledge. Perfect for analysts, investors, and anyone interested in gaining financial insights from textual data in seconds.

## Features

- **Automated Financial Data Extraction**: Extracts financial metrics such as company name, stock symbol, revenue, net income, etc., from financial news articles.
- **Powered by OpenAI API**: Uses state-of-the-art NLP models to intelligently parse and interpret complex financial reports.
- **Intuitive Streamlit Interface**: A clean, easy-to-navigate interface for a smooth user experience.
- **Customizable & Scalable**: Ready to expand with additional financial metrics and adaptable to other text-based data sources.

## Getting Started

### Prerequisites

- **OpenAI API Key**: You'll need to create an OpenAI account at [OpenAI's website](https://www.openai.com/) and acquire an API key. OpenAI provides $5 in free credits upon sign-up, which is sufficient for testing this project.
- **Python 3.8+**: Ensure Python is installed on your machine.

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/financial-data-extraction.git
    cd financial-data-extraction
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up API Key**: Create a file named `secret_key.py` in the root directory and add your OpenAI API key as follows:
    ```python
    # secret_key.py
    OPENAI_API_KEY = "your_openai_api_key_here"
    ```

### Running the Application

After setting up the dependencies and API key, start the Streamlit application:

```bash
streamlit run app.py
```

Navigate to `http://localhost:8501` in your browser to access the app.

## Usage

1. **Enter the News Article Text**: Copy and paste the relevant section of a financial news article into the text input box.
2. **Extract Key Financial Metrics**: Click the "Extract Data" button, and the tool will output key financial data such as:
   - **Company Name**
   - **Stock Symbol**
   - **Revenue**
   - **Net Income**
   - ...and more.
3. **Interpret and Use**: The extracted data can be easily interpreted, saved, or exported for further analysis.

## Example Output

Given a news article about a company's quarterly earnings, the tool might output:

- **Company Name**: XYZ Corp
- **Stock Symbol**: XYZ
- **Revenue**: $5.6 billion
- **Net Income**: $1.2 billion

This makes it easy to transform textual data into structured information for quick decision-making.

## Project Roadmap

- **Additional Financial Metrics**: Expand functionality to include data points like EBITDA, EPS, and more.
- **Data Export Options**: Support export to CSV or Excel formats for seamless integration into reports.
- **Performance Enhancements**: Improve processing speed for larger articles and multiple inputs.

## Contact

If you have any questions or want to contribute, please reach out to [Hrishikesh REDDY](Hrishikeshreddy.in@gmail,com).

---

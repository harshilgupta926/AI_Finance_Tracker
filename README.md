
```Markdown
# AI Finance Tracker 📊

An AI-powered finance tracking application built using **Python, Streamlit, and Groq API** that helps users analyze their financial data from CSV and Excel files. The application provides automated insights, spending analysis, and interactive visualizations to understand financial patterns easily.

## 🚀 Features

- 📂 Upload financial data using CSV or Excel files
- 🤖 AI-powered financial analysis using Groq API
- 📊 Interactive charts and visual reports
- 💰 Track income, expenses, and spending patterns
- 🔍 Analyze transaction history
- 🧠 Get AI-generated financial insights
- 📈 Identify spending trends and categories
- ⚡ Fast and user-friendly Streamlit interface

## 🛠️ Technologies Used

- **Python** - Core programming language
- **Streamlit** - Web application framework
- **Pandas** - Data processing and analysis
- **OpenPyXL** - Excel file handling
- **Groq API** - AI-powered financial analysis
- **Matplotlib / Plotly** - Data visualization

## 📁 Project Structure

```

AI-Finance-Tracker/
│
├── app.py                 # Main Streamlit application
├── requirements.txt       # Required Python libraries
├── README.md              # Project documentation
│
└── data/
└── sample_finance.csv # Sample dataset

````

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/AI-Finance-Tracker.git
````

### 2. Navigate into the project folder

```bash
cd AI-Finance-Tracker
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

## 🔑 Setup Groq API Key

1. Create an API key from Groq
2. Add your API key in your environment variables:

Windows:

```bash
set GROQ_API_KEY="your_api_key_here"
```

Mac/Linux:

```bash
export GROQ_API_KEY="your_api_key_here"
```

Or add it directly inside your Streamlit secrets file:

```
.streamlit/secrets.toml
```

Example:

```toml
GROQ_API_KEY = "your_api_key_here"
```

## ▶️ Run the Application

Start the Streamlit app using:

```bash
streamlit run app.py
```

The application will open in your browser.

## 📊 How It Works

1. Upload your CSV or Excel finance file.
2. The application processes and cleans the data.
3. Financial information is analyzed using Python and Pandas.
4. AI insights are generated using the Groq API.
5. Visual dashboards display spending behavior and trends.

## 📌 Example Use Cases

* Personal expense tracking
* Monthly budget analysis
* Spending habit evaluation
* Financial report generation
* Understanding income and expense patterns

## 🔮 Future Improvements

* Add expense prediction using Machine Learning
* Add database support
* Add user authentication
* Generate automatic monthly reports
* Add voice-based financial assistant

## 👨‍💻 Author

**Harshil Gupta**

AI | Data Analytics | Python Projects


You can directly paste this as your `README.md`.
```

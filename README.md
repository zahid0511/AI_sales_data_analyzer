# 📊 AI Sales Data Analyzer

An AI-powered sales analytics application that allows users to analyze sales data using **natural language**.

Instead of writing SQL or Python queries manually, users can simply ask questions such as:

> "Which product generated the highest revenue?"

The application uses **PandasAI** to interpret the question and **Gemini through LiteLLM** to perform the analysis, with **Streamlit** providing the interactive web interface.

## 🖥️ Application Preview

Here is a preview of the **AI Sales Data Analyzer** in action:
Screenshot (291).png


The interface allows users to explore sales data, select predefined business questions, or ask their own questions using natural language.


## ✨ Features

* 🤖 Natural-language sales analysis
* 📊 AI-powered data querying with PandasAI
* 🧠 Gemini integration through LiteLLM
* 📁 CSV-based sales data analysis
* 🔍 Predefined business questions
* 💬 Custom questions from users
* 📈 Revenue and sales performance analysis
* 🌐 Interactive Streamlit interface

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **PandasAI**
* **LiteLLM**
* **Google Gemini**
* **Streamlit**

## 💡 Example Questions

The application includes predefined questions such as:

* Calculate the total revenue from all sales.
* Calculate the average order value.
* Identify the product with the highest revenue.
* Find the city with the highest revenue.
* Identify the highest-performing salesperson.

You can also ask your own questions, for example:

```text
Which city sold the most laptops?
```

or

```text
Which salesperson generated the highest revenue?
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-sales-data-analyzer.git
cd ai-sales-data-analyzer
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run app.py
```

The application will open in your browser at:

```text
http://localhost:8501
```

### 🔑 Gemini API Key

When the application starts, enter your **Gemini API key** in the sidebar.

The API key is entered at runtime and is **not stored in the source code**.

## 📂 Project Structure

```text
ai-sales-data-analyzer/
│
├── app.py                  # Streamlit application
├── sales_data.csv          # Sales dataset
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── .gitignore              # Ignored files
```

## 🎯 Project Objective

The goal of this project is to demonstrate how **Generative AI can be combined with traditional data analytics** to make business data easier to explore.

The application allows a user to interact with structured sales data using natural language rather than manually writing analysis code.

## 🔮 Future Improvements

* 📈 Automatic visualization generation
* 💬 Conversational chat history
* 📊 Interactive KPI dashboard
* 📁 Support for Excel and multiple CSV files
* 🔐 Secure API-key management using Streamlit Secrets
* 🚀 Deployment on Streamlit Community Cloud

## 👨‍💻 Author

**Md Zahid**

Built as a practical project exploring **Data Analytics, Generative AI, and AI-assisted business intelligence**.

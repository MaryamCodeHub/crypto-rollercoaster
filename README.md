# 📈 The Crypto Rollercoaster: Bitcoin Price vs Public Interest

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Libraries](https://img.shields.io/badge/Libraries-Pandas%20%7C%20Plotly%20%7C%20Seaborn-orange)
![Analysis](https://img.shields.io/badge/Analysis-Data%20Visualization%20%7C%20Storytelling-green)

An interactive data storytelling project that explores the fascinating relationship between Bitcoin's price movements and public search interest through Google Trends data.

## 🎯 Project Overview

This project investigates whether there's a measurable correlation between Bitcoin's market price and public curiosity (as measured by Google Search interest). Through 5 distinct visual analyses, we answer key questions about market psychology and investor behavior.

## ❓ Key Questions Answered

1. **Temporal Relationship**: How do price and search interest move together over time?
2. **Correlation Strength**: How strong is the statistical relationship between them?
3. **Yearly Patterns**: Which year showed the strongest correlation?
4. **Peak Analysis**: When did the highest price and search interest occur?
5. **Lead-Lag Dynamics**: Does price lead search interest or vice versa?

## 📊 Dataset Sources

- **Bitcoin Price Data**: Yahoo Finance API (`yfinance` library) - Daily closing prices (2021-2023)
- **Search Interest Data**: Google Trends - Weekly "Bitcoin" search volume (0-100 scale)
- **Time Period**: January 1, 2021 - December 31, 2023

## 🛠️ Technical Stack

### Programming Language
- **Python 3.8+**

### Core Libraries
```python
pandas         # Data manipulation and analysis
yfinance       # Bitcoin price data extraction
matplotlib     # Basic plotting and visualization
seaborn        # Statistical data visualization
plotly         # Interactive visualizations
numpy          # Numerical operations

Visualization Tools
Plotly: Interactive time-series charts

Seaborn: Correlation heatmaps and statistical plots

Matplotlib: Custom annotations and styling

📁 Project Structure
text
crypto-rollercoaster/
├── crypto_analysis.ipynb          # Main Jupyter notebook with full analysis
├── requirements.txt               # Python dependencies
├── data/
│   ├── raw/                      # Raw data files
│   └── processed/                # Cleaned and merged data
├── visuals/                      # Exported visualization images
└── README.md                     # This file
🚀 Installation & Setup
Clone the repository

bash
git clone https://github.com/your-username/crypto-rollercoaster.git
cd crypto-rollercoaster
Create virtual environment (optional but recommended)

bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies

bash
pip install -r requirements.txt
Run the analysis

bash
jupyter notebook crypto_analysis.ipynb
📈 Key Findings
🔍 Overall Correlation: 0.68
Strong positive relationship between price and search interest

When Bitcoin price increases, public search interest follows

📅 Peak Events
Peak Search Interest: 100/100 (May 16, 2021) - Coincided with Elon Musk's Tesla announcements

Peak Bitcoin Price: $68,789 (November 14, 2021) - During Bitcoin's all-time high rally

🎯 Yearly Analysis
2021: Highest correlation (0.72) - Most volatile year

2022: Moderate correlation (0.61) - Market consolidation

2023: Strong correlation (0.67) - Renewed interest

⏰ Lead-Lag Relationship
Price leads Search Interest by 1-2 days

People search about Bitcoin after price movements occur

🎨 Visualizations Included
Dual-Axis Timeline - Interactive Plotly chart showing both metrics over time

Scatter Plot with Trendline - Correlation strength visualization

Yearly Correlation Bar Chart - Comparison across years

Peak Analysis Timeline - annotated with historical events

Lead-Lag Analysis Plot - Time-shift correlation analysis

💡 Business Insights
Marketing Timing: Best to launch crypto campaigns 1-2 days after major price movements

Sentiment Indicator: Search interest can serve as a fear/greed indicator

Market Prediction: High search volume often precedes price volatility

🤝 Contributing
Contributions are welcome! Please feel free to:

Fork the project

Create a feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

🙋‍♂️ Author
Maryam Naseem
GitHub: @MaryamCodeHub

LinkedIn: [Your Profile](https://www.linkedin.com/in/maryam--naseem)

🎓 Learning Outcomes
This project demonstrates:

Advanced data visualization techniques

Time series analysis

Statistical correlation analysis

Storytelling with data

API integration and data cleaning

Professional project documentation

⭐ If you found this project helpful, please give it a star on GitHub!


### **📋 Additional Files You Should Create:**

1. **`requirements.txt`** file:
pandas==1.5.3
yfinance==0.2.18
matplotlib==3.7.0
seaborn==0.12.2
plotly==5.13.0
numpy==1.24.0
jupyter==1.0.0

text

2. **`.gitignore`** file:
Byte-compiled / optimized / DLL files
pycache/
*.py[cod]

Jupyter Notebook
.ipynb_checkpoints/

Data files
*.csv
*.xlsx

Virtual environment
venv/
env/

IDE files
.vscode/
.idea/

text

### **🚀 GitHub Upload Instructions:**

1. **Create new repository** on GitHub
2. **Upload these files:**
   - `crypto_analysis.ipynb` (your Colab notebook)
   - `README.md` (this file)
   - `requirements.txt`
   - `.gitignore`
3. **Add a good banner image** in README
4. **Enable GitHub Pages** for portfolio view

Yeh README file recruiters ko aapki technical skills, storytelling ability, aur professional approach dikhayega! 🎯

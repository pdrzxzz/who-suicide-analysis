# WHO Suicide Analysis

An Exploratory Data Analysis (EDA) of the World Health Organization (WHO) suicide dataset.

## 📊 Project Overview

This project analyzes global suicide data to identify patterns, trends, and factors that may influence suicide rates across different countries, age groups, and demographics.

## 🚀 Quick Start

### Option 1: Google Colab (Recommended)
Simply upload the `who_suicides_analysis.ipynb` file to Google Colab and run it. All dependencies will be automatically installed.

### Option 2: Local Setup
If you want to run locally:

```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Option A: Use an IDE (Recommended)
# Open the project in VS Code, PyCharm, or your preferred IDE
# The notebook will work in any IDE that supports Jupyter notebooks

# Option B: Use Jupyter Notebook
jupyter notebook who_suicides_analysis.ipynb
```

## 📦 Dependencies

The project uses these libraries:
- **numpy** & **pandas**: Data manipulation and analysis
- **matplotlib** & **seaborn**: Data visualization
- **kagglehub**: Data source access

## 🎨 What i learned  

Data analysis is not about desscribing what you see in the plots, its explain why you plotted that, highlighting interesting patterns and raise questions.
It's about using external knowledge and research to form and back up hypotheses to explain patterns.
Useful websites for creating nice plots:
- [Python Graph Gallery](https://python-graph-gallery.com/)
- [Data to Viz](https://www.data-to-viz.com/)

## 📁 Project Structure
```
who-suicide-analysis/
├── who_suicides_analysis.ipynb  # Main analysis notebook
├── requirements.txt             # Python dependencies
└── README.md                    # This file
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

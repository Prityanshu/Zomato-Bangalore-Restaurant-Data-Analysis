# 🍽️ Zomato Bangalore Restaurant Data Analysis

A comprehensive data analysis and visualization project exploring restaurant trends, ratings, costs, and cuisines in Bangalore using the Zomato dataset. Built with Python, Jupyter Notebook, pandas, and seaborn.

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange.svg)
![pandas](https://img.shields.io/badge/pandas-v1.5+-purple.svg)
![seaborn](https://img.shields.io/badge/seaborn-v0.11+-teal.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 🌟 Features

- **📊 In-depth Data Cleaning**: Handles missing values, outliers, and inconsistent data
- **📈 Rich Visualizations**: Bar plots, box plots, and heatmaps for deep insights
- **🍲 Cuisine & Location Analysis**: Discover popular cuisines and restaurant hotspots
- **💸 Cost & Rating Trends**: Explore how cost and ratings vary by type and area
- **📂 Modular Notebook**: Well-organized, step-by-step Jupyter notebook
- **🗺️ Location-based Insights**: Analyze restaurant density and trends by Bangalore locality

## 🏗️ Project Structure

```
zomato-dataset/
├── assignment3.ipynb           # Main Jupyter notebook for analysis
├── zomato.csv                  # Main dataset (Bangalore restaurants)
├── location_Type.csv           # Supporting data: location vs. type
├── location_booktable.csv      # Supporting data: location vs. book table
├── location_online.csv         # Supporting data: location vs. online order
└── README.md                   # This file
```

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/zomato-dataset.git
   cd zomato-dataset
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv zomato_env
   # On Windows
   zomato_env\Scripts\activate
   # On macOS/Linux
   source zomato_env/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   # Or install manually:
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   # Or
   jupyter lab
   ```

5. **Open `assignment3.ipynb`** and run the cells step by step.

## 📊 Dataset

The analysis uses the Zomato Bangalore Restaurants dataset, containing over 50,000 records with features like:

- **name**: Restaurant name
- **online_order**: Online ordering availability
- **book_table**: Table booking availability
- **rate**: Aggregate rating
- **votes**: Number of votes
- **location**: Area/locality in Bangalore
- **rest_type**: Type of restaurant (e.g., Casual Dining, Cafe)
- **cuisines**: Cuisines offered
- **Cost2plates**: Approximate cost for two people
- **Type**: Service type (e.g., Buffet, Delivery)

## 📈 Analysis Highlights

- **Top Localities**: Find which areas have the most restaurants
- **Popular Cuisines**: Discover the most common cuisines in Bangalore
- **Cost vs. Rating**: Analyze how restaurant cost relates to ratings
- **Online Order & Table Booking**: Trends in online ordering and table booking
- **Restaurant Type Distribution**: See which types of restaurants dominate the city

## 🛠️ Technical Stack

- **Python 3.8+**
- **Jupyter Notebook**
- **pandas, numpy** (data processing)
- **matplotlib, seaborn** (visualization)

## 📋 Requirements

```txt
pandas>=1.5.0
numpy>=1.21.0
matplotlib>=3.5.0
seaborn>=0.11.0
jupyter
```

## 🔍 Key Steps Deep Dive

### Data Cleaning
- Remove duplicates and handle missing values
- Standardize cost and rating formats
- Group rare categories as 'others' for clarity

### Exploratory Data Analysis
- Visualize restaurant distribution by location and type
- Analyze rating and cost patterns
- Explore cuisine and service trends

### Visualization
- Bar plots for top locations, cuisines, and types
- Box plots for cost and rating distributions
- Heatmaps for correlation analysis

## 🚨 Notes & Limitations

- The analysis is based on historical Zomato data for Bangalore
- Data may not reflect current restaurant status or new openings
- All processing is local; no personal data is stored

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Author

- **Prityanshu Yadav** – *Developer & Maintainer*  
  [GitHub Profile](https://github.com/Prityanshu)

## 🙏 Acknowledgments

- Zomato for the dataset
- pandas and seaborn communities for excellent tools
- Open source community for inspiration

---

**⭐ If you found this project helpful, please give it a star!**

Made with ❤️ for data-driven food discovery. 


## here's the link to download the datasets
https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants

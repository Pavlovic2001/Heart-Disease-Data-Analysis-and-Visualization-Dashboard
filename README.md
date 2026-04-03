# Heart Disease Data Analysis and Visualization Dashboard

This project demonstrates a complete, end-to-end workflow for analyzing heart disease data from multiple clinical sources. It focuses on data cleaning, preprocessing, feature analysis, and interactive visualization.

The core of this project is a combination of Python-based data processing, SQL-based data management, and an interactive Power BI dashboard, providing insights into patient demographics, clinical indicators, and heart disease diagnosis.

## Technology Stack

-   **Backend & Data Processing**: Python, Pandas, NumPy  
-   **Database & Querying**: PostgreSQL, SQL  
-   **Visualization**: Power BI  

## Key Features

-   **Multi-Source Data Integration**: Combines datasets from the Cleveland Clinic Foundation and University Hospital Zurich.  
-   **Robust Data Cleaning & Preprocessing**: Cleans missing and inconsistent values using Python notebooks.  
-   **Feature Analysis**: Identifies the most important clinical features for heart disease diagnosis using machine learning techniques.  
-   **Interactive Dashboard**: Power BI dashboard visualizes patient demographics, clinical indicators, and comparisons between patients with and without heart disease.  

## File Structure
```bash
├── Analytics.ipynb       # Exploratory data analysis and feature insights
├── DeepCleaning.ipynb    # Data cleaning and preprocessing pipeline
├── Prediction.ipynb      # Machine learning models and feature importance
├── Heart.sql             # Database creation and heart disease tables
├── Load_table.sql        # Scripts to load cleaned data into PostgreSQL
└── README.md
 
```

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

-   Python 3.9+ (Recommended)  
-   PostgreSQL  
-   Power BI Desktop  

### Setup & Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/Pavlovic2001/heart-disease-analysis
    cd heart-disease-analysis
    ```

2.  **Create and activate a virtual environment:**
    ```sh
    # For Unix/macOS
    python3 -m venv venv
    source venv/bin/activate
    
    # For Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```

3.  **Install Python packages:**
    ```sh
    pip install -r
    ```

4.  **Database Setup:**
    - Run `Heart.sql` to create the database schema  
    - Run `Load_table.sql` to populate tables with cleaned data  

## Usage / Workflow

Run the notebooks **from the project root directory** in the following order:

1.  **Data Cleaning & Preprocessing:**
    ```sh
    # Open DeepCleaning.ipynb in Jupyter Notebook or VS Code
    ```

2.  **Exploratory Data Analysis:**
    ```sh
    # Open Analytics.ipynb to analyze patient demographics and feature distributions
    ```

3.  **Machine Learning & Prediction:**
    ```sh
    # Open Prediction.ipynb to train models and analyze feature importance
    ```

4.  **Interactive Dashboard:**
    - Open your Power BI dashboard to explore interactive visualizations of heart disease data.

## Workflow Overview

- Load and merge datasets from multiple clinical sources  
- Clean and preprocess clinical data using Python  
- Store and query data with PostgreSQL  
- Perform feature analysis and model building  
- Visualize insights using Power BI  

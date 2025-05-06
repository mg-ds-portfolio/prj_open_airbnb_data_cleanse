# Airbnb Data Cleansing Project

This project demonstrates basic data cleansing techniques using an open-source Airbnb dataset. The goal is to prepare the data for future analysis by handling missing values, standardizing formats, and identifying any inconsistencies.

## Overview

This project includes:
- Exploratory inspection of the dataset
- Cleaning and transformation of raw data
- Exporting a clean version of the dataset for analysis

## Key Actions
- Removed or imputed missing values
- Converted columns to appropriate data types
- Dropped duplicates and invalid entries

## Tools Used
- Python (pandas, numpy)
- Jupyter Notebook

## File Structure
```
notebooks/         # Jupyter notebook showing the data cleansing process
requirements.txt   # Python dependencies
README.md          # Project overview
data/              # Raw input (not included) and optional output files
```

## How to Use

1. Clone this repository:
   ```
   git clone https://github.com/mg-ds-portfolio/prj_open_airbnb_data_cleanse.git
   ```

2. Create and activate a virtual environment

   ```
   python -m venv venv
   source venv/bin/activate  # On Mac/Linux
   venv\Scripts\activate     # On Windows
   ```

3. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Open the notebook:
   - Navigate to the `notebooks/` folder:
      ```
      cd notebooks
      ```
   - Start the Jupyter server:
      ```
      jupyter notebook
      ```
      This command will launch a local web server and automatically open your default web browser showing the Jupyter interface. If the browser does not open automatically, copy the URL provided in the terminal (it will look something like `http://localhost:8888/?token=...`) and paste it into your browser.

   - In your browser, click on the relevant `.ipynb` file to open it, then run each cell in order to reproduce the cleaning process.

## Data Source

This project uses data from Kaggle:[Airbnb Open Data on Kaggle](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)

(Note: Please download the dataset directly from Kaggle to comply with their usage terms.)

## License

The structure of the dataset is shared under the Open Database License.  
The contents are © the original authors and cannot be redistributed.  
To use the dataset, download it directly from [Kaggle](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)

# Python Final Project: Book Data Analysis
## Project Overview
This project is an analysis of book data using Python tools learned in Math 120. This project will explore trends and data analysis within book datasets.
## Project Structure
```
Math-120-Final-Project/
├── data/                 # Cleaned and processed data
│   └── books_data.csv    
├── data_raw/                    
│   ├── Book_Details.csv     # Raw book data
│   └── Books_Data.csv       # Raw book data with sales
├── Math120_Final.ipynb      # Main analysis notebook
└── README.md               # This file
```
## Requirements
- Python 3.7+
- pandas
- matplotlib
- numpy
- jupyter (for local execution)
## Installation and Setup
1. Clone this repository
```
git clone https://github.com/ireneher11/Math-120-Final-Project.git
cd Math-120-Final-Project
```
2. Install required packages (if needed):
```
pip install pandas matplotlib numpy jupyter
```
3. Launch Jupyter Notebook:
```
jupyter notebook notebook.ipynb
```
### Google Colab Execution
1. Open Google Colab
2. Upload the notebook.ipynb file or connect to your GitHub repository
3. Run the first cell to automatically set up the environment
## Data Description
- Books_Details: Contains book id, cover_img, book_title, book_description, forrmat, publication_info, authorlink, author, num_pages, num_ratings, num_reviews, and rating_distribution.
- Books_Data: Contains publishing year, book name, author, book_rating, book_average_rating, book_ratings_count, genre, publisher revenue, sale price, sales rank, publisher, and units sold.
## Analysis Features
- Loading the data
- Augumenting the dataset and then merging them into one
- Using charts for data visualization
- Using classes and methods to build functions for predicting genres
## Key Learning Objectives Demonstrated
- File I/O operations with pandas
- Data cleaning and preprocessing
- Data merging and joining
- data analysis
- Data visualization
- Function creation and modular programming
- Environment compatibility (local vs. cloud)
## Usage
Run all cells in Math120_Final.ipynb sequentially. The notebook will:

1. Set up the environment automatically
2. Load and clean the raw data
3. Save processed data to the data/ folder
4. Generate visualizations
5. Predict genre based on titles and summaries
## Author
Irene Her   
Math 120 - Fall 2025

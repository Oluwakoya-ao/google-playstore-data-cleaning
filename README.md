# 📱 Google Play Store Data Cleaning

This project focuses on cleaning and preparing a dataset of mobile applications from the Google Play Store. The goal is to make the dataset analysis-ready by handling missing values, correcting data types, and removing inconsistencies.

## 📂 Repository Structure

```
📁 google-playstore-data-cleaning/
│
├── Google_Playstore.ipynb     # Jupyter Notebook with cleaning steps
├── Google-Playstore.csv       # Original dataset 
└── README.md                  # Project documentation
```

## 🧹 Cleaning Objectives

- Handle missing values  
- Correct data types  
- Clean string formatting issues (e.g., price, installs)  
- Remove duplicates and outliers  
- Prepare the dataset for further analysis or visualization  

## 📊 Dataset Summary

The dataset includes app metadata such as:

- App Name  
- Category  
- Rating  
- Number of Installs  
- Price  
- Size  
- Last Updated  
- Content Rating  
- And more...

## 🛠️ Tools Used

- Python  
- Pandas  
- NumPy  
- Regex  
- Jupyter Notebook  

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/oluwakoya-ao/google-playstore-data-cleaning.git
   ```

2. Navigate into the project folder:

   ```bash
   cd google-playstore-data-cleaning
   ```

3. Open the notebook in Jupyter:

   ```bash
   jupyter notebook Google_Playstore.ipynb
   ```

4. Run each cell to see the data cleaning process.

## 📌 Key Takeaways

- The raw dataset contained inconsistencies such as:
  - Commas and symbols in numeric fields (e.g., "1,000+", "$4.99")
  - Missing values across several columns
  - Duplicated entries
- These issues were resolved through:
  - Type conversion
  - Regex-based cleaning
  - Null value handling
  - Deduplication
- The cleaned dataset is now ready for exploration, analysis, or modeling.

## 📸 Suggested Improvements

Optional additions to enhance this project:

- Add visual summaries of missing data using `seaborn` or `missingno`
- Include before/after samples of cleaned fields
- Export and include the final cleaned CSV dataset

## 🙌 Acknowledgments

Dataset sourced from Kaggle: [Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

## 👨‍💻 Author

**Oluwakoya Oluwafemi**  
📧 ooluwakoyafavour@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/oluwakoya/)

---

Feel free to fork, star, or contribute to this project!



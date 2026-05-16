# 🚀 Smartphone Market ETL Pipeline & Smart Deal Analyzer

An end-to-end Data Engineering and Machine Learning project focused on automated data acquisition, rigorous data transformation, and predictive modeling to identify fair market value and flag undervalued smartphone deals in real-time.

---

## 🎥 Project Demo (Video)
See the full workflow and interface in action:  
👉 **[Click Here to Watch the Project Demo Video](https://drive.google.com/open?id=1A0HIHfEJy_fE8SMa6d5W8vYOfglf2jbf&usp=drive_fs)** *(Replace this with your Google Drive or YouTube video link)*

---

## 🛠️ Project Architecture & Features

### 1. Data Acquisition (Extraction)
- Built automated web scrapers using `BeautifulSoup` and `Selenium`.
- Harvested live, unstructured market data (pricing, device specifications, item conditions) from various online platforms.

### 2. Data Transformation & Cleaning
- Handled missing values, normalized text formats, and removed duplicates using `Pandas`.
- Performed detailed feature engineering, including extracting storage capacities, categorizing brand tiers, and standardizing item conditions (e.g., Refurbished, Excellent, Good).

### 3. Predictive Modeling
- Implemented and trained a Machine Learning model (`Random Forest Regressor`) to predict the "Fair Market Value" of smartphones based on their specific features.

### 4. Smart Deal Analyzer (Interface)
- Developed an interactive predictor dashboard.
- Users can input or select specific smartphone specifications, and the system instantly evaluates the retail price to flag whether it is a **Good Deal**, **Fair Deal**, or **Overpriced**.

---

## 💻 Tech Stack Used
- **Language:** Python 🐍
- **Libraries:** Pandas, NumPy, Scikit-Learn, BeautifulSoup, Selenium
- **Environment:** Jupyter Notebook / Google Colab

---

## 🎓 Acknowledgments
Special thanks to **Dr. [Insert Dr Name]** and our teaching assistants **[Insert TA Name]** for their continuous guidance, support, and mentorship throughout the duration of this project.

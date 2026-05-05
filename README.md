# 📊 Instagram Engagement Analysis & Strategy

## 🔍 Overview

This project analyzes Instagram data to uncover patterns in user engagement, posting behavior, and follower growth. The goal is to identify **optimal posting strategies** and provide **data-driven recommendations** to improve engagement for *Alfido Tech*.

---

## 🎯 Objectives

* Identify the **best time and day to post**
* Analyze **content types driving higher engagement**
* Measure **engagement rate (likes + comments per follower)**
* Understand **follower growth trends**
* Provide actionable **business recommendations**

---

## 🛠️ Tech Stack

* **Python** (Pandas, NumPy)
* **Matplotlib** (Data Visualization)
* **SQLite** (Database Management)
* **Jupyter Notebook**

---

## 📁 Dataset

* Source:https://www.kaggle.com/datasets/bhanupratapbiswas/instgram
* Contains data on:

  * Users
  * Photos
  * Likes
  * Comments
  * Follows
  * Tags

---

## ⚙️ Data Processing Pipeline

1. Loaded multiple CSV files into Pandas DataFrames
2. Cleaned missing and inconsistent values
3. Converted date/time columns into proper datetime format
4. Standardized column names across datasets
5. Created relational database using SQLite:

   * Users
   * Photos
   * Likes
   * Comments
   * Follows
   * Interactions
6. Built a unified **interactions table** combining likes, comments, and follows

---

📁 Project Structure
instagram-engagement-analysis/
│
├── notebooks/
│   └── Instagram_Data_Analysis.ipynb
├── README.md                       
│
├── images/
│   ├── best_posting_hour.png
│   └── best_posting_day.png
|
├── data/
│   ├── users.csv
│   ├── photos.csv
│   ├── likes.csv
│   ├── comments.csv
│   ├── follows.csv
│   ├── tags.csv
│   └── photo_tags.csv                  
│
├── insta_lite.db                   

---

## 📈 Key Metrics

### 🔹 Engagement Rate

Engagement Rate = (Likes + Comments) / Followers

Used to measure how effectively content interacts with audience.

---

## 📊 Analysis & Visualizations

### 1. ⏰ Best Posting Time

* Engagement analyzed by **hour of the day**
* Identifies peak activity windows

### 2. 📅 Best Posting Day

* Engagement compared across all weekdays
* Highlights strongest performing days

### 3. 🖼️ Content Type Analysis

* Compared engagement across different content types
* Identified highest-performing formats

### 4. 📈 Follower Growth Trends

* Analyzed how follower count changes over time
* Helps identify growth spikes

---

## 🔍 Key Insights

* 📌 Engagement varies significantly based on **posting time**
* 📌 Certain days consistently outperform others
* 📌 Content type plays a major role in engagement levels
* 📌 Follower growth is influenced by posting consistency and interaction

---

## 🚀 Business Recommendations (For Alfido Tech)

### 1. Optimize Posting Time

Post during peak engagement hours identified in the analysis to maximize reach and visibility.

### 2. Focus on High-Performing Content

Increase production of content types that show higher engagement (e.g., visually appealing or filtered posts).

### 3. Use Hashtags Strategically

Avoid excessive hashtags; instead use a focused set of relevant and niche tags.

### 4. Maintain Consistent Posting Schedule

Post regularly on high-performing days to build audience expectation and algorithm trust.

### 5. Improve Audience Interaction

Engage with users through comments and calls-to-action to boost visibility and retention.

---

## ▶️ How to Run the Project

Follow these steps to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/instagram-engagement-analysis.git
cd instagram-engagement-analysis
```

---

### 2. Install Required Libraries

Make sure Python is installed (version 3.8+ recommended)

```bash
pip install pandas numpy matplotlib sqlite3
```

---

### 3. Add Dataset

* Download the dataset from Kaggle
* Place all `.csv` files inside the project folder (or `/content/` if using Google Colab)

---

### 4. Run the Notebook

#### 👉 Option A: Using Jupyter Notebook

```bash
jupyter notebook
```

* Open `Instagram_Analysis.ipynb`
* Run all cells step by step

#### 👉 Option B: Using Google Colab

* Upload the notebook to Colab
* Upload dataset files
* Run all cells

---

### 5. Output

* Graphs will be displayed:

  * Best Posting Hour
  * Best Posting Day
  * Content Type Performance
  * Follower Growth

* Console will print:

  * Best posting time
  * Best day
  * Best content type

---

## ⚠️ Important Notes

* Ensure dataset file names match expected names
* If graphs do not appear, add:

```python
%matplotlib inline
```

* Make sure date columns are correctly parsed

---

## 📦 Optional (Advanced)

To run via Python script:

```bash
python analysis.py
```

(Only if you convert notebook to script)


## 📊 Sample Outputs

<img width="763" height="606" alt="Screenshot 2026-05-05 205457" src="https://github.com/user-attachments/assets/17312080-6d70-45a5-bdc5-5e7a94399210" />
<img width="756" height="629" alt="Screenshot 2026-05-05 205522" src="https://github.com/user-attachments/assets/03938ba5-7d94-4020-8e4d-8983a27b0751" />


---

## 📌 Conclusion

This project demonstrates how data analysis can be used to transform raw social media data into actionable insights. By leveraging engagement metrics and behavioral patterns, businesses can significantly improve their online presence and audience interaction.

---

## 🔗 Future Improvements

* Build a **machine learning model** to predict engagement
* Create an **interactive dashboard (Power BI / Tableau)**
* Perform **sentiment analysis on comments**

---

## 👩‍💻 Author

Pratikshya Panda
B.Tech CSE Student

---

## 📜 License

This project is for educational and learning purposes.

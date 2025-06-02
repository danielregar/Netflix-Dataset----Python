 # 🎬 Netflix Movies & TV Shows EDA (2008 - 2021)

Welcome to my exploratory data analysis of Netflix’s library! Using Python and some popular visualization tools, I explored 7,789 titles from 2008 through mid-2021 to find interesting trends and insights.

---

## 📌 Dataset Overview

- **Source:** [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
- **Number of records:** 7,789  
- **Period covered:** 2008 to 2021  
- **Includes:** Title, Type, Director, Cast, Country, Date Added, Genre, Rating, and more  

---

## 🛠️ Tools & Libraries Used

- `pandas`  
- `matplotlib`  
- `seaborn`  
- `collections.Counter`  

---

## 🧹 Data Cleaning & Preparation

- Checked and handled missing values and duplicates  
- Converted `date_added` to datetime format  
- Created new columns like `year_added` and `month_added` for trend analysis  

---

## 📈 Key Findings

### Content Added by Year

2019 had the highest number of new titles added — over 2,000!

![image](https://github.com/user-attachments/assets/4add6292-14d5-4fcd-9caf-4949e726ad64)

---

### Content Added by Month

December is the most popular month for new releases, particularly in the fourth quarter.

![image](https://github.com/user-attachments/assets/8bc22604-f3cc-484c-9022-38122d3f491a)


---

### Movies vs. TV Shows Over Time

Movies outnumber TV shows consistently, as shown in stacked bar charts by year and month.

![image](https://github.com/user-attachments/assets/7eec418f-f155-41f8-8730-3a9dddda19df)
![image](https://github.com/user-attachments/assets/a66961f2-c5c9-44e2-9a40-8a4d6c868230)


---

### Top Contributing Countries

The United States leads as the top content provider. Some titles come from multiple countries, so splitting these was important(this also happens with the Cast and Director columns).![image](https://github.com/user-attachments/assets/667803fa-4e9f-46d2-ba0a-7ad36166205e)


![image](https://github.com/user-attachments/assets/8c9d9010-890a-4464-98db-90b8d6d2b51f)


---

### Directors and Cast Highlights

- **Top Director:** Jan Suter (~20 titles)  
- **Top Cast Member:** Anupam Kher (40+ titles)  

![image](https://github.com/user-attachments/assets/abfa343e-4663-41c1-9ad4-d8b9576b473b)
![image](https://github.com/user-attachments/assets/9e524c3a-c255-4a58-913d-4fb8ceb5fcad)


---

### Ratings & Genres

- Most common rating: **TV-MA (Mature Audience)** with 2,500+ titles  
- Top genre: **International Movies** 

![image](https://github.com/user-attachments/assets/e6e20ecf-c76a-496d-9734-2425a468c4b8)
![image](https://github.com/user-attachments/assets/89ce6d1c-917a-4160-841d-d06743d7e251)


---

## 💡 Conclusion

This analysis gives a clear picture of how Netflix’s content strategy has grown — more titles, global diversity, and a focus on mature and international content.

---

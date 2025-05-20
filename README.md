
# 🌍 Global Cost vs Value of Higher Education 

**Author:** Fahad Bin Gias

---

## 🎯 Project Objective

This project explores the **true cost and ROI (return on investment)** of international higher education by analyzing 900+ programs across 40+ countries. It aims to help students, institutions, and advisors make **data-driven decisions** based on value — not just prestige.

---

## 📦 Datasets Used

| Dataset | Description | Key Fields |
|---------|-------------|-------------|
| [Cost of Education](https://www.kaggle.com/datasets/adilshamim8/cost-of-international-education) | Tuition, living, visa, and insurance costs  | Country, City, Program, Tuition, Rent, Duration |
| [QS Rankings (2024)](https://www.kaggle.com/datasets/joebeachcapital/qs-world-university-rankings-2024) | Global university rankings | University, Country, QS Rank, QS Tier |
| [Salary Dataset](https://www.kaggle.com/datasets/zedataweaver/global-salary-data/code) | Average annual income by country | Country, Avg_Income_USD |

---

## 🛠 Features Engineered

- **Total Cost (USD)** = Tuition + Rent + Insurance + Visa  
- **Cost-to-Income ROI** = Total Cost / Avg Annual Income  
- **QS Tier Groupings**: Top 100, 101–300, 301–600, 600+  
- **Tuition-Free Flag**  
- **Regional Classification & KMeans Clustering**

---

## 📊 Key Insights

- **Prestige comes at a premium** — Top 100 schools are the costliest, but not always the fastest ROI
- **Top ROI Tier**: QS Rank 301–600 schools show fastest cost recovery  
- **South Asian institutions (Bangladesh & India)** offer globally ranked programs under $20K  
- **3-Year Bachelor's** and **funded PhDs** outperform 4-Year Bachelor's in ROI  
- **Best tech ROI fields**: Data Engineering, Robotics, and Computer Engineering

---

## 📈 Dashboard Access

🔗 [Explore the Interactive Dashboard (Looker Studio)](https://lookerstudio.google.com/reporting/2709d58a-8fbc-4406-9b1f-ef07b1ca191c/page/p_akfpwnmmsd)

Use filters to explore programs by:
- Country
- Degree Level
- QS Rank Tier
- ROI < 2 years
- Tuition-Free Programs

---

## 🗂️ Project Files

- 📊 `DATA_Caps.pptx`: Final presentation
- 📓 `global-edu-roi-analysis.ipynb`: Jupyter Notebook
- 📁 `education_roi_looker.csv`: Dashboard-ready dataset
- 🗒️ `Capstone_Speaker_Notes.txt`: Slide-by-slide presentation notes

---

## 📬 Contact

For feedback or collaboration:  
🔗 [LinkedIn](https://linkedin.com/in/fahadbingias)  
💻 [GitHub](https://github.com/fahadbgias)

---

## 📌 Future Work

- Integrate salary data by field of study  
- Estimate breakeven time based on post-grad migration or earning path  
- Expand scope to include business, law, and liberal arts disciplines

---

## 📄 License

MIT License — feel free to reuse or build upon this project with attribution.

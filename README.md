# 📊 Website Data Analysis (Python EDA)

This project performs **Exploratory Data Analysis (EDA)** on website traffic and engagement data using **Python**.  
The goal is to uncover insights into user behavior, sessions, engagement, and channel performance.  

---

## 🚀 Project Overview
- Analyzed website dataset containing metrics like:
  - **Users**
  - **Sessions**
  - **Engaged Sessions**
  - **Engagement Rate**
  - **Average Engagement Time per Session**
  - **Event Count**
  - **Channel Group**
  - **DateHour**
- Explored trends over time, user engagement patterns, and traffic sources.
- Visualized data with **Seaborn** and **Matplotlib** for better storytelling.

---

## 📂 Dataset
The dataset includes website performance metrics exported from analytics tools.  
Each row represents activity grouped by **channel** and **time (DateHour)**.

| Column Name                          | Description |
|--------------------------------------|-------------|
| Channel_Group                        | Source/medium of website traffic |
| DateHour                             | Timestamp (date & hour) |
| Users                                | Number of users |
| Sessions                             | Number of sessions |
| Engaged sessions                     | Sessions with user interaction |
| Average engagement time per session  | Avg. active time per session |
| Engaged sessions per user            | Engagement intensity |
| Events per session                   | Events triggered in each session |
| Engagement rate                      | Percentage of engaged sessions |
| Event count                          | Total events |

---

## 🛠️ Tools & Libraries
- **Python 3**
- **Pandas** – Data cleaning & transformation
- **Matplotlib** – Visualization
- **Seaborn** – Advanced plotting
- **Jupyter Notebook** – Interactive analysis

---

## 📊 Key Analysis & Visualizations
- **Time Series Analysis** → Users & Sessions over DateHour  
- **Channel Performance** → Total Users & Engagement by Channel Group  
- **Engagement Insights** → Avg. engagement time & events per session  
- **Distribution Analysis** → Box plots of engagement rate  
- **Correlation Heatmap** → Relationship between metrics  

Example Plots:
- Line graph of **Users vs Sessions over time**  
- Bar chart of **Users by Channel Group**  
- Box plot of **Engagement Rate** by Channel Group  
- Correlation **Heatmap** of website metrics

📈 Results & Insights

Identified top-performing traffic channels driving maximum users.

Found that engagement varies strongly by channel group.

Time-series analysis showed peak activity hours.

Correlation revealed strong links between Sessions, Users, and Events.

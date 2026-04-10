# 📊 Learning from GitHub Data: Insights from Top Repositories

## 📌 Overview
This project explores top GitHub repositories to uncover patterns in popularity, usage, and development trends using exploratory data analysis (EDA).

Instead of focusing on building predictive models, the goal is to learn directly from data—understanding relationships, extracting insights, and discovering what makes projects successful on GitHub.

## 💡 Project Idea
Working with GitHub data can be challenging, but it also offers an opportunity to learn from real-world developer activity.

This project focuses on:
- Understanding data rather than just processing it
- Extracting meaningful insights
- Using data as a learning tool, not just a step in a pipeline

## 📂 Dataset
We used a dataset of top GitHub repositories, which includes metrics such as:
- Stars
- Forks
- Repository age
- Open issues
- Programming domains

Dataset:
https://www.kaggle.com/datasets/muhammadaqeelkabir/top-github-repositories

Notebook:
https://colab.research.google.com/drive/1kSDQjvm7oL9mnL3yDnZU_rkXN7raNn2t#scrollTo=MqbmwX91RpnP

## 🔍 Key Analyses & Insights

### 1. Stars vs Forks
- Stars indicate popularity and appreciation
- Forks indicate usage and contribution

Insight:
Projects with more stars tend to have more forks, suggesting that popularity often leads to wider adoption and influence.

### 2. Correlation Between Metrics
We analyzed relationships between numerical features:

- Stars vs Forks: correlation ≈ 0.769 (strong positive)
  → Popular projects are also widely used

- Repository Age vs Open Issues: correlation ≈ 0.143 (weak positive)
  → Age alone does not strongly affect unresolved issues

Insight:
Correlation helps quantify relationships, but strong conclusions require context and interpretation.

### 3. User vs Organization Projects
- Many top repositories are owned by organizations
- Organization projects tend to have more stars and forks

Insight:
Team collaboration and resources contribute significantly to project success.

### 4. Projects by Domain
Most common domains include:
- Go, Rust, Python, C++
- Android & iOS
- DevOps & Web Development
- Machine Learning & Data Science
- Blockchain & Cybersecurity

Insight:
Modern development focuses heavily on systems programming, mobile apps, and AI-related fields.

### 5. Average Stars per Domain
- AI (Machine Learning & Deep Learning) and Data Science projects receive higher average stars

Insight:
These domains are not only active but also attract strong community interest.

### 6. Time-Based Analysis
- Many successful repositories were created in recent years
- Older repositories remain relevant if actively maintained

Insight:
Project success depends more on continuous activity and updates than age alone.

## 🛠️ Tools Used
- Python → core programming language
- Pandas → data manipulation and analysis
- Matplotlib & Seaborn → data visualization

## 🚀 How to Run

1. Clone the repository:
git clone <your-repo-link>

2. Install required libraries:
pip install pandas matplotlib seaborn

3. Open the notebook:
- Run locally with Jupyter Notebook
- Or use the provided Google Colab link

## 🎯 Conclusion
This project demonstrates that data is more than just input for models—it is a source of knowledge.

By analyzing GitHub repositories, we learned:
- What drives project popularity
- How collaboration impacts success
- Which domains are trending
- Why maintenance matters over time

## 📎 Final Note
This project is a step toward developing a deeper understanding of data—not just as numbers, but as a way to explore real-world behavior and trends.

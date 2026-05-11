# People say they hate Crocs. But they keep buying them. 🐊
**An Analytical Deep Dive into The Crocs Paradox: Sentiment vs. Sales**

[![Read the Blog](https://img.shields.io/badge/Read_the_Blog-PDF-red.svg)](./[你的PDF文件名].pdf)

## 📌 Project Overview
Crocs has long been criticized as one of the most controversial products in fashion. Online discussions are often filled with skepticism and mockery. Yet, many of their collaborations resell at prices significantly above retail. 

This project explores the "Crocs Paradox" by bridging the gap between social media sentiment and market value. We investigate whether negative public sentiment actually harms sales, or if the sheer volume of attention and discussion outweighs universal approval in today's attention economy.

## 📊 Methodology & Tech Stack
To quantify how people actually feel about Crocs collaborations and connect online opinions with resale performance, our team utilized the following approach:
* **Data Collection:** Scraped public discussions from Reddit (e.g., `r/crocs`, `r/Sneakers`, `r/streetwear`) using the **Reddit JSON search API**.
* **Sentiment Analysis:** Applied the **VADER** sentiment model to assign polarity scores (-1 to +1) to user comments.
* **Statistical Modeling:** Conducted regression analysis and constructed a Mediation Path (Baron & Kenny) to evaluate the relationship between Sentiment Score, Discussion Volume (Log of Comment Count), and Resale Premium Ratio.

## 💡 Key Findings
1. **The Overhype Penalty:** Products with widespread positive sentiment often signal accessibility, which can reduce the perception of scarcity and lower resale premiums.
2. **Controversy Drives Visibility:** Items with lower sentiment scores generated significantly higher levels of discussion and engagement.
3. **Attention Sells More Than Approval:** Discussion volume acts as a critical mediator. Algorithms prioritize high-interaction content, meaning controversial products gain more exposure. Consumers often buy what they see most, rather than what they like most.

## 📖 Read the Full Blog
We have compiled our research, data visualizations, and full insights into a comprehensive blog post. 

👉 **[Click here to read the full PDF blog](./[你的PDF文件名].pdf)**

*(Note: Replace the link above with the actual relative path to your PDF file in this repository)*

## 👥 Project Team
This analysis was a collaborative effort by our team:
* **Xinyan Jiang:** [你的具体负责部分，例如：Data visualization, regression modeling, and sentiment tracking]
* **Sahithi:** [她的具体负责部分，例如：Reddit API data collection and text mining]
* **[组员3姓名]:** [其负责部分，例如：Market research and editorial writing]
* **[组员4姓名]:** [其负责部分]

---
*If you find this analysis interesting, feel free to connect with us on LinkedIn or reach out for further discussion on data analytics and consumer behavior!*

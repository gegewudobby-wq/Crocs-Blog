# People say they hate Crocs. But they keep buying them. 🐊
**An Analytical Deep Dive into The Crocs Paradox: Sentiment vs. Sales**

[![Read the Blog](https://img.shields.io/badge/Read_the_Blog-PDF-red.svg)](https://gegewudobby-wq.github.io/Crocs-Blog/crocs%20blog.pdf)

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

👉 **[Click here to read the full PDF blog](https://gegewudobby-wq.github.io/Crocs-Blog/crocs%20blog.pdf)**

## 👥 Project Team
We are students from the Master of Science in Business Analytics (MSBA) program at the University of Illinois Urbana-Champaign (UIUC).

* **Xinyan Jiang**
* **Jinyi Li**
* **Linyao Gao**
* **Zhuoru Chen**

---
*Feel free to reach out for further discussion on data analytics and consumer behavior!*

<h1 align="center">🏆🏅 UN Youth Hacakthon 2022 Submission 🤾‍♂️</h1>
<p align="center">by <b>Team Mayo 🇮🇩</b></p><br>
<p align="center">
  <img src="https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=If%20Useful&style=style=flat&color=BC4E99" alt="Star Badge"/>
  <a href="https://www.github.com/caesarmario">
    <img src="https://img.shields.io/github/followers/caesarmario?style=social&link=https://www.github.com/caesarmario" alt"GitHub"/>
  </a>
  <a href="https://linktr.ee/caesarmario_">
    <img src="https://img.shields.io/badge/Follow%20My%20Other%20Works-019875?style=flat&labelColor=019875&link=https:/linktr.ee/caesarmario_" alt="Linktree"/>
  </a>
</p><br>

## 👥 Team Members
<p align="center"><img src="https://i.imgur.com/3iy542Y.png" width="70%"></p>
<ul>
  <li>Mario Caesar - [<a href="https://www.linkedin.com/in/caesarmario/">LinkedIn</a>]</li>
  <li>Timotius Marselo - [<a href="https://www.linkedin.com/in/timotius-marselo/">LinkedIn</a>]</li>
  <li>Yoel - [<a href="https://www.linkedin.com/in/yoel-yoel/">LinkedIn</a>]</li>
</ul>

## 📃 Table of Contents:
  - [Team Members](#-team-members)
  - [TOC](#-table-of-contents)
  - [About Repository](#-about-repository)
  - [Project Background](#-project-background)
  - [Datasets](#-datasets)
  - [Model Results](#-model-results)
    - [Summary of Model 1](#-summary-of-gaussian-naive-bayes)
    - [Summary of Model 2](#-summary-of-xgboost)

## 🖋 About Repository:
👉 This repository is the **Mayo team's submission of answers for the UN Youth Hackathon 2022**. This repository includes **Jupyter notebooks, presentation files, and raw & cleaned datasets**. The topic is the **rise of food & energy prices that affect poverty and hunger in Malawi**.

## 🧐 Project Background
> Malawi is one of the world's least developed countries and is ranked 174 out of 189 countries according to the 2020 Human Development Index. It has about 16 million people, 53% living under the national poverty line and 90% living on less than $2 per day. Some of Malawi's main challenges are low economic growth and also commodity price increase. The increase in food prices and energy prices will determine Malawi’s food insecurities and livelihood. This project hopes to help alleviate some of Malawi's challenges, by classifying and ranking Malawi's cities based on their food insecurity level, in hope that government can prioritize the city with the most severe food insecurity level.

## 📄 Datasets
- [Food Prices data for Malawi](https://data.humdata.org/dataset/wfp-food-prices-for-malawi)
- Malawi Integrated Household Panel Survey 2010 2013 2016 2019 (Long Term Panel, 102 EAs) from **World Bank Microdata Library**

## 👀 Model Results
👉 After going through the **data preprocessing, EDA, and feature selection**, the cleaned dataset will be entered into **two machine learning models**, which are **gaussian naive Bayes and XGBoost**.

### ▶ Summary of Gaussian Naive Bayes
<p align="center"><img src="https://i.imgur.com/GV4ou0u.png" width="50%"></p>
<ul>
  <li>GaussianNB model has a recall of 0.796 and precision of 0.583 for the food insecure class. This means out of the 1448 food insecure households, the model have predicted 79.6% of them as food insecure ; and out of the 1977 households predicted as insecure, 58.3% of the households are truly food insecure.</li>
  <li>The ROC AUC for food insecure class is 0.71 which means the diagnostic ability of the model is acceptable.</li>
</ul>

### ▶ Summary of XGBoost
<p align="center"><img src="https://i.imgur.com/VG11u78.png" width="50%"></p>
<ul>
  <li>XGBoost model has a recall of 0.694 and precision of 0.585 for the food insecure class. This means out of the 1448 food insecure households, the model have predicted 69.4% of them as food insecure; and out of the 1719 households predicted as insecure, 58.5% of the households are truly food insecure.</li>
  <li>The ROC AUC for food insecure class is 0.69 which means the diagnostic ability of the model is acceptable.</li>
</ul>

<br><p align="center"><img src="https://i.imgur.com/Sf9pt30.png" width="70%"><br><i>Food Insecurity Ranking from Two Models</i></p>

---

## 🙌 Support Us!
👉 If you find this project useful, **please ⭐ this repository 😆**!


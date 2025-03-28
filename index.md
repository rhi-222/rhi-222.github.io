---
title: Portfolio
---
<style>
  /* ---------- Global ---------- */
  body {
    background-color: #FAF5E9;
    color: #374040;
    font-family: 'Open Sans', sans-serif;
    padding: 1rem;
  }

  h1, h2, h3, h4, h5, h6 {
    font-family: 'Open Sans', sans-serif;
    font-weight: 530;
    color: #374040;
  }

  /* ---------- Main content width (no overlap!) ---------- */
  .page {
    max-width: auto;
    margin: auto;
    padding: 0rem;
  }

  /* ---------- Link style ---------- */
  a {
    color: #748A80; /* Forest green */
    text-decoration: none;
    font-weight: bold;
  }

  a:hover {
    color: #3D4844;
    text-decoration: none;
  }

  /* ---------- Buttons ---------- */
  .custom-button {
    padding: 10px 20px;
    font-size: 15px;
    margin: 6px;
    border-radius: 8px;
    border: 0px solid #374040;
    cursor: pointer;
    font-weight: 500;
    transition: all 0.2s ease-in-out;
    display: inline-block;
    text-align: center;
  }

  /* Button color classes */
  .btn-green     { background-color: #D2E0D4; color: #2A3030; }
  .btn-pink      { background-color: #EED8C8; color: #2A3030; }
  .btn-paper     { background-color: #F2EEE3; color: #2A3030; }
  .btn-orange    { background-color: #F3AC6F; color: #2A3030; }
  .btn-yellow    { background-color: #D2D2AE; color: #2A3030; }
  .btn-darkgreen { background-color: #748A80; color: #F2EEE3; }

  .custom-button:hover {
    transform: scale(1.00);
    filter: brightness(1.07);
  }
</style>

<div style="display: flex; justify-content: center; flex-wrap: wrap; gap: 0px; margin-top: 2rem;">
  <a href="/diaries">
    <button class="custom-button btn-yellow">My Data Diaries</button>
  </a>
  <a href="/projects">
    <button class="custom-button btn-orange">My TripleTen Projects</button>
  </a>
</div>
---

# Hi, I’m Rhi 👩🏻‍💻✨

I’m an aspiring data scientist with the heart of a visionary and the mind of a scientist.

Currently completing a data science bootcamp with **Triple Ten**. I’m building a portfolio that blends **environmental science, astronomy, and research-driven exploration**—fields where I believe data has the power to uncover meaning, tell better stories, and drive responsible innovation.

I’m especially drawn to projects that combine data with purpose, whether that’s tracking climate change, mapping the cosmos, or making complex patterns easier to understand.

---

## About Me

- 🖥️ **Core Skills**: Python (Pandas, NumPy, Matplotlib, Seaborn), SQL, Machine Learning (Supervised & Unsupervised), Deep Learning (CNNs), Data Visualization  
- 📊 **Focus**: Data Science & Predictive Modeling  
- 🌱 **Currently Exploring**: Computer Vision, Time Series Forecasting, and NLP  
- 📍 **Location**: San Antonio, TX

---

## Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-f7931e?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-ff6f00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-00758f?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>

---

## Featured Projects

- [📡 Telecom Churn Prediction](https://github.com/rhi-222/telecom-churn-prediction)  
  Built predictive models to identify high-risk customers, achieving an **AUC-ROC score of 0.85**.

- [🧑‍🎨 Human Age Prediction (Deep Learning)](https://github.com/rhi-222/human-age-prediction)  
  Trained a **CNN model** for age estimation with an **MAE of 7.1 years**.
  
- [🎮 What Makes a Video Game a Best-Seller? (Project Article)](https://lying-nymphea-848.notion.site/What-Makes-a-Video-Game-a-Best-Seller-A-Data-Science-Investigation-1ab2aee0caf980a4bf12d30e25e51a86?pvs=4)  
  Key insights from EDA and hypothesis testing on what drives commercial success in the gaming industry.
  
<div style="text-align: center; margin-top: 1rem;">
  <a href="/projects">
    <button class="custom-button btn-orange">↳ View All TripleTen Projects</button>
  </a>
</div>

---

## Recent Data Diaries

These are my latest reflections as I grow into the data scientist I’m becoming.

<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <strong>{{ post.date | date: "%B %d, %Y" }}</strong> – 
      <a href="{{ post.url }}">{{ post.title }}</a>  
      <br>
      <em>{{ post.excerpt | strip_html | truncate: 100 }}</em>
    </li>
  {% endfor %}
</ul>

<div style="text-align: center; margin-top: 1rem;">
  <a href="/diaries">
    <button class="custom-button btn-yellow">↳ Explore All Posts</button>
  </a>
</div>

---

## Let’s Connect!

<div style="display: flex; justify-content: center; flex-wrap: wrap; gap: 0px; margin-bottom: 0rem;">
  <a href="mailto:rhiannon.filli@gmail.com" target="_blank">
    <button class="custom-button btn-pink">Email Me</button>
  </a>
  <a href="https://www.linkedin.com/in/rhiannonfilli" target="_blank">
    <button class="custom-button btn-green">LinkedIn</button>
  </a>
</div>
<div style="text-align: center;">
  <a href="/rhi_resume.pdf" download>
    <button class="custom-button btn-darkgreen">Download My Resume</button>
  </a>
</div>

---

![Rhi's GitHub stats](https://github-readme-stats.vercel.app/api?username=rhi-222&show_icons=true&theme=calm&hide=prs&hide_border=true)

---


_Thanks for visiting – I’m open to new opportunities and discoveries._ 

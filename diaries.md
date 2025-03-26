---
title: Data Diaries
---
<style>
  .diary-post {
    background-color: #FAF7EF;
    padding: 1.2rem;
    border-radius: 10px;
    margin-bottom: 1rem;
    box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  }
  .diary-post h3 {
    margin: 0;
    font-size: 1.1rem;
  }
  .diary-post p {
    margin: 0.4rem 0 0;
    font-size: 0.95rem;
    color: #4A4A4A;
  }
  /* ---------- Global ---------- */
  body {
    background-color: #FAF5E9;
    color: #374040;
    font-family: 'Open Sans', sans-serif;
    padding: 1rem;
  }

  h1, h2, h3, h4, h5, h6 {
    font-family: 'Open Sans', sans-serif;
    font-weight: 500;
    color: #374040;
  }
  /* ---------- Main content width (no overlap!) ---------- */
  .page {
    max-width: auto;
    margin: auto;
    padding: 1rem;
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
</style>

<p align="center">
  <a href="/" class="nav-link">← Back to Home</a>
</p>

---

# Data Diaries 📓

Reflections on my journey as an aspiring data scientist—what I’m learning, building, and discovering along the way.

{% for post in site.posts %}
<div class="diary-post">
  <h3>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </h3>
  <p><em>{{ post.date | date: "%B %d, %Y" }}</em></p>
  <p>{{ post.excerpt | strip_html | truncate: 100 }}</p>
</div>
{% endfor %}

---

<p align="center">
  <a href="/" class="nav-link">← Back to Home</a>
</p>

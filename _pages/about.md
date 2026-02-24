---
layout: single
permalink: /
title: "Ling Zhang"
author_profile: false
classes: wide
---

<style>
  /* 1. Hide the default page title */
  .page__title { display: none !important; }

  /* 2. Container and Text Alignment */
  .profile-container {
    display: flex;
    align-items: center;
    margin-bottom: 25px;
  }

  .profile-text {
    display: flex;
    flex-direction: column;
    justify-content: center; /* Vertically centers the text against the photo */
    height: 100px; /* Matches your 100px image height */
    line-height: 1.2;
  }

  /* 3. Color Logic for Day/Night Mode */
  .profile-name {
    margin: 0; 
    padding: 0; 
    border: none; 
    font-size: 1.4em; 
    color: #000000; /* Default black for Day mode */
  }

  .profile-title {
    font-size: 0.95em; 
    font-weight: 600; 
    color: #333333; /* Dark grey for Day mode */
  }

  /* Automatically switch colors if the user is in Dark Mode */
  @media (prefers-color-scheme: dark) {
    .profile-name { color: #ffffff !important; }
    .profile-title { color: #eeeeee !important; }
    .profile-links a { color: #4fb3ff !important; }
  }

  /* 4. Link Styling */
  .profile-links {
    font-size: 0.85em;
    margin-top: 5px;
  }
  .profile-links a {
    margin-right: 12px;
    text-decoration: none;
  }
</style>

<div class="profile-container">
  <img src="/images/profile.png" style="width: 100px; height: 100px; border-radius: 50%; margin-right: 20px; object-fit: cover; border: 1px solid #eee;">
  
  <div class="profile-text">
    <h2 class="profile-name">Ling Zhang</h2>
    
    <div class="profile-title">
      Senior Researcher at Microsoft Research Asia
    </div>

    <div class="profile-links">
      <a href="mailto:zhangling@microsoft.com">
        <i class="fas fa-fw fa-envelope"></i> Email
      </a>
      <a href="https://scholar.google.com/citations?user=JzRpUcMAAAAJ" target="_blank" rel="noopener noreferrer">
        <i class="fas fa-fw fa-graduation-cap"></i> Scholar
      </a>
      <a href="/files/my_cv.pdf" target="_blank" rel="noopener noreferrer" class="btn btn--info" style="margin: 0; padding: 2px 8px; font-size: 0.8em; border-radius: 4px; color: white !important;">
        Download CV
      </a>
    </div>
  </div>
</div>

<hr>

# About Me
Write your professional biography here.

# Research Interests
* **Artificial Intelligence**
* **Machine Learning**

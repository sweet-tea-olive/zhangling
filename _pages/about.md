---
layout: single
permalink: /
title: "Ling Zhang"
author_profile: false
classes: wide
---

<style>
  /* 1. Hide the default large title */
  .page__title { display: none !important; }

  /* 2. Standard Colors (Light Mode) */
  :root {
    --profile-name: #000000;
    --profile-title: #333333;
    --profile-research: #666666;
    --profile-link: #003366;
  }

  /* 3. Dark Mode Colors (Automatically detects system/browser theme) */
  @media (prefers-color-scheme: dark) {
    :root {
      --profile-name: #ffffff;
      --profile-title: #eeeeee;
      --profile-research: #bbbbbb;
      --profile-link: #4fb3ff;
    }
  }

  /* 4. Layout Tweak: Match text height to 100px photo */
  .profile-container {
    display: flex;
    align-items: center;
    margin-bottom: 30px;
    line-height: 1.2; /* Tightens spacing between lines */
  }

  .profile-text {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100px; /* Forces text container to match photo height */
  }
</style>

<div class="profile-container">
  <!-- Profile Photo (100px) -->
  <img src="/images/profile.png" style="width: 100px; height: 100px; border-radius: 50%; margin-right: 20px; object-fit: cover; border: 1px solid #eee;">
  
  <div class="profile-text">
    <!-- Name: Smaller font (1.4em) -->
    <h2 style="margin: 0; padding: 0; border: none; font-size: 1.4em; color: var(--profile-name);">Ling Zhang</h2>
    
    <!-- Job Title: Small and Bold -->
    <div style="font-size: 0.95em; font-weight: 600; color: var(--profile-title);">
      Senior Researcher at Microsoft Research Asia
    </div>
    

    <!-- Contact Links & CV Button -->
    <div style="font-size: 0.85em;">
      <a href="mailto:your-email@microsoft.com" style="margin-right: 12px; color: var(--profile-link); text-decoration: none;">
        <i class="fas fa-fw fa-envelope"></i> Email
      </a>
      <a href="https://scholar.google.com" style="margin-right: 12px; color: var(--profile-link); text-decoration: none;">
        <i class="fas fa-fw fa-graduation-cap"></i> Scholar
      </a>
      <a href="/files/my_cv.pdf" class="btn btn--info" style="margin: 0; padding: 2px 8px; font-size: 0.8em; border-radius: 4px;">
        Download CV
      </a>
    </div>
  </div>
</div>

<hr>

# About Me
Write your professional biography here...

# Research Interests
* **Artificial Intelligence**
* **Machine Learning**

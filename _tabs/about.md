---
layout: page
title: About
icon: fas fa-info-circle
order: 1
---

<div class="about-hero">
  <h1 class="display-title">👋 Hi, I'm Sohaib Maan</h1>
  <p class="hero-subtitle">Machine Learning Enthusiast</p>
  <blockquote>
    "Dedicated to turning raw data into intelligent insights and building predictive models for real-world impact."
  </blockquote>
</div>

## 🤖 Tech Stack & Tools
<div class="skills-grid">
  <div class="skill-item python"><i class="fab fa-python"></i> Python <span>(Scikit-Learn, Pandas)</span></div>
  <div class="skill-item csharp"><i class="fas fa-code"></i> C# <span>(.NET / ML.NET)</span></div>
  <div class="skill-item sql"><i class="fas fa-database"></i> MySQL <span>(Data Engineering)</span></div>
  <div class="skill-item web"><i class="fab fa-html5"></i> Web <span>(HTML5 / CSS3)</span></div>
</div>

## 🎓 Education & Journey
I am currently a student at **UET Faisalabad**, bridging the gap between complex algorithms and user-friendly applications.

---



<style>
  /* --- Quantum Neon Overhaul --- */

  /* 1. Header with Radiant Gradient */
  .display-title {
    font-size: 3rem;
    font-weight: 900;
    background: linear-gradient(to right, #00d2ff, #92fe9d); /* Cyan to Lime */
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 0.2rem;
    letter-spacing: -1px;
  }

  .hero-subtitle {
    color: #22d3ee; /* Electric Cyan */
    font-family: 'Courier New', monospace;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 2px;
    margin-bottom: 20px;
  }

  /* 2. Glassmorphism Mission Box */
  blockquote {
    border-left: 5px solid #00d2ff !important;
    background: rgba(0, 210, 255, 0.05) !important;
    border-radius: 12px !important;
    padding: 25px !important;
    color: #e2e8f0 !important;
    box-shadow: inset 0 0 20px rgba(0, 210, 255, 0.05);
  }

  /* 3. Skill Tiles with Neon Borders */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 20px;
    margin-top: 30px;
  }

  .skill-item {
    background: #111827 !important; /* Deepest Navy */
    border: 2px solid #1e293b !important;
    padding: 20px;
    border-radius: 16px;
    text-align: center;
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    position: relative;
  }

  /* Individual Glow Colors */
  .python:hover { border-color: #3776ab !important; box-shadow: 0 0 20px rgba(55, 118, 171, 0.3); }
  .csharp:hover { border-color: #68217a !important; box-shadow: 0 0 20px rgba(104, 33, 122, 0.3); }
  .sql:hover { border-color: #00758f !important; box-shadow: 0 0 20px rgba(0, 117, 143, 0.3); }
  .web:hover { border-color: #e34c26 !important; box-shadow: 0 0 20px rgba(227, 76, 38, 0.3); }

  .skill-item i {
    font-size: 2rem;
    margin-bottom: 15px;
    display: block;
  }

  /* 4. Animated "Learning" Pulse */
  .edu-highlight {
    background: rgba(34, 211, 238, 0.1);
    color: #22d3ee;
    padding: 2px 8px;
    border-radius: 4px;
    font-weight: bold;
    border: 1px solid rgba(34, 211, 238, 0.3);
  }

  /* Custom Hover for Icons */
  .skill-item:hover i {
    transform: scale(1.2) rotate(5deg);
    transition: 0.3s;
  }
</style>

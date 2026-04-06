---
layout: page
title: About
icon: fas fa-info-circle
order: 1
---

<div class="about-header">
  <h1 class="display-title">Hi, I'm Sohaib Maan</h1>
  <p class="hero-subtitle">Machine Learning Enthusiast & Developer</p>
  <blockquote>
    "Dedicated to turning raw data into intelligent insights and building predictive models for real-world impact."
  </blockquote>
</div>

## 🤖 Tech Stack & Tools

<div class="skills-grid">
  <div class="skill-item python">
    <i class="fab fa-python"></i>
    <span>Python</span>
    <small>(Scikit-Learn, Pandas)</small>
  </div>
  <div class="skill-item csharp">
    <i class="fas fa-code"></i>
    <span>C#</span>
    <small>(.NET / ML.NET)</small>
  </div>
  <div class="skill-item sql">
    <i class="fas fa-database"></i>
    <span>MySQL</span>
    <small>(Data Engineering)</small>
  </div>
  <div class="skill-item web">
    <i class="fab fa-html5"></i>
    <span>Web</span>
    <small>(HTML5 / CSS3)</small>
  </div>
</div>

## 🚀 The Journey So Far

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="milestone-title">UET Faisalabad 🎓</h3>
      <p class="milestone-date">2025 - PRESENT</p>
      <p>Advancing my engineering degree with a focus on high-performance computing and algorithmic efficiency at <strong>UET</strong>.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="milestone-title">Machine Learning Deep Dive 🤖</h3>
      <p class="milestone-date">SEP 2025 - FEB 2026</p>
      <p>Dedicated 6 months to mastering <strong>Predictive Modeling</strong>. Specializing in Scikit-Learn and Pandas to engineer features for intelligent insights.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="milestone-title">C# (.NET Framework) 🌐</h3>
      <p class="milestone-date">FEB 2026 - PRESENT</p>
      <p>Bridging the gap by integrating ML models into functional web and desktop environments using <strong>.NET and C#</strong>.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="milestone-title">MySQL & Data Engineering 🗄️</h3>
      <p class="milestone-date">FEB 2026 - PRESENT</p>
      <p>Focused on <strong>Database Architecture</strong> and query optimization. Managing relational data structures to ensure seamless data flow for ML pipelines.</p>
    </div>
  </div>
</div>










<style>
  /* --- Monokai Pro / Octagon Developer Vibe --- */

  /* 1. Header with Octagon Gradient */
  .display-title {
    font-size: 3rem;
    font-weight: 900;
    background: linear-gradient(to right, #ffd866, #ff6188); /* Mellow Amber to Salmon */
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 0.2rem;
    letter-spacing: -1px;
  }

  .hero-subtitle {
    color: #ffd866; /* Octagon Yellow */
    font-family: 'JetBrains Mono', 'Fira Code', monospace;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 2px;
    margin-bottom: 20px;
    opacity: 0.9;
  }

  /* 2. Glassmorphism Mission Box - Octagon Tint */
  blockquote {
    border-left: 5px solid #ffd866 !important;
    background: rgba(255, 216, 102, 0.05) !important;
    border-radius: 12px !important;
    padding: 25px !important;
    color: #e3e3e3 !important;
    box-shadow: inset 0 0 20px rgba(255, 216, 102, 0.02);
  }

  /* 3. Skill Tiles - Octagon Palette */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 20px;
    margin-top: 30px;
  }

  .skill-item {
    background: #282a36 !important; /* Dark Slate */
    border: 1px solid #3d3f4b !important;
    padding: 20px;
    border-radius: 16px;
    text-align: center;
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
  }

  /* Hover Glows - Octagon Professional Colors */
  .python:hover { border-color: #a9dc76 !important; box-shadow: 0 0 20px rgba(169, 220, 118, 0.2); }
  .csharp:hover { border-color: #ab9df2 !important; box-shadow: 0 0 20px rgba(171, 157, 242, 0.2); }
  .sql:hover { border-color: #ffd866 !important; box-shadow: 0 0 20px rgba(255, 216, 102, 0.2); }
  .web:hover { border-color: #fc9867 !important; box-shadow: 0 0 20px rgba(252, 152, 103, 0.2); }

  .skill-item i {
    font-size: 2rem;
    margin-bottom: 15px;
    display: block;
    color: #ffd866; 
  }
  
  .skill-item span { color: #fdfdfd; font-weight: bold; display: block; }
  .skill-item small { color: #727072; font-size: 0.8rem; }

  /* --- FIXED TIMELINE ALIGNMENT - Octagon Edition --- */
  .timeline {
    position: relative;
    max-width: 100%;
    margin: 40px 0;
    padding-left: 30px;
    border-left: 2px solid #3d3f4b; 
  }

  .timeline-item {
    position: relative;
    margin-bottom: 30px;
  }

  /* The Glowing Dots - Amber */
  .timeline-dot {
    position: absolute;
    left: -38px; 
    top: 20px;
    width: 14px;
    height: 14px;
    background: #ffd866;
    border-radius: 50%;
    box-shadow: 0 0 10px rgba(255, 216, 102, 0.6);
    z-index: 10;
    border: 2px solid #282a36;
  }

  /* The Content Boxes */
  .timeline-content {
    background: rgba(40, 42, 54, 0.6) !important;
    border: 1px solid rgba(255, 216, 102, 0.05) !important;
    padding: 20px;
    border-radius: 16px;
    margin-left: 10px;
    transition: all 0.3s ease;
  }

  .timeline-content:hover {
    background: rgba(255, 216, 102, 0.02) !important;
    border-color: #ffd866 !important;
    transform: translateX(8px);
  }

  /* --- "PRESENT" HIGHLIGHT - Salmon Pink --- */
  .timeline-item:nth-last-child(-n+2) .timeline-dot {
    background: #ff6188 !important; /* Salmon for active focus */
    box-shadow: 0 0 15px rgba(255, 97, 136, 0.5);
  }

  .timeline-item:nth-last-child(-n+2) .timeline-content {
    border-left: 3px solid #ff6188 !important;
  }

  .milestone-title { color: #fdfdfd !important; font-size: 1.2rem !important; font-weight: 700; }
  
  .milestone-date {
    color: #ffd866 !important;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.85rem;
    font-weight: bold;
    margin-bottom: 10px;
    display: inline-block;
  }

  .timeline-item:nth-last-child(-n+2) .milestone-date {
    color: #ff6188 !important;
  }

  .timeline-content p { color: #939293 !important; line-height: 1.6; margin: 0; }
</style>

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
  /* --- Global Theme & Header --- */
  .display-title {
    font-size: 3rem;
    font-weight: 900;
    background: linear-gradient(to right, #00d2ff, #92fe9d);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 0.2rem;
  }

  .hero-subtitle {
    color: #22d3ee;
    font-family: 'Courier New', monospace;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 2px;
    margin-bottom: 20px;
  }

  blockquote {
    border-left: 5px solid #00d2ff !important;
    background: rgba(0, 210, 255, 0.05) !important;
    border-radius: 12px !important;
    padding: 20px !important;
    color: #e2e8f0 !important;
  }

  /* --- Skill Tiles --- */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
    gap: 15px;
    margin-top: 20px;
  }

  .skill-item {
    background: #111827 !important;
    border: 1px solid #1e293b !important;
    padding: 20px;
    border-radius: 16px;
    text-align: center;
    transition: 0.3s ease;
  }

  .skill-item:hover { transform: translateY(-5px); border-color: #22d3ee !important; }
  .skill-item i { font-size: 2rem; margin-bottom: 10px; display: block; color: #22d3ee; }
  .skill-item span { color: #f8fafc; font-weight: bold; display: block; }
  .skill-item small { color: #64748b; font-size: 0.8rem; }

  /* --- Timeline Logic --- */
  .timeline {
    position: relative;
    padding-left: 30px;
    border-left: 2px solid #1e293b;
    margin: 40px 0;
  }

  .timeline-item {
    position: relative;
    margin-bottom: 30px;
  }

  .timeline-dot {
    position: absolute;
    left: -38px;
    top: 22px;
    width: 14px;
    height: 14px;
    background: #22d3ee;
    border-radius: 50%;
    border: 2px solid #000;
    z-index: 10;
  }

  .timeline-content {
    background: rgba(30, 41, 59, 0.4) !important;
    border: 1px solid rgba(255, 255, 255, 0.05) !important;
    padding: 18px;
    border-radius: 14px;
    margin-left: 10px;
  }

  /* --- Active State Highlights (Amber) --- */
  /* Targets the last two items (C# and MySQL) */
  .timeline-item:nth-last-child(-n+2) .timeline-dot {
    background: #fbbf24 !important;
    box-shadow: 0 0 15px rgba(251, 191, 36, 0.5);
  }

  .timeline-item:nth-last-child(-n+2) .timeline-content {
    border-left: 3px solid #fbbf24 !important;
  }

  .milestone-title { color: #f1f5f9 !important; font-size: 1.15rem !important; margin-bottom: 4px !important; }
  .milestone-date { color: #22d3ee !important; font-size: 0.8rem; font-weight: bold; margin-bottom: 8px; display: inline-block; }
  .timeline-item:nth-last-child(-n+2) .milestone-date { color: #fbbf24 !important; }
  
  .timeline-content p { color: #94a3b8 !important; font-size: 0.9rem; line-height: 1.5; margin: 0; }
</style>

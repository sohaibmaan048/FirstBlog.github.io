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




## 🚀 The Journey So Far

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="milestone-title">UET Faisalabad 🎓</h3>
      <p class="milestone-date">2022 - Present</p>
      <p>Currently pursuing my degree, focusing on the intersection of Software Engineering and Data Science. Maintaining a strong foundation in core algorithms.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="milestone-title">Machine Learning Deep Dive 🤖</h3>
      <p class="milestone-date">2023 - 2024</p>
      <p>Shifted focus toward <strong>Predictive Modeling</strong>. Mastered Scikit-Learn and Pandas to clean raw data and turn it into actionable insights.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="milestone-title">Full-Stack Integration 🌐</h3>
      <p class="milestone-date">Present</p>
      <p>Bridging the gap by integrating ML models into functional web and desktop environments using <strong>.NET and C#</strong>.</p>
    </div>
  </div>
</div>
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



  /* --- Timeline Styling --- */
.timeline {
  position: relative;
  max-width: 800px;
  margin: 40px 0;
  padding-left: 30px;
  border-left: 2px solid #1e293b; /* The vertical line */
}

.timeline-item {
  position: relative;
  margin-bottom: 40px;
}

/* The Glowing Dots */
.timeline-dot {
  position: absolute;
  left: -37px;
  top: 5px;
  width: 12px;
  height: 12px;
  background: #22d3ee;
  border-radius: 50%;
  box-shadow: 0 0 10px #22d3ee, 0 0 20px rgba(34, 211, 238, 0.4);
}

/* The Content Boxes */
.timeline-content {
  background: rgba(30, 41, 59, 0.4) !important;
  border: 1px solid rgba(255, 255, 255, 0.05) !important;
  padding: 20px;
  border-radius: 16px;
  transition: 0.3s ease;
}

.timeline-content:hover {
  background: rgba(34, 211, 238, 0.05) !important;
  border-color: #22d3ee !important;
  transform: translateX(10px);
}

.milestone-title {
  color: #f1f5f9 !important;
  font-size: 1.25rem !important;
  font-weight: 700 !important;
  margin-bottom: 5px !important;
}

.milestone-date {
  color: #22d3ee !important;
  font-family: 'JetBrains Mono', monospace;
  font-size: 0.85rem;
  font-weight: bold;
  text-transform: uppercase;
  margin-bottom: 10px;
}

.timeline-content p {
  color: #94a3b8 !important;
  font-size: 0.95rem;
  line-height: 1.6;
  margin: 0;
}
</style>

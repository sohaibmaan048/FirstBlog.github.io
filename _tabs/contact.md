---
layout: page
title: Contact
icon: fas fa-envelope
order: 4
---

# Get in Touch
I’m always happy to connect! Feel free to reach out through any of the platforms below or send me a direct message.

<div class="row g-3 mb-5">
  <div class="col-md-4">
    <a href="mailto:sohaibmaan048@gmail.com" class="contact-card">
      <div class="card h-100 text-center p-3">
        <i class="fas fa-envelope fa-2x mb-2"></i>
        <span>Email Me</span>
        <small>sohaibmaan048@gmail.com</small>
      </div>
    </a>
  </div>

  <div class="col-md-4">
    <a href="https://github.com/sohaibmaan048" target="_blank" class="contact-card">
      <div class="card h-100 text-center p-3">
        <i class="fab fa-github fa-2x mb-2"></i>
        <span>GitHub</span>
        <small>@sohaibmaan048</small>
      </div>
    </a>
  </div>

  <div class="col-md-4">
    <a href="https://www.linkedin.com/in/sohaib-maan-067140346" target="_blank" class="contact-card">
      <div class="card h-100 text-center p-3">
        <i class="fab fa-linkedin fa-2x mb-2"></i>
        <span>LinkedIn</span>
        <small>View Profile</small>
      </div>
    </a>
  </div>
</div>

## Send a Message

<form action="https://formspree.io/f/xjgppjez" method="POST" class="modern-form">
  <div class="mb-3">
    <label class="form-label">Your Name</label>
    <input type="text" name="name" class="form-control" placeholder="Enter your name" required>
  </div>

  <div class="mb-3">
    <label class="form-label">Your Email</label>
    <input type="email" name="_replyto" class="form-control" placeholder="name@example.com" required>
  </div>

  <div class="mb-3">
    <label class="form-label">Message</label>
    <textarea name="message" class="form-control" rows="5" placeholder="How can I help you?" required></textarea>
  </div>

  <input type="text" name="_gotcha" style="display:none">

  <button type="submit" class="btn-submit">
    Send Message <i class="fas fa-paper-plane ms-2"></i>
  </button>
</form>



<style>
  /* --- Modern Tech / Slate & Cyan Palette --- */
  
  /* Reset and Typography */
  .contact-container {
    margin-top: 2rem;
  }

  /* The Link Wrapper */
  .contact-card {
    text-decoration: none !important;
    display: block;
    margin-bottom: 1rem;
  }

  /* The Card Design */
  .contact-card .card {
    background: #0f172a !important; /* Deep Space Navy */
    border: 1px solid #1e293b !important; /* Subtle Slate Border */
    border-radius: 12px !important;
    padding: 20px !important;
    transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1) !important;
    position: relative;
    overflow: hidden;
  }

  /* The "Cyber" Glow on Hover */
  .contact-card:hover .card {
    transform: translateY(-5px);
    border-color: #22d3ee !important; /* Bright Cyan */
    box-shadow: 0 0 20px rgba(34, 211, 238, 0.15);
    background: #111827 !important;
  }

  /* Icon and Text Colors */
  .contact-card i {
    color: #22d3ee; /* Cyan Icons */
    margin-bottom: 10px;
    filter: drop-shadow(0 0 5px rgba(34, 211, 238, 0.3));
  }

  .contact-card span {
    color: #f8fafc !important; /* High Contrast White */
    font-weight: 600;
    font-size: 1.05rem;
    display: block;
  }

  .contact-card small {
    color: #64748b !important; /* Muted Slate */
    font-family: 'JetBrains Mono', monospace; /* Tech feel */
    font-size: 0.8rem;
  }

  /* Form Styling - Integrated Look */
  .modern-form .form-control {
    background: #020617 !important; /* Almost Black */
    border: 1px solid #1e293b !important;
    color: #f1f5f9 !important;
    border-radius: 8px !important;
    padding: 12px !important;
  }

  .modern-form .form-control:focus {
    border-color: #22d3ee !important;
    box-shadow: 0 0 0 2px rgba(34, 211, 238, 0.1) !important;
  }

  /* Submit Button - Solid Professional Look */
  .btn-submit {
    background: #22d3ee !important; /* Solid Cyan */
    color: #020617 !important; /* Dark text for readability */
    border: none !important;
    padding: 14px !important;
    border-radius: 8px !important;
    font-weight: 800 !important;
    text-transform: uppercase;
    letter-spacing: 1px;
    width: 100%;
    margin-top: 15px;
    transition: 0.2s ease;
    cursor: pointer;
  }

  .btn-submit:hover {
    background: #06b6d4 !important; /* Slightly darker cyan */
    box-shadow: 0 0 25px rgba(34, 211, 238, 0.4);
    transform: scale(1.01);
  }

  /* Label Colors */
  .form-label {
    color: #94a3b8 !important;
    font-size: 0.85rem;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }
</style>

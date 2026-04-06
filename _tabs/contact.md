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
  /* Container Styling */
  #get-in-touch + p {
    margin-bottom: 30px;
    color: #94a3b8;
  }

  /* Remove default link styling */
  .contact-card {
    text-decoration: none !important;
    display: block;
    transition: all 0.3s ease;
  }

  /* The Tiles/Cards - Professional Dark Theme */
  .contact-card .card {
    background: rgba(30, 41, 59, 0.5) !important; /* Semi-transparent slate */
    backdrop-filter: blur(10px); /* Blur effect */
    border: 1px solid rgba(255, 255, 255, 0.05) !important;
    border-radius: 16px !important;
    padding: 25px 15px !important;
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275) !important;
  }

  /* Hover State - Indigo Glow */
  .contact-card:hover .card {
    transform: translateY(-8px);
    background: rgba(110, 142, 251, 0.1) !important;
    border-color: #6e8efb !important;
    box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4), 0 0 15px rgba(110, 142, 251, 0.2);
  }

  /* Icon Colors */
  .contact-card i {
    color: #94a3b8; /* Muted silver/gray by default */
    transition: color 0.3s ease;
  }

  .contact-card:hover i {
    color: #6e8efb; /* Turns Brand Blue on hover */
  }

  /* Text inside cards */
  .contact-card span {
    color: #f1f5f9 !important; /* Off-white */
    font-weight: 700;
    font-size: 1.1rem;
    margin-top: 10px;
    display: block;
  }

  .contact-card small {
    color: #64748b !important; /* Muted blue-gray */
    font-size: 0.85rem;
  }

  /* Form Input Styling - Deep Navy */
  .modern-form .form-label {
    color: #94a3b8;
    font-size: 0.9rem;
    font-weight: 600;
    margin-left: 5px;
  }

  .modern-form .form-control {
    background: #0f172a !important; /* Darker than the cards */
    border: 1px solid #1e293b !important;
    color: #e2e8f0 !important;
    border-radius: 12px !important;
    padding: 14px !important;
    transition: 0.3s;
  }

  .modern-form .form-control:focus {
    border-color: #6e8efb !important;
    background: #1e293b !important;
    box-shadow: 0 0 0 4px rgba(110, 142, 251, 0.1) !important;
  }

  /* Submit Button - Soft Gradient */
  .btn-submit {
    background: linear-gradient(135deg, #6366f1 0%, #8b5cf6 100%) !important;
    color: white !important;
    border: none !important;
    padding: 16px !important;
    border-radius: 12px !important;
    font-weight: 700 !important;
    letter-spacing: 0.5px;
    width: 100%;
    margin-top: 10px;
    cursor: pointer;
    box-shadow: 0 4px 15px rgba(99, 102, 241, 0.3);
    transition: 0.3s;
  }

  .btn-submit:hover {
    box-shadow: 0 8px 25px rgba(99, 102, 241, 0.5);
    transform: scale(1.01);
    filter: brightness(1.1);
  }
</style>

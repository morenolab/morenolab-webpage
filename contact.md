---
layout: page
title: "Contact"
description: ""
feature_image: "/assets/images/contact_banner.png"
order: 7
---

<style>
  .contact-form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    max-width: 600px;
    margin: 2rem 0;
    padding: 20px;
    background: #f9f9f9;
    border-radius: 8px;
    border: 1px solid #eee;
  }
  .contact-form label {
    font-weight: bold;
    margin-bottom: -0.5rem;
    color: #333;
  }
  .contact-form input, .contact-form select, .contact-form textarea {
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-family: inherit;
  }
  .contact-form button {
    background-color: #0056b3;
    color: white;
    padding: 12px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-weight: bold;
    transition: background 0.3s ease;
  }
  .contact-form button:hover {
    background-color: #004494;
  }
  .social-container {
    display: flex;
    gap: 15px;
    margin-top: 1rem;
    flex-wrap: wrap;
  }
  .social-button {
    padding: 8px 16px;
    border-radius: 20px;
    background: #eee;
    color: #333;
    text-decoration: none;
    font-size: 0.9rem;
    font-weight: 500;
    transition: all 0.3s ease;
  }
  .social-button:hover {
    background: #0056b3;
    color: white;
  }
  .map-container {
    overflow: hidden;
    padding-bottom: 56.25%;
    position: relative;
    height: 0;
    margin-top: 1.5rem;
    border-radius: 8px;
    border: 1px solid #eee;
  }
  .map-container iframe {
    left: 0;
    top: 0;
    height: 100%;
    width: 100%;
    position: absolute;
  }
  .lab-section {
    margin-top: 2rem;
    padding-top: 1rem;
    border-top: 1px solid #eee;
  }
</style>

We welcome inquiries from researchers, students, and institutions worldwide. Whether you are looking for collaboration opportunities or have questions about our genomic research, we look forward to hearing from you.

### 📩 Send us a Message

For general questions or partnership proposals, please use the form below or contact us at [popgenlab@cinvestav.mx](mailto:popgenlab@cinvestav.mx).

<form action="https://formspree.io/f/xojkjzpo" method="POST" class="contact-form">
  <label for="full-name">Full Name</label>
  <input type="text" name="name" id="full-name" placeholder="Dr. Alex Smith" required>

  <label for="email-address">Email Address</label>
  <input type="email" name="_replyto" id="email-address" placeholder="email@institution.edu" required>

  <label for="subject">Inquiry Type</label>
  <select name="subject" id="subject">
    <option value="General Inquiry">General Inquiry</option>
    <option value="Research Collaboration">Research Collaboration</option>
    <option value="Prospective Student">Prospective Student / Joining the Lab</option>
    <option value="Media/Press">Media / Press</option>
  </select>

  <label for="message">Message</label>
  <textarea rows="5" name="message" id="message" placeholder="How can we help you?" required></textarea>

  <button type="submit">Send Message</button>

  <input type="hidden" name="_next" value="https://localhost:4000/thank-you">

</form>

---

### 🧬 Join the Lab

We are always looking for motivated students (Undergraduate, MSc, and PhD) and Postdoctoral fellows.

**Prospective Students:** Please include your CV and a 1-2 paragraph description of your research interests.

**Postdoctoral Candidates:** Inquiries should include a CV, a cover letter, and contact info for two references.

---

### 🌐 Follow Our Research

Stay updated with our latest publications, fieldwork, and lab news:

<div class="social-container">
  <a href="https://x.com/moreno_lab" class="social-button">X / Twitter</a>
  <a href="https://github.com/morenolab" class="social-button">GitHub</a>
  <a href="https://www.linkedin.com/company/human-population-genomics-moreno-lab" class="social-button">LinkedIn</a>
</div>

---

### 📍 Find Us
**Cinvestav Sede Sur**

Calzada de los Tenorios No. 235, Col. Granjas Coapa  
Alcaldía Tlalpan, C.P. 14330, Ciudad de México

<div class="map-container">
  <iframe 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3765.234390547963!2d-99.12450802396172!3d19.29388364504141!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x85ce009fd9886f77%3A0x8821950e395f190a!2sCinvestav%20Sede%20Sur!5e0!3m2!1sen!2smx!4v1709560000000!5m2!1sen!2smx" 
    width="600" 
    height="450" 
    style="border:0;" 
    allowfullscreen="" 
    loading="lazy" 
    referrerpolicy="no-referrer-when-downgrade">
  </iframe>
</div>
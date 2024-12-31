---
layout: single
title: ""
permalink: /resume/
author_profile: true
toc: true
toc_label: "Contents"
---
<!-- Collapsible Container for Skills -->
# Skills and Competencies


  <!-- Collapsible Section for Programming Languages -->
  <button class="collapsible">Programming Languages</button>
  <div class="content">
    <ul>
      <li>Python</li>
      <li>R</li>
      <li>SQL</li>
      <li>C++</li>
    </ul>
    <p>Advanced proficiency in data science, AI, and automation.</p>
  </div>

  <!-- Collapsible Section for Frameworks -->
  <button class="collapsible">Frameworks</button>
  <div class="content">
    <ul>
      <li>TensorFlow</li>
      <li>PyTorch</li>
      <li>Keras</li>
      <li>Hugging Face Transformers</li>
    </ul>
    <p>Expert in machine learning frameworks for deep learning and NLP.</p>
  </div>

  <!-- Collapsible Section for Cloud & Ops -->
  <button class="collapsible">Cloud & Ops</button>
  <div class="content">
    <ul>
      <li>AWS</li>
      <li>Docker</li>
      <li>MLOps</li>
      <li>CI/CD</li>
    </ul>
    <p>Experience in deploying models and managing cloud infrastructures.</p>
  </div>

  <!-- Collapsible Section for Healthcare Compliance -->
  <button class="collapsible">Healthcare Compliance</button>
  <div class="content">
    <ul>
      <li>HIPAA</li>
      <li>FDA</li>
      <li>HL7 Standards</li>
    </ul>
    <p>Knowledge in regulatory compliance within the healthcare industry.</p>
  </div>

<!-- CSS for Collapsible Sections -->
<style>
  /* Button styling */
  .collapsible {
    background-color:rgb(191, 135, 62);
    color: white;
    cursor: pointer;
    padding: 15px;
    width: 100%;
    border: none;
    text-align: left;
    font-size: 1.2em;
    margin: 5px 0;
    border-radius: 10px;
    transition: 0.3s;
  }

  /* Hover effect */
  .collapsible:hover {
    background-color:rgb(176, 109, 22);
  }

  /* Collapsible content styling */
  .content {
    padding: 0 18px;
    display: none;
    overflow: hidden;
    background-color: #f1f1f1;
    margin-bottom: 10px;
    border-radius: 10px;
  }

  ul {
    list-style-type: none;
    padding: 0;
    font-size: 1em;
  }

  ul li {
    padding: 5px 0;
  }

  p {
    padding: 10px;
    font-size: 1em;
  }
</style>

<!-- JavaScript for Collapsible Functionality -->
<script>
  // Get all collapsible buttons
  var coll = document.getElementsByClassName("collapsible");

  // Loop through each button
  for (var i = 0; i < coll.length; i++) {
    coll[i].addEventListener("click", function() {
      // Toggle the content visibility
      this.classList.toggle("active");
      var content = this.nextElementSibling;
      
      // If the content is visible, hide it, otherwise show it
      if (content.style.display === "block") {
        content.style.display = "none";
      } else {
        content.style.display = "block";
      }
    });
  }
</script>

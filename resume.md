---
layout: single
title: ""
permalink: /resume/
author_profile: true
---
<div style="margin: 40px 0;">
  <h2 style="text-align: center;">Skills and Competencies</h2>

  <!-- Flip Cards Section -->
  <div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; margin-top: 20px;">
    <!-- Card 1: Programming Languages -->
    <div class="flip-card">
      <div class="flip-card-inner">
        <div class="flip-card-front">
          <img src="https://img.icons8.com/color/48/000000/python.png" alt="Python">
          <h4>Programming Languages</h4>
          <ul>
            <li>Python</li>
            <li>R</li>
            <li>SQL</li>
            <li>C++</li>
          </ul>
        </div>
        <div class="flip-card-back">
          <p>Advanced proficiency in data science, AI, and automation.</p>
        </div>
      </div>
    </div>

    <!-- Card 2: Frameworks -->
    <div class="flip-card">
      <div class="flip-card-inner">
        <div class="flip-card-front">
          <img src="https://img.icons8.com/color/48/000000/tensorflow.png" alt="TensorFlow">
          <h4>Frameworks</h4>
          <ul>
            <li>TensorFlow</li>
            <li>PyTorch</li>
            <li>Keras</li>
            <li>Hugging Face Transformers</li>
          </ul>
        </div>
        <div class="flip-card-back">
          <p>Expert in machine learning frameworks for deep learning and NLP.</p>
        </div>
      </div>
    </div>

    <!-- Card 3: Cloud & Ops -->
    <div class="flip-card">
      <div class="flip-card-inner">
        <div class="flip-card-front">
          <img src="https://img.icons8.com/color/48/000000/docker.png" alt="Docker">
          <h4>Cloud & Ops</h4>
          <ul>
            <li>AWS</li>
            <li>Docker</li>
            <li>MLOps</li>
            <li>CI/CD</li>
          </ul>
        </div>
        <div class="flip-card-back">
          <p>Experience in deploying models and managing cloud infrastructures.</p>
        </div>
      </div>
    </div>

    <!-- Card 4: Healthcare Compliance -->
    <div class="flip-card">
      <div class="flip-card-inner">
        <div class="flip-card-front">
          <img src="https://img.icons8.com/color/48/000000/health-data.png" alt="Healthcare">
          <h4>Healthcare Compliance</h4>
          <ul>
            <li>HIPAA</li>
            <li>FDA</li>
            <li>HL7 Standards</li>
          </ul>
        </div>
        <div class="flip-card-back">
          <p>Knowledge in regulatory compliance within the healthcare industry.</p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- CSS for Flip Cards -->
<style>
  /* Flip Card Container */
/* Flip Card Container */
.flip-card {
  background-color: transparent;
  width: 250px;
  height: 250px;
  perspective: 1000px;
  margin: 10px;
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.6s;
  transform-style: preserve-3d;
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  border: 1px solid #ddd;
  border-radius: 10px;
  padding: 20px;
  overflow: hidden; /* Prevent content from overflowing */
}

.flip-card-front {
  background-color: #f9f9f9;
}

.flip-card-back {
  background-color: #4caf50;
  color: white;
  transform: rotateY(180deg);
}

/* Image styling */
.flip-card img {
  margin-bottom: 10px;
  width: 48px;
  height: 48px;
}

/* Title styling */
h4 {
  margin: 10px 0;
  font-size: 1.1em;
  overflow: hidden; /* Prevent title from overflowing */
  text-overflow: ellipsis; /* Add ellipsis if title is too long */
  white-space: nowrap; /* Prevent title from wrapping */
}

/* Unordered List styling */
ul {
  list-style-type: none;
  padding: 0;
  font-size: 0.9em;
  overflow-y: auto; /* Allow scrolling if list is too long */
  max-height: 120px; /* Set a max height to avoid overflowing */
  margin: 0;
}

/* List Item styling */
ul li {
  padding: 5px 0;
  overflow: hidden; /* Prevent individual items from overflowing */
  text-overflow: ellipsis; /* Add ellipsis if items are too long */
  white-space: nowrap; /* Prevent wrapping of list items */
}

</style>

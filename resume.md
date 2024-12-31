---
layout: single
title: ""
permalink: /resume/
author_profile: true
toc: true
toc_label: "Contents"
---
## Skills and Competencies

  <!-- Flip Cards Section -->
  <div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; margin-top: 20px;">
    <!-- Card 1 -->
    <div class="flip-card">
      <div class="flip-card-inner">
        <div class="flip-card-front">
          <img src="https://img.icons8.com/color/48/000000/python.png" alt="Python">
          <h4>Programming</h4>
        </div>
        <div class="flip-card-back">
          <p>Python, R, SQL, C++, MATLAB</p>
        </div>
      </div>
    </div>
    <!-- Card 2 -->
    <div class="flip-card">
      <div class="flip-card-inner">
        <div class="flip-card-front">
          <img src="https://img.icons8.com/color/48/000000/tensorflow.png" alt="TensorFlow">
          <h4>Frameworks</h4>
        </div>
        <div class="flip-card-back">
          <p>TensorFlow, PyTorch, Keras, SciKit-Learn, Hugging Face Transformers</p>
        </div>
      </div>
    </div>
    <!-- Card 3 -->
    <div class="flip-card">
      <div class="flip-card-inner">
        <div class="flip-card-front">
          <img src="https://img.icons8.com/color/48/000000/docker.png" alt="Docker">
          <h4>Cloud & Ops</h4>
        </div>
        <div class="flip-card-back">
          <p>AWS, Docker, MLOps, CI/CD, Compute Canada Cloud</p>
        </div>
      </div>
    </div>
    <!-- Card 4 -->
    <div class="flip-card">
      <div class="flip-card-inner">
        <div class="flip-card-front">
          <img src="https://img.icons8.com/color/48/000000/health-data.png" alt="Healthcare">
          <h4>Healthcare Compliance</h4>
        </div>
        <div class="flip-card-back">
          <p>EHR, EMR, HIPAA, FDA, HL7 Standards</p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- CSS for Flip Cards -->
<style>
  .flip-card {
    background-color: transparent;
    width: 200px;
    height: 200px;
    perspective: 1000px;
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
  }
  .flip-card-front {
    background-color: #f9f9f9;
  }
  .flip-card-back {
    background-color: #4caf50;
    color: white;
    transform: rotateY(180deg);
  }
  img {
    margin-bottom: 10px;
    width: 48px;
    height: 48px;
  }
  h4 {
    margin: 10px 0;
  }
  p {
    padding: 0 10px;
  }
</style>

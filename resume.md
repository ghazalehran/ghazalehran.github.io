---
layout: single
title: ""
permalink: /resume/
author_profile: true
toc: true
toc_label: "Contents"
---
<div style="margin: 40px 0;">
  <h2 style="text-align: center;">Skills and Competencies</h2>

  <!-- Skill Cards Section -->
  <div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; margin-top: 20px;">
    <!-- Card 1 -->
    <div style="width: 250px; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
      <img src="https://img.icons8.com/color/48/000000/python.png" alt="Python" style="margin-bottom: 10px;">
      <h4>Programming</h4>
      <p>Python, R, SQL, C++, MATLAB</p>
    </div>
    <!-- Card 2 -->
    <div style="width: 250px; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
      <img src="https://img.icons8.com/color/48/000000/tensorflow.png" alt="TensorFlow" style="margin-bottom: 10px;">
      <h4>Frameworks</h4>
      <p>TensorFlow, PyTorch, Keras, SciKit-Learn, Hugging Face Transformers</p>
    </div>
    <!-- Card 3 -->
    <div style="width: 250px; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
      <img src="https://img.icons8.com/color/48/000000/docker.png" alt="Docker" style="margin-bottom: 10px;">
      <h4>Cloud & Ops</h4>
      <p>AWS, Docker, MLOps, CI/CD, Compute Canada Cloud</p>
    </div>
    <!-- Card 4 -->
    <div style="width: 250px; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
      <img src="https://img.icons8.com/color/48/000000/health-data.png" alt="Healthcare" style="margin-bottom: 10px;">
      <h4>Healthcare Compliance</h4>
      <p>EHR, EMR, HIPAA, FDA, HL7 Standards</p>
    </div>
  </div>

  <!-- Radar Chart Section -->
  <div style="margin-top: 50px; text-align: center;">
    <h3>Proficiency Chart</h3>
    <canvas id="skillsChart" width="400" height="400"></canvas>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script>
        const ctx = document.getElementById('skillsChart').getContext('2d');
        const skillsChart = new Chart(ctx, {
            type: 'radar',
            data: {
                labels: ['Python', 'R', 'SQL', 'Machine Learning', 'Deep Learning', 'NLP', 'Docker'],
                datasets: [{
                    label: 'Proficiency Level',
                    data: [9, 8, 7, 9, 9, 8, 7],
                    backgroundColor: 'rgba(75, 192, 192, 0.2)',
                    borderColor: 'rgba(75, 192, 192, 1)',
                    borderWidth: 2
                }]
            },
            options: {
                scales: {
                    r: {
                        suggestedMin: 0,
                        suggestedMax: 10
                    }
                },
                responsive: true
            }
        });
    </script>
  </div>
</div>

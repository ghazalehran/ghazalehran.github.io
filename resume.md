---
layout: single
title: ""
permalink: /resume/
author_profile: true
toc: true
toc_label: "Contents"
---
## Technical Expertise

<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; margin-top: 20px;">
  <div style="width: 200px; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
    <img src="https://img.icons8.com/color/48/000000/python.png" alt="Python">
    <h4>Programming</h4>
    <p>
      Python<br>
      R<br>
      SQL<br>
      C++<br>
      MATLAB<br>
    </p>
  </div>
  
  <div style="width: 200px; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
    <img src="https://img.icons8.com/color/48/000000/tensorflow.png" alt="TensorFlow">
    <h4>Frameworks</h4>
    <p>
      TensorFlow<br>
      PyTorch<br>
      Keras<br>
      Hugging Face Transformers<br>
    </p>
  </div>
  
  <div style="width: 200px; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
    <img src="https://img.icons8.com/ios/50/000000/scikit-learn.png" alt="Scikit-learn">
    <h4>Libraries</h4>
    <p>
      JAX<br>
      OpenCV<br>
      SciPy<br>
      Scikit-learn<br>
      spaCy<br>
      Tidyverse<br>
      PostgreSQL<br>
      Boost<br>
    </p>
  </div>
  
  <div style="width: 200px; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
    <img src="https://img.icons8.com/color/48/000000/docker.png" alt="Docker">
    <h4>Cloud & Ops</h4>
    <p>
      AWS<br>
      Compute Canada Cloud<br>
      Docker<br>
      Git<br>
      MLOps<br>
      CI/CD<br>
    </p>
  </div>
</div>

## Domain & Industry Knowledge

<!-- Machine Learning & AI Accordion -->
<div style="max-width: 800px; margin: 20px auto; text-align: left;">
  <button class="accordion">
    <img src="https://img.icons8.com/ios/50/000000/artificial-intelligence.png" alt="Machine Learning Icon" style="height: 30px; margin-right: 10px;">
    <strong>Machine Learning & AI</strong>
  </button>
  <div class="panel">
    <p>In-depth knowledge of various Machine Learning techniques, including both <strong>Supervised</strong> and <strong>Unsupervised Learning</strong>, allowing for the creation of models that can predict outcomes and discover hidden patterns in data. Expertise in <strong>Deep Learning</strong> with advanced models like <strong>Convolutional Neural Networks (CNNs)</strong>, <strong>Recurrent Neural Networks (RNNs)</strong>, <strong>Generative Adversarial Networks (GANs)</strong>, and <strong>Autoencoders</strong>. Proficient in implementing solutions for complex problems in <strong>Natural Language Processing (NLP)</strong> and <strong>Computer Vision</strong>, enabling the extraction of insights from text and image data.</p>
  </div>
</div>

<!-- Healthcare Data & Compliance Accordion -->
<div style="max-width: 800px; margin: 20px auto; text-align: left;">
  <button class="accordion">
    <img src="https://img.icons8.com/ios/50/000000/hospital-room.png" alt="Healthcare Icon" style="height: 30px; margin-right: 10px;">
    <strong>Healthcare Data & Compliance</strong>
  </button>
  <div class="panel">
    <p>Extensive experience working with healthcare data systems like <strong>Electronic Health Records (EHR)</strong> and <strong>Electronic Medical Records (EMR)</strong>, ensuring proper management and integration of patient data. Expertise in <strong>Hospital Information Systems (HIS)</strong> for seamless healthcare operations. Well-versed in industry regulations, including <strong>HIPAA (Health Insurance Portability and Accountability Act)</strong>, <strong>FDA (U.S. Food and Drug Administration)</strong>, and <strong>HL7 (Health Level Seven Standards)</strong>, ensuring compliance in handling sensitive healthcare information. Knowledgeable in the implementation of systems that improve healthcare delivery, protect patient privacy, and meet government standards.</p>
  </div>
</div>

  <style>
    /* Basic Reset */
    body, h4, p {
      margin: 0;
      padding: 0;
    }

    /* Accordion button styles */
    .accordion {
      background-color: #f1f1f1;
      color: #444;
      padding: 15px;
      width: 100%;
      text-align: left;
      border: none;
      outline: none;
      cursor: pointer;
      font-size: 16px;
      transition: 0.4s;
      display: flex;
      align-items: center;
      border-radius: 5px;
    }

    .accordion:hover {
      background-color: #ddd;
    }

    .accordion:after {
      content: '\002B';  /* "+" symbol */
      font-size: 18px;
      color: #777;
      margin-left: auto;
    }

    .accordion.active:after {
      content: "\2212";  /* "−" symbol */
    }

    /* Panel (hidden by default) */
    .panel {
      padding: 15px;
      background-color: #f9f9f9;
      display: none;
      overflow: hidden;
      border-radius: 5px;
      margin-top: 10px;
    }

    /* Style for active accordion (when expanded) */
    .accordion.active + .panel {
      display: block;
    }

    /* Accordion Container */
    .accordion-container {
      max-width: 800px;
      margin: 20px auto;
      text-align: left;
    }

    /* Icon Styles */
    .accordion img {
      height: 30px;
      margin-right: 10px;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .accordion {
        font-size: 14px;
      }

      .panel p {
        font-size: 14px;
      }
    }
  </style>

<body>


  <!-- JavaScript for Accordion Toggle -->
  <script>
    // Accordion toggle behavior
    document.querySelectorAll('.accordion').forEach((accordion) => {
      accordion.addEventListener('click', function() {
        this.classList.toggle('active');
        const panel = this.nextElementSibling;
        if (panel.style.display === 'block') {
          panel.style.display = 'none';
        } else {
          panel.style.display = 'block';
        }
      });
    });
  </script>

</body>

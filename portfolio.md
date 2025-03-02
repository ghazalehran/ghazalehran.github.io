---
title: "<br><br>My Work<br><br>"
layout: splash
permalink: /portfolio/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/photo-portfolio-header.avif
  excerpt: "<br><br><br><br><br><br>"
# intro: 
#   - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row0:
  - image_path: assets/images/wids.jpg
    alt: "sll"
    title: "Uncovering ADHD and Gender Disparities Using Brain Imaging and Machine Learning"
    excerpt: "For the WiDS Datathon 2025, I'm developing a multi-outcome machine learning model to predict ADHD diagnoses and identify sex-based differences using brain imaging and behavioral data. Optimizing for weighted F1 score, I'm focusing on addressing the underdiagnosis of ADHD in females — gaining insights that could help drive more personalized and equitable mental health care."
    url: "https://github.com/ghazalehran/WiDS-Datathon-2025"
feature_row1:
  - image_path: assets/images/simsiam.png
    alt: "sll"
    title: "SimSiam: Self-Supervised Feature Learning with PyTorch"
    excerpt: "Dive into SimSiam, a self-supervised learning algorithm designed to extract meaningful representations from data without the need for labeled samples. This guide walks through the key components, training pipeline, and performance evaluation on CIFAR-10, with visual insights into learned features."
    url: "https://github.com/ghazalehran/GenerativeModels/tree/main/SSL"
feature_row2:
  - image_path: assets/images/VAE2.jpg
    alt: "VAE-cat"
    title: "Exploring Variational Autoencoders: A Hands-On Guide"
    excerpt: "Explore the power of Variational Autoencoders (VAEs) in this hands-on guide. Learn how to implement and train a VAE on the SVHN dataset using       PyTorch, with step-by-step instructions for building the model and visualizing results. Perfect for those looking to dive into generative models and image generation!"
    url: "https://github.com/ghazalehran/GenerativeModels/tree/main/VAE"
feature_row3:
  - image_path: assets/images/mvarica.avif
    alt: "Image courtesy of unsplash"
    title: "Connectivity Analysis with MVAR and ICA"
    excerpt: 'This project applies MVAR (Multivariate Autoregressive) modeling and ICA (Independent Component Analysis) to EEG time-series data to estimate connectivity measures like transfer functions and directed coherence.<a href="https://github.com/ppsp-team/HyPyP/blob/master/tutorial/getting_started.ipynb" target="_blank">Check out the PDC Connectivity in the Tutorial section</a>'
    url: "https://github.com/ppsp-team/HyPyP/blob/master/hypyp/mvarica.py"
feature_row4:
  - image_path: /assets/images/emoji.avif
    alt: "Image courtesy of unsplash"
    title: "Sentiment Analysis with Machine Learning & LIME"
    excerpt: "A simple yet powerful sentiment classification system using machine learning models (Naive Bayes, SVM, Neural Networks) to predict text sentiment. Implemented feature engineering techniques like Bag of Words and NLP, and applied LIME for model interpretability. The project focuses on building accurate, explainable AI solutions for text sentiment analysis."
    url: "https://github.com/ghazalehran/Sentiment-Analysis"
feature_row5:
  - image_path: /assets/images/Data3.jpeg
    alt: "Photo from iStoc"
    title: "Data Harmonization With R"
    excerpt: "Coming Soon"
    url: "https://github.com/ghazalehran/Data-Integration-in-R"
# feature_row2:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Left Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row3:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Right Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row4:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Center Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
---
{% include feature_row id="feature_row0" type="left" %}

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="left" %}

{% include feature_row id="feature_row5" type="left" %}

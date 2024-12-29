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
feature_row2:
  - image_path: assets/images/VAE.jpg
    alt: "VAE-cat"
    title: "Exploring Variational Autoencoders: A Hands-On Guide"
    excerpt: "Explore the power of Variational Autoencoders (VAEs) in this hands-on guide. Learn how to implement and train a VAE on the SVHN dataset using       PyTorch, with step-by-step instructions for building the model and visualizing results. Perfect for those looking to dive into generative models and image generation!"
    url: "https://github.com/ghazalehran/VAE-GenerativeModels"
feature_row3:
  - image_path: assets/images/mvarica.avif
    alt: "Image courtesy of unsplash"
    title: "Connectivity Analysis with MVAR and ICA"
    excerpt: "TThis project applies MVAR (Multivariate Autoregressive) modeling and ICA (Independent Component Analysis) to EEG time-series data to estimate connectivity measures like transfer functions and directed coherence. Check out the PDC Connectivity in the Tutorial (https://github.com/ppsp-team/HyPyP/blob/master/tutorial/getting_started.ipynb) section."
    url: "https://github.com/ppsp-team/HyPyP/blob/master/hypyp/mvarica.py"

    # btn_label: "Read More"
    # btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/portfolio-coming-2.webp
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
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

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="left" %}

<!-- {% include feature_row id="intro" type="center" %} -->

<!-- {% include feature_row layout="half"%}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %} -->

<!-- {% include feature_row id="feature_row4" type="center" %} -->

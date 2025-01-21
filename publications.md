---
title: ""
layout: single
permalink: /publications/
---

# Publications

---

<div class="section_pub">
### Towards Multi-Brain Decoding in Autism: A Self-Supervised Learning Approach  
**Authors:** Ghazaleh Ranjabaran, Quentin Moreau, Adrien Dubois, Guillaume Dumas  

<p class="abstract">
**Abstract:**  
This study introduces a self-supervised learning (SSL) approach to hyperscanning electroencephalography (EEG) data, targeting the identification of autism spectrum condition (ASC) during social interactions. Hyperscanning enables simultaneous recording of neural activity across interacting individuals, offering a novel path for studying brain-to-brain synchrony in ASC. Leveraging a large-scale, single-brain EEG dataset for SSL pretraining, we developed a multi-brain classification model fine-tuned with hyperscanning data from dyadic interactions involving ASC and neurotypical participants. The SSL model demonstrated superior performance (78.13% accuracy) compared to supervised baselines and logistic regression using spectral EEG biomarkers. These results underscore the efficacy of SSL in addressing the challenges of limited labeled data, enhancing EEG-based diagnostic tools for ASC, and advancing research in social neuroscience.
</p>

**Keywords:** Autism, Hyperscanning, EEG, Self-Supervised Learning, Inter-Brain Synchronization, Precision Psychiatry  

<p class="additional-info">
**Status:** Under review at *Taylor & Francis*<br>
**Pre-print:** [Link to pre-print](https://example.com/preprint-link)<br>
**Contact:** [guillaume.dumas@ppsp.team](mailto:guillaume.dumas@ppsp.team)
</p>
</div>

---

<div class="section_pub">
### A Neurodynamic Model of Inter-Brain Coupling in the Gamma Band  
**Authors:** Quentin Moreau, Lena Adel, Caitriona Douglas, Ghazaleh Ranjbaran, Guillaume Dumas  

<p class="abstract">
**Abstract:**  
The use of EEG to simultaneously record multiple brains (i.e., hyperscanning) during social interactions has led to the discovery of inter-brain coupling (IBC). IBC is defined as the neural synchronization between people and is considered to be a marker of social interaction. IBC has previously been observed across different frequency bands, including theta [4–7 Hz]. Given the proximity of this frequency range with behavioral rhythms, models have been able to combine IBC in theta with sensorimotor coordination patterns. Interestingly, empirical EEG-hyperscanning results also report the emergence of IBC in the gamma range [>30Hz]. Gamma oscillations’ fast and transient nature makes a direct link between gamma-IBC and other (much slower) interpersonal dynamics difficult, leaving gamma-IBC without a plausible model. However, at the intrabrain level, gamma activity is coupled with the dynamics of lower frequencies through cross-frequency coupling (CFC). This paper provides a biophysical explanation, through the simulation of neural data, for the emergence of gamma inter-brain coupling using a Kuramoto model of four oscillators divided into two separate (brain) units. By modulating both the degree of inter-brain coupling in the theta band (i.e., between-units coupling) and CFC (i.e., intraunit theta-gamma coupling), we provide a theoretical explanation of the observed gamma-IBC phenomenon in the EEG-hyperscanning literature.
</p>

**Keywords:** Cross-frequency coupling, EEG, Hyperscanning, Kuramoto model, Synchronization  

<p class="additional-info">
**DOI:** [10.1152/jn.00224.2022](https://doi.org/10.1152/jn.00224.2022)<br>
**PubMed:** [36070245](https://pubmed.ncbi.nlm.nih.gov/36070245)<br>
**Status:** Published in *Journal of Neurophysiology*<br>
**Pre-print:** [Link to pre-print](https://example.com/preprint-link)
</p>
</div>

---

<style>
.section_pub {
    margin-bottom: 40px;
    padding: 20px 10px;
    background-color: #f8f8f8;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

/* Title styling */
.section_pub h3 {
    font-family: 'Roboto', sans-serif;
    font-size: 1.5em;
    color: #2A5D84;
    margin-bottom: 10px;
}

/* Abstracts */
.abstract {
    font-size: 0.9em;
    line-height: 1.7;
    text-align: justify;
    color: #333;
}

/* Additional info (Status, DOI, etc.) */
.additional-info {
    font-size: 0.9em;
    margin-top: 10px;
    color: #555;
}

.additional-info a {
    color: #FF6A5D;  /* Accent color for links */
}

.section_pub hr {
    border: none;
    border-top: 2px solid #ddd;
    margin-top: 20px;
    margin-bottom: 20px;
}

/* Keywords */
.section_pub p strong {
    color: #2A5D84;
}
</style>

---
title: "NeuroScanAI Brain Tumor Detection System"
collection: portfolio
permalink: /portfolio/neuroscanai
order: 3
# date: 2024-03-01
---
<div style="display: flex; gap: 10px; flex-wrap: wrap;">
  <img src='/images/NeuroScan1.png' alt='DynPercept comparison 1' style='max-width: 280px;'>
  <img src='/images/NeuroScan2.png' alt='DynPercept comparison 2' style='max-width: 280px;'>
  <!-- <img src='/images/dynpercept-3.png' alt='DynPercept comparison 3' style='max-width: 280px;'> -->
</div>


**Technologies:** PyTorch, MobileNet, CNN, Streamlit, Hugging Face Spaces, Grad-CAM

Trained a brain tumor MRI classifier combining a **custom CNN architecture** and **MobileNet**, achieving **98% validation accuracy**

**Key contributions:**
- Built and trained a hybrid CNN + MobileNet architecture optimized for both accuracy and inference efficiency
- Implemented **Grad-CAM explainability** to visualize model attention regions, allowing clinicians to see which parts of an MRI scan influenced the model's prediction
- Deployed the model as an interactive web application using **Streamlit**, hosted on **Hugging Face Spaces** for public access and testing

This project emphasizes **clinical interpretability** alongside raw accuracy, a critical requirement for any AI system intended to support real-world medical decision-making, where black-box predictions alone are insufficient for trust and adoption.

[Live Demo](https://huggingface.co/spaces/MuhammadMubashir/NeuroAI_Tumor_Detection) [GitHub](https://github.com/Mubashir714/NeuroScan-AI-Brain-Tumor-Detection)

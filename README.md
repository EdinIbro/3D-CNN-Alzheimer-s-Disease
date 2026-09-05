# 3D CNN for Alzheimer's Disease Biomarker Classification

Alzheimer's disease (AD) is the most common cause of dementia and is characterized by progressive neurodegeneration associated with the accumulation of amyloid-$\beta$ (A$\beta$) plaques and tau neurofibrillary tangles. The identification of imaging biomarkers capable of detecting these pathological changes at early stages remains one of the major challenges in Alzheimer's disease research.

This thesis investigates the potential of deep learning techniques for the automatic classification of individuals according to their amyloid-$\beta$ and tau biomarker status using diffusion Magnetic Resonance Imaging (dMRI).

---

## 📌 Dataset & Methodology

* **Cohort:** 317 subjects from the Alzheimer's Disease Neuroimaging Initiative (ADNI), divided into biologically negative (A$\beta^{-}$/Tau$^{-}$) and positive (A$\beta^{+}$/Tau$^{+}$) groups.
* **Input Modalities:** Fractional Anisotropy (FA) and Mean Diffusivity (MD) 3D maps.
* **Model Architecture:** Three-Dimensional Convolutional Neural Network (3D CNN).
* **Validation Scheme:** 5-fold stratified cross-validation evaluated via Accuracy, Precision, Recall, and Macro F1-score.
* **Interpretability:** Gradient-based saliency maps to identify key brain regions driving network predictions.

---

## 📊 Results & Findings

* Both diffusion-derived biomarkers achieved solid classification performance, reaching accuracies close to **70%**.
* The **MD-based model** slightly outperformed the **FA-based model**.
* Gradient-based saliency maps consistently highlighted anatomically meaningful white matter regions, offering biologically plausible explanations.

---

## 💡 Conclusion

Diffusion MRI contains critical microstructural information for distinguishing amyloid-$\beta$ and tau status. Combining dMRI, 3D CNNs, and Explainable AI (XAI) presents a promising framework for the biological characterization of Alzheimer's disease.


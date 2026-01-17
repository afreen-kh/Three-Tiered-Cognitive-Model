# Development of a Three-Tiered Cognitive Hybrid Machine Learning Algorithm for Effective Diagnosis of Alzheimer’s Disease

**Afreen Khan**, S. Zubair  
*Journal of King Saud University – Computer and Information Sciences*, 2022  

🔗 **Paper (PDF):** https://www.sciencedirect.com/science/article/pii/S1319157822002439

---

## Overview

This repository accompanies the research article *“Development of a Three Tiered Cognitive Hybrid Machine Learning Algorithm for Effective Diagnosis of Alzheimer’s Disease”*, published in the *Journal of King Saud University – Computer and Information Sciences (2022)*.

The study proposes a **three-tiered cognitive hybrid machine learning framework** for Alzheimer’s disease (AD) diagnosis, integrating feature selection, multiple classifier learning, and stacked meta-modeling to improve diagnostic accuracy and robustness using cognitive and demographic data.

---

## Research Contribution

The core contributions of this work are:

- A **three-tiered cognitive learning architecture** designed for structured clinical decision-making  
- Integration of **feature selection and hybrid model stacking** to address data heterogeneity  
- A **meta-learning strategy** that aggregates predictions from multiple base classifiers  
- Demonstration of strong diagnostic performance across CN, MCI, and AD cohorts  

The framework emphasizes **model robustness and interpretability**, making it suitable for clinical decision-support contexts.

---

## Architecture Overview

The proposed three-tiered cognitive hybrid framework is designed to progressively refine diagnostic predictions through structured learning stages. The architecture integrates feature selection, hybrid classification, and meta-learning to improve robustness in Alzheimer’s disease diagnosis.

<p align="center">
  <img src="figures/Cognitive Model Framework.png" width="800"/>
</p>

<p align="center">
  <em>Figure 1: Three-tiered cognitive hybrid machine learning architecture for Alzheimer’s disease diagnosis.</em>
</p>

---

## Dataset Scope

The experimental evaluation was conducted using data obtained from the **Alzheimer’s Disease Neuroimaging Initiative (ADNI)**. 

- Cognitive and neuropsychological test scores  
- Demographic variables  
- Diagnostic labels (CN, MCI, AD)

All data usage complies with ADNI data access and sharing policies. No subject-level identifiers are distributed.

---

## Results Summary

The proposed three-tiered hybrid framework demonstrated progressive improvements in diagnostic performance across experimental stages. While individual classifiers achieved strong baseline results, the introduction of hybrid stacking and meta-learning significantly enhanced classification accuracy.

The final cognitive hybrid model achieved a maximum accuracy of **95.12%** in distinguishing cognitively normal, mild cognitive impairment, and Alzheimer’s disease subjects. Validation across multiple ADNI phases confirmed the robustness and generalizability of the approach.

---

## Intended Use

This repository is intended for:

- Readers of the associated publication seeking insight into the **hybrid modeling strategy**
- Researchers interested in **three-tier and stacked learning designs** for clinical ML
- Academic reference within Alzheimer’s disease and cognitive analytics research

The methodology may be re-implemented or extended in future studies using updated datasets or modeling techniques.

---

## Citation

If you use or reference this work, please cite:

```bibtex
@article{khan2022threetier,
  title={Development of a Three Tiered Cognitive Hybrid Machine Learning Algorithm for Effective Diagnosis of Alzheimer’s Disease},
  author={Khan, Afreen and Zubair, S.},
  journal={Journal of King Saud University – Computer and Information Sciences},
  year={2022},
  doi={10.1016/j.jksuci.2022.07.016}
}

# Tiny Embedded Intelligence Layer

**Tiny Embedded Intelligence Layer** (TEIL) is a cutting-edge framework designed to efficiently deploy machine learning (ML) models on resource-scarce embedded systems, such as Arduino, ARM Cortex-M, and similar devices. Developed as part of my PhD thesis, TEIL aims to bridge the gap between advanced ML techniques and the limitations of embedded systems, enabling real-time intelligence in environments with constrained resources.

TEIL offers seamless compatibility with popular machine learning libraries, including Scikit-Learn, and goes a step further by transpiling ML models into optimized C code, ensuring that these models can run effectively on devices with limited memory and processing power. In addition to supporting machine learning models, TEIL also provides capabilities for real-time data analysis, verification of ML models during runtime, and reducing the need for constant cloud communication, making it a versatile solution for autonomous, edge-based intelligence. With TEIL, embedded systems can harness the power of machine learning while maintaining performance and efficiency.

!!! note

    This project is under active development.

## Supported ML Algorithms

Because there are many ML algorithm that exist, this framework is limited to the following:

| Algorithm               | Task           | Documentation |
|:------------------------|:--------------:|:-------------:|
| Decision Tree           | Classification | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#decision-tree) |
| Decision Tree           | Regression     | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#decision-tree) |
| Multi-Layer Percepton   | Classification | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#multi-layer-percepton) |
| Multi-Layer Percepton   | Regression     | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#multi-layer-percepton) |
| SVM (Linear)            | Classification | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#support-vector-machines) |
| SVM (Linear)            | Regression     | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#support-vector-machines) |
| SVM (RBF)               | Classification | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#support-vector-machines) |
| SVM (RBF)               | Regression     | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#support-vector-machines) |
| SVM (Polynomial)        | Classification | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#support-vector-machines) |
| SVM (Polynomial)        | Regression     | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#support-vector-machines) |
| PCA                     | Dimensionality Reduction / Decomposition | []() |
| Gaussian Naive Bayes    | Classification | []() |
| Multinomial Naive Bayes | Classification | []() |
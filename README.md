# AI Tools

A curated collection of artificial intelligence, machine learning, deep learning, model interpretation, and GPU computing tools relevant to GeoAI, remote sensing, and geospatial applications.

The goal of this repository is to make useful AI tools easier to discover and compare across model development, training, evaluation, interpretation, and deployment workflows.

## Categories

- [Deep Learning Frameworks and Libraries](#deep-learning-frameworks-and-libraries)
- [Segmentation and Computer Vision](#segmentation-and-computer-vision)
- [Machine Learning](#machine-learning)
- [Model Interpretation and Explainability](#model-interpretation-and-explainability)
- [Image Evaluation and Similarity](#image-evaluation-and-similarity)
- [GPU and Accelerated Computing](#gpu-and-accelerated-computing)
- [Ensemble Learning and Model Combination](#ensemble-learning-and-model-combination)

---

## Deep Learning Frameworks and Libraries

| Resource | Description | Organization | Focus | Access |
|---|---|---|---|---|
| [PyTorch](https://pytorch.org/) | Open-source deep learning framework widely used for computer vision, remote sensing, and GeoAI model development. | PyTorch Foundation | Deep learning | Open source |
| [TorchGeo](https://github.com/microsoft/torchgeo) | PyTorch library designed specifically for geospatial machine learning and remote sensing datasets. | Microsoft / community | GeoAI / remote sensing | Open source |
| [segmentation_models.pytorch](https://github.com/qubvel-org/segmentation_models.pytorch) | PyTorch library providing semantic segmentation architectures, encoders, losses, and utilities. | Community project | Semantic segmentation | Open source |

---

## Segmentation and Computer Vision

| Resource | Description | Organization | Focus | Access |
|---|---|---|---|---|
| [segmentation_models.pytorch](https://github.com/qubvel-org/segmentation_models.pytorch) | Collection of segmentation architectures and pretrained encoders for image segmentation tasks. | Community project | Semantic segmentation | Open source |
| [Urban Tree Detection](https://github.com/jonathanventura/urban-tree-detection) | Tree detection workflow that can support object detection and annotation in aerial imagery. | Research project | Object detection / trees | Open source |
| [CanopyRS](https://github.com/hugobaudchon/CanopyRS) | Remote sensing framework and resources for canopy and tree-related deep learning workflows. | Research project | Tree crowns / canopy mapping | Open source |
| [SAM 1](https://github.com/facebookresearch/segment-anything) | Original Segment Anything Model for promptable image segmentation with strong zero-shot transfer capabilities. | Meta | Image segmentation / promptable vision | Open source |
| [SAM 2](https://ai.meta.com/research/sam2/) | Unified model for segmenting and tracking objects across images and videos using click, box, or mask prompts. | Meta | Image and video segmentation / tracking | Open model / research |
| [SAM 3](https://ai.meta.com/research/sam3/) | Unified model for detecting, segmenting, and tracking visual concepts using text, exemplar, and visual prompts. | Meta | Detection / segmentation / tracking | Open model / research |
| [SAM 3.1](https://ai.meta.com/blog/segment-anything-model-3/) | Updated SAM 3 release with improved inference efficiency, new checkpoints, and faster multi-object video tracking through Object Multiplex. | Meta | Detection / segmentation / multi-object tracking | Open model / research |
| [SAM 3D](https://ai.meta.com/research/sam3d/) | 3D reconstruction and spatial understanding models for people, objects, and scenes, with potential relevance to future GeoAI and LiDAR workflows. | Meta | 3D reconstruction / spatial vision | Research |

---

## Machine Learning

| Resource | Description | Organization | Focus | Access |
|---|---|---|---|---|
| [LightGBM](https://lightgbm.readthedocs.io/en/stable/) | Gradient boosting framework designed for efficient and scalable machine learning. | Microsoft / community | Gradient boosting | Open source |
| [scikit-learn](https://scikit-learn.org/) | General-purpose machine learning library providing classification, regression, clustering, preprocessing, and model evaluation tools. | scikit-learn | Machine learning | Open source |
| [Google Decision Forests](https://developers.google.com/machine-learning/decision-forests) | Documentation and tools for decision tree and forest-based machine learning methods. | Google | Tree-based machine learning | Open documentation / tools |

---

## Model Interpretation and Explainability

| Resource | Description | Organization | Focus | Access |
|---|---|---|---|---|
| [Partial Dependence](https://scikit-learn.org/stable/modules/partial_dependence.html) | Tools for visualizing how model predictions change with respect to one or more input features. | scikit-learn | Model interpretation | Open source |
| [Permutation Importance](https://scikit-learn.org/stable/modules/permutation_importance.html) | Model-agnostic method for estimating feature importance by measuring changes in model performance after feature permutation. | scikit-learn | Feature importance | Open source |
| [Variable Importances](https://developers.google.com/machine-learning/decision-forests/variable-importances) | Documentation covering several feature-importance measures used in decision forest models. | Google | Feature importance | Open documentation |
| [SHAP](https://christophm.github.io/interpretable-ml-book/shap.html) | Framework based on Shapley values for explaining individual and global machine learning predictions. | Interpretable Machine Learning | Explainable AI | Open |

A useful distinction is that partial dependence primarily describes the shape of a model's response to a feature, while permutation importance and other importance measures are more appropriate when evaluating a feature's contribution to predictive performance.

---

## Image Evaluation and Similarity

| Resource | Description | Organization | Focus | Access |
|---|---|---|---|---|
| [Image Similarity Measures](https://github.com/nekhtiari/image-similarity-measures) | Python implementations of image-quality and similarity metrics for comparing reconstructed, enhanced, or generated imagery. | Community project | Image evaluation | Open source |

---

## GPU and Accelerated Computing

| Resource | Description | Organization | Focus | Access |
|---|---|---|---|---|
| [RAPIDS](https://rapids.ai/) | GPU-accelerated ecosystem for data science and machine learning using NVIDIA GPUs. | NVIDIA | GPU data science | Open source |
| [cuDF](https://docs.rapids.ai/api/cudf/stable/) | GPU-accelerated dataframe library designed to provide pandas-like workflows on NVIDIA GPUs. | NVIDIA | GPU dataframes | Open source |
| [CuPy](https://cupy.dev/) | NumPy-compatible array library accelerated using NVIDIA CUDA GPUs. | Preferred Networks / community | GPU numerical computing | Open source |
| [RAPIDS cuDF and CuPy Guide](https://developer.nvidia.com/blog/10-minutes-to-data-science-transitioning-between-rapids-cudf-and-cupy-libraries/) | Practical guide for transitioning between RAPIDS cuDF and CuPy in GPU-accelerated data science workflows. | NVIDIA | GPU computing | Open |

---

## Ensemble Learning and Model Combination

| Resource | Description | Organization | Focus | Access |
|---|---|---|---|---|
| [Stacking to Improve Model Performance](https://medium.com/@brijesh_soni/stacking-to-improve-model-performance-a-comprehensive-guide-on-ensemble-learning-in-python-9ed53c93ce28) | Practical overview of stacking multiple machine learning models to improve predictive performance. | Community tutorial | Ensemble learning | Open article |

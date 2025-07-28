# FRIES: Framework for inconsistency estimation of saliency metrics

Abstract:
Saliency maps are widely used as a post-hoc approach to explain the decision-making process of Deep Learning (DL) based image classification models, but evaluating their fidelity remains a complex problem. While saliency metrics have been introduced to evaluate the fidelity of saliency maps, existing saliency metrics, such as perturbation-based saliency metrics, have been previously reported to demonstrate statistical inconsistency. Although inconsistencies have been noted in different works, there exists no mechanism for estimating the same, i.e., Inconsistency Estimation (IE). Our primary objective is to address this limitation, and therefore, we propose a framework to estimate the inconsistency of saliency metrics for any given DL model. The framework enables building IE models for estimating the inconsistency by employing a set of perturbation types and schemes. The framework’s modular architecture provides flexibility across (i) perturbation types (Inpainting, Uniform, and Gaussian blur), (ii) perturbation schemes (pixel-wise and patch-wise), (iii) learning mechanisms (Convolutional Neural Networks and Vision Transformers) and (iv) IE modeling techniques (bagging and boosting). Extensive experimental results are shown on three well-known DL architectures (Inception-V3, Xception, and ResNet-50) on three different public datasets, including the Imagenette, Oxford-IIIT Pets Dataset, and PASCAL VOC 2007, along with results on ViTs for Oxford-IIIT Pets Dataset, and PASCAL VOC 2007. With a comprehensive evaluation of seven different perturbation types that include two inpainting, two Gaussian blur (with kernel widths of 0.9 and 1.5), and three uniform perturbations, our work shows the effectiveness of the proposed approach in estimating inconsistency. Statistically founded tests such as repeated cross-validation and the Permutation Test further validate the idea of the proposed framework for estimating the inconsistency of saliency metrics across unseen perturbations, making it useful in real-world scenarios.








@Article{Bora_2025_PR,
  author    = {Bora, Revoti Prasad and Terh\"orst, Philipp and Veldhuis, Raymond and Ramachandra, Raghavendra and Raja, Kiran},
  title     = {FRIES: Framework for Inconsistency Estimation of Saliency Metrics},
  journal   = {Pattern Recognition},
  year      = {2025},
  volume    = {147},
  pages     = {112136},
  month     = {August},
  doi       = {10.1016/j.patcog.2025.112136}
}


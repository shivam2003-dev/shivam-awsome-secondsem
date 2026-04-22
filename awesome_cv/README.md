# Awesome Computer Vision

A curated roadmap of papers, libraries, datasets, courses, tools, projects, blogs, and benchmarks for modern Computer Vision.

## 🚀 Start Here (Beginner → Advanced path)

1. **Foundations:** Learn CNNs, feature extraction, and vision basics with [CS231n](https://cs231n.stanford.edu/) and [Deep Learning Book (Chapter 9)](https://www.deeplearningbook.org/contents/convnets.html).
2. **Classic breakthroughs:** Study [AlexNet](https://dl.acm.org/doi/10.1145/3065386), [VGG](https://arxiv.org/abs/1409.1556), and [ResNet](https://arxiv.org/abs/1512.03385).
3. **Detection & segmentation:** Read [Faster R-CNN](https://arxiv.org/abs/1506.01497), [Mask R-CNN](https://arxiv.org/abs/1703.06870), and [U-Net](https://arxiv.org/abs/1505.04597).
4. **Transformers in vision:** Understand [ViT](https://arxiv.org/abs/2010.11929), [Swin Transformer](https://arxiv.org/abs/2103.14030), and [DETR](https://arxiv.org/abs/2005.12872).
5. **Generative vision:** Explore [GANs](https://arxiv.org/abs/1406.2661), [StyleGAN](https://arxiv.org/abs/1812.04948), and [Latent Diffusion Models](https://arxiv.org/abs/2112.10752).
6. **Multimodal/foundation models:** Dive into [CLIP](https://arxiv.org/abs/2103.00020), [Segment Anything (SAM)](https://arxiv.org/abs/2304.02643), and [DINOv2](https://arxiv.org/abs/2304.07193).

## 📄 Papers (with links + 1-line why it matters)

- [ImageNet Classification with Deep Convolutional Neural Networks (AlexNet)](https://dl.acm.org/doi/10.1145/3065386) — Triggered the deep learning era in large-scale image recognition.
- [Very Deep Convolutional Networks for Large-Scale Image Recognition (VGG)](https://arxiv.org/abs/1409.1556) — Showed depth and simple convolution blocks can scale effectively.
- [Deep Residual Learning for Image Recognition (ResNet)](https://arxiv.org/abs/1512.03385) — Introduced residual connections enabling very deep networks.
- [Going Deeper with Convolutions (Inception)](https://arxiv.org/abs/1409.4842) — Improved efficiency using multi-branch convolution modules.
- [R-CNN](https://arxiv.org/abs/1311.2524) — Established region-based object detection with CNN features.
- [Fast R-CNN](https://arxiv.org/abs/1504.08083) — Made region-based detection faster and end-to-end trainable.
- [Faster R-CNN](https://arxiv.org/abs/1506.01497) — Added region proposal networks for near real-time detection quality.
- [Mask R-CNN](https://arxiv.org/abs/1703.06870) — Unified object detection and instance segmentation elegantly.
- [U-Net](https://arxiv.org/abs/1505.04597) — Became a standard architecture for semantic segmentation, especially biomedical imaging.
- [Feature Pyramid Networks (FPN)](https://arxiv.org/abs/1612.03144) — Improved multi-scale detection with top-down feature fusion.
- [You Only Look Once: Unified, Real-Time Object Detection (YOLO)](https://arxiv.org/abs/1506.02640) — Popularized single-shot real-time detection.
- [Vision Transformer (ViT)](https://arxiv.org/abs/2010.11929) — Demonstrated transformer architectures can dominate image classification.
- [Swin Transformer](https://arxiv.org/abs/2103.14030) — Introduced hierarchical windowed attention for dense vision tasks.
- [DETR](https://arxiv.org/abs/2005.12872) — Reframed object detection as direct set prediction with transformers.
- [CLIP](https://arxiv.org/abs/2103.00020) — Enabled strong zero-shot visual classification via language supervision.
- [Segment Anything (SAM)](https://arxiv.org/abs/2304.02643) — Introduced promptable segmentation at foundation-model scale.
- [Generative Adversarial Nets (GAN)](https://arxiv.org/abs/1406.2661) — Launched adversarial generative modeling for realistic synthesis.
- [A Style-Based Generator Architecture for GANs (StyleGAN)](https://arxiv.org/abs/1812.04948) — Improved controllability and quality in image synthesis.
- [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752) — Made diffusion-based image generation practical and scalable.

## 🧰 Libraries & Frameworks

- [PyTorch](https://github.com/pytorch/pytorch) — Primary deep learning framework used in vision research and production.
- [TensorFlow](https://github.com/tensorflow/tensorflow) — End-to-end ML framework with broad vision ecosystem support.
- [OpenCV](https://github.com/opencv/opencv) — Core computer vision library for classic and modern pipelines.
- [torchvision](https://github.com/pytorch/vision) — Vision models, datasets, and transforms for PyTorch workflows.
- [MMDetection](https://github.com/open-mmlab/mmdetection) — Comprehensive detection toolbox with strong baselines.
- [Detectron2](https://github.com/facebookresearch/detectron2) — Modular object detection and segmentation framework.
- [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) — Popular real-time detection and segmentation toolkit.

## 📊 Datasets

- [ImageNet](https://www.image-net.org/) — Foundational large-scale image classification dataset.
- [COCO](https://cocodataset.org/) — Standard benchmark for detection, segmentation, and captioning.
- [Pascal VOC](http://host.robots.ox.ac.uk/pascal/VOC/) — Classic dataset for detection and segmentation evaluation.
- [Open Images](https://storage.googleapis.com/openimages/web/index.html) — Large-scale dataset for detection, localization, and relationships.
- [Cityscapes](https://www.cityscapes-dataset.com/) — Urban scene understanding benchmark for segmentation.
- [KITTI](https://www.cvlibs.net/datasets/kitti/) — Autonomous driving benchmark for detection, depth, and tracking.

## 🎓 Courses

- [Stanford CS231n: Convolutional Neural Networks for Visual Recognition](https://cs231n.stanford.edu/) — Flagship deep learning for vision course.
- [DeepLearning.AI Computer Vision Specialization](https://www.coursera.org/specializations/computer-vision) — Practical CV workflows from fundamentals to applications.
- [fast.ai Practical Deep Learning for Coders](https://course.fast.ai/) — Hands-on computer vision training with modern tooling.

## 🛠 Tools / Ecosystem

- [Weights & Biases](https://wandb.ai/site) — Experiment tracking, artifact versioning, and visual comparison.
- [FiftyOne](https://github.com/voxel51/fiftyone) — Dataset curation, visualization, and model error analysis.
- [CVAT](https://github.com/cvat-ai/cvat) — Widely used annotation platform for computer vision datasets.
- [Label Studio](https://github.com/HumanSignal/label-studio) — Open-source data labeling for vision and multimodal tasks.
- [Roboflow](https://roboflow.com/) — Dataset management and deployment tools for vision pipelines.

## 🧪 Projects / Ideas

- Reproduce ResNet training on CIFAR-10 and analyze augmentation impacts.
- Compare DETR vs YOLO on COCO for mAP, latency, and compute trade-offs.
- Build an instance segmentation app with Mask R-CNN and interactive visualization.
- Fine-tune CLIP for domain-specific image retrieval and zero-shot tagging.
- Train a diffusion model on a small custom dataset and evaluate sample diversity.
- Create an active-learning loop for data labeling with uncertainty sampling.
- Build a real-time webcam detection system with model quantization for edge devices.
- Benchmark semantic segmentation models on Cityscapes with FPS-quality tradeoff charts.

## 📝 Blogs / Learning Resources

- [PyImageSearch](https://pyimagesearch.com/) — Practical tutorials for computer vision engineering.
- [Papers with Code (Computer Vision)](https://paperswithcode.com/area/computer-vision) — Task-wise SOTA papers, code, and leaderboards.
- [Distill](https://distill.pub/) — High-quality visual explainers for deep learning concepts.
- [OpenMMLab Docs](https://openmmlab.com/) — Production-grade vision framework guides and recipes.
- [The Gradient](https://thegradient.pub/) — Accessible articles on modern ML and vision trends.

## 📈 Benchmarks

- [ImageNet Leaderboards](https://paperswithcode.com/sota/image-classification-on-imagenet) — Standard benchmark for image classification progress.
- [COCO Detection Leaderboards](https://paperswithcode.com/sota/object-detection-on-coco) — Primary benchmark for object detection quality.
- [Cityscapes Semantic Segmentation](https://www.cityscapes-dataset.com/benchmarks/) — Standard benchmark for urban semantic segmentation.
- [KITTI Benchmarks](https://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=2d) — Widely used benchmark for autonomous-driving perception.

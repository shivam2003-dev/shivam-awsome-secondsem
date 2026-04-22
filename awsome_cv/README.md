# Shivam Awesome Computer Vision

A curated, production-aware roadmap for learning and building modern Computer Vision systems.

## 🧭 Learning Path (Beginner → Advanced)

1. **Vision fundamentals:** Learn CNN basics, convolutions, and feature hierarchies via [CS231n](https://cs231n.stanford.edu/) and the [Deep Learning Book (ConvNets)](https://www.deeplearningbook.org/contents/convnets.html).
2. **Classification era:** Study [AlexNet](https://arxiv.org/abs/1404.5997), [VGG](https://arxiv.org/abs/1409.1556), and [ResNet](https://arxiv.org/abs/1512.03385) for scaling depth and accuracy.
3. **Detection & segmentation:** Read [Faster R-CNN](https://arxiv.org/abs/1506.01497), [Mask R-CNN](https://arxiv.org/abs/1703.06870), and [U-Net](https://arxiv.org/abs/1505.04597).
4. **Transformer CV:** Move to [ViT](https://arxiv.org/abs/2010.11929), [Swin Transformer](https://arxiv.org/abs/2103.14030), and [DETR](https://arxiv.org/abs/2005.12872).
5. **Foundation and multimodal vision:** Learn [CLIP](https://arxiv.org/abs/2103.00020), [SAM](https://arxiv.org/abs/2304.02643), and [DINOv2](https://arxiv.org/abs/2304.07193).
6. **Generation:** Understand [GANs](https://arxiv.org/abs/1406.2661), [StyleGAN](https://arxiv.org/abs/1812.04948), and [Latent Diffusion](https://arxiv.org/abs/2112.10752).

## 📄 Papers (with links + 1-line insight)

- [Deep Residual Learning for Image Recognition (ResNet)](https://arxiv.org/abs/1512.03385) — Residual blocks made very deep visual networks trainable.
- [Faster R-CNN](https://arxiv.org/abs/1506.01497) — Unified region proposals and detection for strong two-stage object detection.
- [Mask R-CNN](https://arxiv.org/abs/1703.06870) — Added an instance mask head to detection with minimal architecture changes.
- [An Image is Worth 16x16 Words (ViT)](https://arxiv.org/abs/2010.11929) — Brought transformer pretraining recipes to vision classification.
- [End-to-End Object Detection with Transformers (DETR)](https://arxiv.org/abs/2005.12872) — Reframed detection as direct set prediction without NMS heuristics.
- [Learning Transferable Visual Models From Natural Language Supervision (CLIP)](https://arxiv.org/abs/2103.00020) — Enabled zero-shot image classification via language supervision.

## 🔗 Paper → Code Mapping

| Paper | Official / Best Implementation |
|---|---|
| [ResNet](https://arxiv.org/abs/1512.03385) | [torchvision models](https://github.com/pytorch/vision) |
| [Faster R-CNN](https://arxiv.org/abs/1506.01497) | [Detectron2](https://github.com/facebookresearch/detectron2) |
| [Mask R-CNN](https://arxiv.org/abs/1703.06870) | [matterport/Mask_RCNN](https://github.com/matterport/Mask_RCNN) |
| [ViT](https://arxiv.org/abs/2010.11929) | [google-research/vision_transformer](https://github.com/google-research/vision_transformer) |
| [DETR](https://arxiv.org/abs/2005.12872) | [facebookresearch/detr](https://github.com/facebookresearch/detr) |
| [CLIP](https://arxiv.org/abs/2103.00020) | [openai/CLIP](https://github.com/openai/CLIP) |

## 🧰 Libraries & Frameworks

- [PyTorch](https://github.com/pytorch/pytorch) — Dominant deep learning framework for CV research and production.
- [OpenCV](https://github.com/opencv/opencv) — Core library for classical vision and image/video processing.
- [torchvision](https://github.com/pytorch/vision) — Vision datasets, transforms, and pretrained model baselines.
- [MMDetection](https://github.com/open-mmlab/mmdetection) — Production-grade object detection toolbox with reproducible configs.
- [Detectron2](https://github.com/facebookresearch/detectron2) — Modular framework for detection and segmentation research.

## 📊 Datasets

- [ImageNet](https://www.image-net.org/) — Foundational large-scale dataset for visual classification.
- [COCO](https://cocodataset.org/) — Standard benchmark for detection, segmentation, and captioning.
- [Pascal VOC](http://host.robots.ox.ac.uk/pascal/VOC/) — Classic benchmark for detection and segmentation baselines.
- [Cityscapes](https://www.cityscapes-dataset.com/) — Urban-scene benchmark for semantic segmentation and perception.
- [KITTI](https://www.cvlibs.net/datasets/kitti/) — Core autonomous driving benchmark for 2D/3D tasks.

## 🎓 Courses

- [Stanford CS231n](https://cs231n.stanford.edu/) — Foundational course for modern deep visual recognition.
- [fast.ai Practical Deep Learning](https://course.fast.ai/) — Applied CV workflows from prototyping to deployment.
- [DeepLearning.AI Computer Vision Specialization](https://www.coursera.org/specializations/computer-vision) — Structured practical track on detection and segmentation.

## 🧪 Experiments (Actionable)

- **Detection trade-offs:** Benchmark YOLO vs Faster R-CNN on COCO for mAP/latency/cost.
- **Segmentation robustness:** Compare U-Net, DeepLab, and Mask R-CNN under resolution and domain shifts.
- **Vision-language retrieval:** Fine-tune CLIP on a domain corpus and evaluate zero-shot vs supervised retrieval.

## 🏗 CV System Design (IMPORTANT)

- **Data pipeline first:** Version data splits, augmentations, and annotation policies before model tuning.
- **Two-stage serving:** Use cheap classifier gates before expensive detector/segmentor passes for latency budgets.
- **Edge/cloud split:** Run lightweight preprocessing on-device and batch heavy inference in GPU services.

## ⚙️ CV Infra / Serving (DevOps angle)

- [NVIDIA Triton Inference Server](https://github.com/triton-inference-server/server) — Multi-framework model serving with dynamic batching.
- [TorchServe](https://github.com/pytorch/serve) — PyTorch-native serving with model archiving and handlers.
- [ONNX Runtime](https://github.com/microsoft/onnxruntime) — High-performance cross-platform inference runtime.
- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) — Scalable Python-native API serving for CV endpoints.

## 🧩 Use Cases

- **Autonomous driving:** Detection, segmentation, and tracking for perception stacks.
- **Medical imaging:** Lesion/organ segmentation with uncertainty-aware review loops.
- **Retail analytics:** Shelf monitoring, people flow analysis, and product recognition.
- **Industrial QA:** Defect detection with active learning and low-shot adaptation.

## 📈 Evaluation Metrics

- **Top-1 / Top-5 Accuracy** — Core classification quality metrics.
- **mAP** — Standard object detection metric across IoU thresholds.
- **IoU / Dice** — Primary segmentation overlap metrics.
- **FPS / P95 latency** — Deployment-readiness metrics for real-time inference.

## 🛠 Tools / Ecosystem

- [Weights & Biases](https://wandb.ai/site) — Experiment tracking, model comparison, and artifact management.
- [FiftyOne](https://github.com/voxel51/fiftyone) — Dataset visualization and error analysis for CV pipelines.
- [CVAT](https://github.com/cvat-ai/cvat) — Team annotation platform for image and video tasks.
- [Label Studio](https://github.com/HumanSignal/label-studio) — Flexible labeling platform for multimodal workflows.

## 📝 Blogs / Learning Resources

- [PyImageSearch](https://pyimagesearch.com/) — Practical implementation-oriented CV tutorials.
- [Papers with Code (Computer Vision)](https://paperswithcode.com/area/computer-vision) — SOTA papers, code, and benchmark leaderboards.
- [OpenMMLab Docs](https://openmmlab.com/) — Framework docs and recipes for production CV modeling.

## 📊 Benchmarks

- [ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet) — Canonical image classification benchmark.
- [COCO Detection](https://paperswithcode.com/sota/object-detection-on-coco) — Standard benchmark for detection quality.
- [Cityscapes Segmentation](https://www.cityscapes-dataset.com/benchmarks/) — Urban semantic segmentation leaderboard.

## ✍️ Shivam’s Notes (Insight Section)

- Data quality and labeling consistency usually matter more than model family swaps.
- For strict latency budgets, optimize preprocessing and batching before architecture changes.
- Foundation models help bootstrap, but domain-specific failure analysis decides production success.

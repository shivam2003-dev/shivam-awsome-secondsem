# Shivam Awesome Computer Vision

A curated, production-aware roadmap for learning and building modern Computer Vision systems.

## 🧭 Learning Path (Beginner → Advanced)

1. **Vision basics:** Learn CNN foundations with [CS231n](https://cs231n.stanford.edu/) and [Deep Learning Book (ConvNets)](https://www.deeplearningbook.org/contents/convnets.html).
2. **Classification milestones:** Study [AlexNet](https://arxiv.org/abs/1404.5997), [VGG](https://arxiv.org/abs/1409.1556), and [ResNet](https://arxiv.org/abs/1512.03385).
3. **Detection & segmentation:** Read [Faster R-CNN](https://arxiv.org/abs/1506.01497), [Mask R-CNN](https://arxiv.org/abs/1703.06870), [U-Net](https://arxiv.org/abs/1505.04597), and [DeepLabv3+](https://arxiv.org/abs/1802.02611).
4. **Vision transformers:** Move to [ViT](https://arxiv.org/abs/2010.11929), [Swin](https://arxiv.org/abs/2103.14030), and [DETR](https://arxiv.org/abs/2005.12872).
5. **Foundation vision:** Learn [CLIP](https://arxiv.org/abs/2103.00020), [SAM](https://arxiv.org/abs/2304.02643), [DINOv2](https://arxiv.org/abs/2304.07193), and [MAE](https://arxiv.org/abs/2111.06377).

## 📄 Papers (with links + 1-line insight)

- [AlexNet](https://arxiv.org/abs/1404.5997) — Triggered the deep learning era in large-scale visual recognition.
- [VGG](https://arxiv.org/abs/1409.1556) — Showed depth and simple blocks can scale effectively.
- [ResNet](https://arxiv.org/abs/1512.03385) — Residual connections enabled very deep network training.
- [FPN](https://arxiv.org/abs/1612.03144) — Multi-scale feature pyramids improved detection across object sizes.
- [Faster R-CNN](https://arxiv.org/abs/1506.01497) — Unified region proposal and detection in one trainable pipeline.
- [Mask R-CNN](https://arxiv.org/abs/1703.06870) — Added instance segmentation with minimal overhead.
- [U-Net](https://arxiv.org/abs/1505.04597) — Became a segmentation standard, especially in medical imaging.
- [ViT](https://arxiv.org/abs/2010.11929) — Demonstrated transformer scalability for image classification.
- [Swin Transformer](https://arxiv.org/abs/2103.14030) — Hierarchical windowed attention for dense CV tasks.
- [DETR](https://arxiv.org/abs/2005.12872) — Reframed detection as direct set prediction.
- [CLIP](https://arxiv.org/abs/2103.00020) — Enabled strong zero-shot visual classification.
- [SAM](https://arxiv.org/abs/2304.02643) — Brought promptable segmentation at foundation-model scale.
- [MAE](https://arxiv.org/abs/2111.06377) — Self-supervised masked autoencoding improved visual pretraining efficiency.
- [Latent Diffusion](https://arxiv.org/abs/2112.10752) — Made high-resolution diffusion generation practical.

## 🔗 Paper → Code Mapping

| Paper | Official / Best Implementation |
|---|---|
| [ResNet](https://arxiv.org/abs/1512.03385) | [torchvision](https://github.com/pytorch/vision) |
| [Faster R-CNN](https://arxiv.org/abs/1506.01497) | [Detectron2](https://github.com/facebookresearch/detectron2) |
| [Mask R-CNN](https://arxiv.org/abs/1703.06870) | [matterport/Mask_RCNN](https://github.com/matterport/Mask_RCNN) |
| [ViT](https://arxiv.org/abs/2010.11929) | [google-research/vision_transformer](https://github.com/google-research/vision_transformer) |
| [DETR](https://arxiv.org/abs/2005.12872) | [facebookresearch/detr](https://github.com/facebookresearch/detr) |
| [SAM](https://arxiv.org/abs/2304.02643) | [segment-anything](https://github.com/facebookresearch/segment-anything) |
| [CLIP](https://arxiv.org/abs/2103.00020) | [openai/CLIP](https://github.com/openai/CLIP) |

## 🧰 Libraries & Frameworks

- [PyTorch](https://github.com/pytorch/pytorch) — Dominant framework for CV research and production.
- [OpenCV](https://github.com/opencv/opencv) — Core image/video processing and classical vision library.
- [torchvision](https://github.com/pytorch/vision) — Models, datasets, and transforms for CV workflows.
- [MMDetection](https://github.com/open-mmlab/mmdetection) — Strong detection toolbox with reproducible recipes.
- [Detectron2](https://github.com/facebookresearch/detectron2) — Modular detection and segmentation framework.
- [Ultralytics](https://github.com/ultralytics/ultralytics) — Widely used YOLO training and deployment toolkit.
- [OpenMMLab](https://github.com/open-mmlab) — Broad CV ecosystem for detection, segmentation, and pose.

## 📊 Datasets

- [ImageNet](https://www.image-net.org/) — Foundational large-scale classification benchmark.
- [COCO](https://cocodataset.org/) — Standard benchmark for detection, segmentation, and captioning.
- [Pascal VOC](http://host.robots.ox.ac.uk/pascal/VOC/) — Classic detection/segmentation benchmark.
- [Cityscapes](https://www.cityscapes-dataset.com/) — Urban scene segmentation benchmark.
- [KITTI](https://www.cvlibs.net/datasets/kitti/) — Autonomous driving dataset for 2D/3D perception.
- [ADE20K](https://groups.csail.mit.edu/vision/datasets/ADE20K/) — Large scene parsing dataset.
- [Open Images](https://storage.googleapis.com/openimages/web/index.html) — Large-scale detection and relationship annotations.

## 🎓 Courses

- [Stanford CS231n](https://cs231n.stanford.edu/) — Foundational deep vision course.
- [fast.ai Practical Deep Learning](https://course.fast.ai/) — Applied model training and deployment workflows.
- [DeepLearning.AI Computer Vision Specialization](https://www.coursera.org/specializations/computer-vision) — Structured practical CV curriculum.

## 🧪 Experiments (Actionable)

- **Detector comparison:** Compare YOLO vs Faster R-CNN on COCO for mAP, P95 latency, and memory.
- **Segmentation robustness:** Evaluate U-Net/DeepLab/Mask R-CNN under domain shift and label noise.
- **Self-supervised boost:** Pretrain with MAE and measure fine-tuning gains on small labeled data.
- **Vision-language retrieval:** Fine-tune CLIP on domain data and compare zero-shot vs supervised retrieval.

## 🏗 CV System Design (IMPORTANT)

- **Data pipeline first:** Version annotations, splits, and augmentations before architecture tuning.
- **Serving tiers:** Use lightweight gates before expensive detectors/segmentors for strict latency SLOs.
- **Feedback loops:** Add human review and hard-negative mining for continuous model improvement.

## ⚙️ CV Infra / Serving (DevOps angle)

- [NVIDIA Triton Inference Server](https://github.com/triton-inference-server/server) — High-throughput multi-framework serving.
- [TorchServe](https://github.com/pytorch/serve) — PyTorch-native production model serving.
- [ONNX Runtime](https://github.com/microsoft/onnxruntime) — Cross-platform optimized inference runtime.
- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) — Scalable Python-native API serving.

## 🧩 Use Cases

- **Autonomous driving:** Detection/segmentation/tracking for perception stacks.
- **Medical imaging:** Segmentation and triage with uncertainty-aware quality control.
- **Retail analytics:** Shelf monitoring, traffic analysis, and checkout automation.
- **Industrial QA:** Defect detection with active-learning data loops.

## 📈 Evaluation Metrics

- **Top-1 / Top-5 Accuracy** — Core classification performance metrics.
- **mAP / AP50 / AP75** — Standard object detection performance metrics.
- **IoU / Dice** — Primary semantic/instance segmentation overlap metrics.
- **FPS / P95 latency** — Deployment-readiness metrics for real-time systems.

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

- [Weights & Biases](https://wandb.ai/site) — Experiment tracking and artifact management.
- [FiftyOne](https://github.com/voxel51/fiftyone) — Dataset curation and model error analysis.
- [CVAT](https://github.com/cvat-ai/cvat) — Team-friendly annotation platform.
- [Label Studio](https://github.com/HumanSignal/label-studio) — Flexible labeling across modalities.

## 🧾 Awesome CV Collections

- [jbhuang0604/awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) — Popular curated CV papers, projects, and resources.
- [amusi/awesome-object-detection](https://github.com/amusi/awesome-object-detection) — Focused object detection papers and code links.

## 📝 Blogs / Learning Resources

- [PyImageSearch](https://pyimagesearch.com/) — Practical implementation-oriented CV tutorials.
- [Papers with Code (CV)](https://paperswithcode.com/area/computer-vision) — SOTA papers, code, and leaderboards.
- [OpenMMLab Docs](https://openmmlab.com/) — Framework docs and production recipes.

## 📊 Benchmarks

- [ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet) — Canonical image classification benchmark.
- [COCO Detection](https://paperswithcode.com/sota/object-detection-on-coco) — Standard detection leaderboard.
- [Cityscapes](https://www.cityscapes-dataset.com/benchmarks/) — Urban semantic segmentation benchmark.

## ✍️ Shivam’s Notes (Insight Section)

- Data quality and labeling consistency usually matter more than architecture swapping.
- Latency wins often come from preprocessing/batching and model compilation, not just smaller backbones.
- Domain-specific error analysis is the fastest path to measurable production gains.

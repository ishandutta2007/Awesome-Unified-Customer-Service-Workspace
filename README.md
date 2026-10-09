# Awesome-Visual-AI-Computer-Vision

# Top Visual AI & Computer Vision Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Image Recognition, Object Detection & Self-Hosted Vision Models*  
**Last updated: October 2026**

This repository tracks notable **commercial computer vision platforms** and **open-source projects** that detect, classify, and segment visual content — from fully managed cloud vision APIs to self-hosted detection frameworks and multimodal foundation models.

**Examples** include Salesforce Einstein Vision, Google Cloud Vision, AWS Rekognition, Azure Computer Vision, Clarifai, Roboflow, Landing AI, Chooch AI, AlwaysAI, and SuperAnnotate (the category leaders).

**Open-source emphasis**: Visual AI and computer vision is one of the strongest open-source domains. **Ultralytics YOLO** leads with 45,000+ GitHub stars as the de facto real-time detection framework — YOLO11 and YOLO26 deliver 40.9 mAP at nano scale with NMS-free inference and edge deployment . **Detectron2** and **MMDetection** power research-grade detection and segmentation from Meta and OpenMMLab . **OpenCV** remains the foundational vision library with 80,000+ stars . **SAM 2**, **GroundingDINO**, and **Florence-2** bring promptable segmentation and open-vocabulary detection . **PaddleOCR** and **EasyOCR** handle text extraction, while **Depth Anything** and **RAFT** cover depth estimation and optical flow . This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Google Cloud Vision](https://cloud.google.com/vision)**  
  **Google's managed computer vision API** — image labeling, face detection, OCR, explicit content detection, and logo detection . **AutoML Vision** for custom model training . **Best for GCP-native vision applications** .

- **[AWS Rekognition](https://aws.amazon.com/rekognition/)**  
  **AWS's managed image and video analysis** — object and scene detection, facial analysis, text detection, and content moderation . **Rekognition Custom Labels** for custom models . **Best for AWS-native vision workloads** .

- **[Azure Computer Vision](https://azure.microsoft.com/en-us/products/ai-services/ai-vision)**  
  **Microsoft's vision services** — image analysis, OCR, face detection, and spatial analysis . **Florence-2 foundation model integration** . **Best for Microsoft-centric vision applications** .

- **[Salesforce Einstein Vision](https://www.salesforce.com/)**  
  **Salesforce's vision AI** — image classification and object detection integrated with Salesforce . **Best for CRM-integrated vision** .

- **[Clarifai](https://www.clarifai.com/)**  
  **Full-stack AI platform with computer vision** — pre-trained models, custom training, and edge deployment . **Best for enterprise vision applications** .

- **[Roboflow](https://roboflow.com/)**  
  **Computer vision platform** — dataset management, annotation, training, and deployment . **Best for developers building custom vision models** .

- **[Landing AI](https://landing.ai/)**  
  **Andrew Ng's visual inspection AI** — end-to-end AI for manufacturing quality control . **Best for industrial visual inspection** .

- **[Chooch AI](https://chooch.ai/)**  
  **Vision AI platform** — pre-built and custom vision models for enterprise . **Best for enterprise video and image analytics** .

- **[AlwaysAI](https://www.alwaysai.co/)**  
  **Computer vision platform** — build, deploy, and manage vision applications at the edge . **Best for edge vision deployment** .

- **[SuperAnnotate](https://www.superannotate.com/)**  
  **Training data platform** — annotation, QA, and data curation for computer vision and NLP . **Best for high-quality dataset creation** .

## Open-Source GitHub Projects

### Real-Time Detection

- **[Ultralytics YOLO](https://github.com/ultralytics/ultralytics)**  
  **The de facto standard for real-time object detection**, AGPL-3.0 licensed with **45,000+ GitHub stars** . **YOLO11 and YOLO26** — YOLO26 delivers **40.9 mAP50-95 at nano scale** with NMS-free inference and edge-first design (January 2026) . **Supports detection, segmentation, pose estimation, tracking, and classification** . **YOLOE-26x** brings open-vocabulary detection . **Export to ONNX, TensorRT, CoreML, TFLite, and more** . **Note**: AGPL-3.0 requires source disclosure for closed-source products; Enterprise license available . **Best for real-time detection and edge deployment** .

- **[Detectron2 (Meta)](https://github.com/facebookresearch/detectron2)**  
  **Meta's research-grade detection and segmentation framework**, Apache-2.0 licensed with **30,000+ GitHub stars** . **Modular architecture for object detection, instance segmentation, keypoint detection, and panoptic segmentation** . **The reference implementation for many research papers** . **Best for research and high-accuracy detection** .

- **[MMDetection (OpenMMLab)](https://github.com/open-mmlab/mmdetection)**  
  **Comprehensive detection toolbox from OpenMMLab**, Apache-2.0 licensed with **30,000+ GitHub stars** . **Modular design with 100+ pre-trained models** . **Supports detection, instance segmentation, and panoptic segmentation** . **Best for benchmarking and model zoo access** .

### Vision Foundation Models

- **[Segment Anything 2 (SAM 2)](https://github.com/facebookresearch/sam2)**  
  **Meta's promptable segmentation for images and video**, Apache-2.0 licensed . **Zero-shot segmentation** with point, box, or mask prompts . **Streaming memory for video object tracking** . **Best for interactive and automatic segmentation** .

- **[GroundingDINO](https://github.com/IDEA-Research/GroundingDINO)**  
  **Open-set object detection with language prompts**, Apache-2.0 licensed . **Detects any object described by text** — no fixed class list . **Integrates with SAM for grounded segmentation** . **Best for open-vocabulary detection** .

- **[Florence-2 (Microsoft)](https://huggingface.co/microsoft/Florence-2-large)**  
  **Unified vision foundation model**, MIT licensed . **Handles captioning, detection, segmentation, OCR, and grounding** with a single model . **Prompt-based task specification** . **Best for multi-task vision applications** .

- **[Depth Anything](https://github.com/LiheYoung/Depth-Anything)**  
  **State-of-the-art monocular depth estimation**, Apache-2.0 licensed . **Robust zero-shot depth** across diverse scenes . **V2 adds finer detail and metric depth** . **Best for depth estimation** .

- **[RAFT (Optical Flow)](https://github.com/princeton-vl/RAFT)**  
  **Recurrent All-Pairs Field Transforms for optical flow**, BSD-3-Clause licensed . **State-of-the-art optical flow estimation** . **Best for motion analysis** .

### OCR & Text Extraction

- **[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)**  
  **The leading open-source OCR toolkit**, Apache-2.0 licensed with **45,000+ GitHub stars** . **PaddleOCR-VL-1.6** achieves **96.33% on OmniDocBench v1.6** — state-of-the-art among open-source solutions . **100+ languages supported** . **Best for multilingual OCR** .

- **[EasyOCR](https://github.com/JaidedAI/EasyOCR)**  
  **Ready-to-use OCR with 80+ languages**, Apache-2.0 licensed with **25,000+ GitHub stars** . **Simple Python API** . **Best for quick OCR integration** .

- **[Tesseract OCR](https://github.com/tesseract-ocr/tesseract)**  
  **The foundational open-source OCR engine**, Apache-2.0 licensed with **60,000+ GitHub stars** . **100+ languages supported** . **Best for general OCR** .

### Foundational Libraries

- **[OpenCV](https://github.com/opencv/opencv)**  
  **The foundational computer vision library**, Apache-2.0 licensed with **80,000+ GitHub stars** . **Image processing, feature detection, object tracking, and camera calibration** . **The building block for most vision applications** . **Best for classical computer vision** .

- **[scikit-image](https://github.com/scikit-image/scikit-image)**  
  **Image processing in Python**, BSD-3-Clause licensed with **6,000+ GitHub stars** . **Filters, transforms, and feature extraction** . **Best for scientific image analysis** .

- **[Kornia](https://github.com/kornia/kornia)**  
  **Differentiable computer vision for PyTorch**, Apache-2.0 licensed with **10,000+ GitHub stars** . **GPU-accelerated vision operations** . **Best for deep learning vision pipelines** .

- **[Albumentations](https://github.com/albumentations-team/albumentations)**  
  **Fast image augmentation library**, MIT licensed with **14,000+ GitHub stars** . **50+ augmentation techniques** . **Best for training data augmentation** .

### Additional Strong Open-Source Options

- **YOLOv5** — Original Ultralytics implementation (predecessor to YOLO11) .
- **YOLOX** — Anchor-free YOLO variant from Megvii .
- **EfficientDet** — Google's efficient detection architecture .
- **RetinaNet** — Focal loss for dense detection .
- **Mask R-CNN** — Instance segmentation reference implementation .
- **U-Net** — Semantic segmentation for biomedical images .
- **DeepLab** — Google's semantic segmentation .
- **Segment Anything (SAM)** — Original promptable segmentation .
- **CLIP** — Contrastive language-image pretraining .
- **BLIP-2** — Vision-language pretraining .
- **LLaVA** — Large language-and-vision assistant .
- **Grounding DINO + SAM** — Combined open-vocabulary detection and segmentation .

**Frameworks for building custom visual AI and computer vision solutions**: Combine **Ultralytics YOLO** for real-time detection and edge deployment . Use **Detectron2** or **MMDetection** for research-grade detection and segmentation . Deploy **SAM 2** for promptable segmentation and video object tracking . Integrate **GroundingDINO** for open-vocabulary detection and **Florence-2** for multi-task vision . Choose **PaddleOCR** or **Tesseract** for text extraction . Use **Depth Anything** for depth estimation and **RAFT** for optical flow . Build on **OpenCV** for classical vision operations and **Kornia** for differentiable pipelines . Note that true managed vision APIs with global infrastructure, pre-trained industry models, and vendor-supported SLAs (Google Cloud Vision, AWS Rekognition, Azure Computer Vision) remain primarily commercial territory; open-source stacks provide strong detection, segmentation, and multimodal foundations that require integration for complete visual AI deployments.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Visual AI platforms process images and video that may contain PII or sensitive content. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA, BIPA).
- **License considerations**: Ultralytics YOLO uses AGPL-3.0 — closed-source products must purchase an Enterprise license or disclose source code . Detectron2 uses Apache-2.0, PaddleOCR uses Apache-2.0, OpenCV uses Apache-2.0, and SAM 2 uses Apache-2.0. Verify licensing against your use case before committing.
- **Model accuracy varies by domain** — benchmark results (e.g., 40.9 mAP for YOLO26) may not reflect performance on your specific data . Validate on your own datasets before deployment.
- **Facial recognition and biometric processing** carry significant legal and ethical obligations. Verify local regulations before deployment .
- The open-source ecosystem provides strong detection, segmentation, and multimodal foundations, but **managed infrastructure, pre-trained industry models, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for computer vision engineers, ML practitioners, and organizations seeking visual AI sovereignty.**  
Let's make visual AI and computer vision more open, transparent, and accessible.

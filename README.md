<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=slice&section=header&color=30D5C8&height=140&animation=fadeIn&text=Hi,%20I'm%20Sijeong.&fontColor=ffffff&fontSize=42&fontAlign=65&fontAlignY=35" alt="header">
</p>

<p align="center">
  <b>AI Engineer & Researcher</b><br/>
  I build vision, multimodal, and generative AI systems from research to deployment, with a focus on robust real-world inference, reproducible experimentation, and practical user-facing products.
</p>

<p align="center">
  <a href="mailto:ssonge413@gmail.com"><img alt="Gmail" src="https://img.shields.io/badge/Email-ssonge413%40gmail.com-EA4335?logo=gmail&logoColor=white&style=flat-square"></a>
  <a href="https://www.linkedin.com/in/sijeong-kim"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Sijeong%20Kim-0A66C2?logo=linkedin&logoColor=white&style=flat-square"></a>
  <a href="https://github.com/sijeong-kim"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-sijeong--kim-000000?logo=github&logoColor=white&style=flat-square"></a>
</p>

---

### 🔭 Interests
`Generative AI` · `Multimodal AI` · `Computer Vision` · `3D Vision` · `Edge AI` · `ML Systems`

### 🛠 Tech
`Python` · `PyTorch` · `C/C++` · `CUDA` · `TensorRT` · `FastAPI` · `Docker` · `AWS` · `Linux`

---

## ⭐ Selected Projects

### 1) Repulsive 3D Gaussian Splatting
**MSc thesis project** on improving diversity in diffusion-based text-to-3D generation with feature-space repulsion on top of 3D Gaussian Splatting.

- Introduced repulsive loss in **DINOv2 / CLIP feature space**
- Improved **semantic diversity from 0.132 to 0.262 (~98%)**
- Preserved quality with near-constant fidelity (**0.391 → 0.397**) and high cross-view consistency (**0.853 → 0.828**)
- Validated results through **PCA analysis** and a **human perceptual study (n = 41)**
- Built a scalable **N-parallel** experimental pipeline with modest efficiency overhead

---

### 2) Tori — Personalized AI Fairytale Book Platform
**Capstone project** for generating and sharing personalized fairytale books from children's diary inputs.

- Built an end-to-end multimodal pipeline: **diary → story, illustrations, and background music**
- Integrated **HyperCLOVA X**, **ChatGPT**, **DALL·E**, and **MusicGen**
- Led AI development and designed the optimized AI serving stack with **FastAPI**, **Nginx**, and asynchronous parallel processing
- Worked within a service architecture using **React/Vercel**, **Spring**, **Redis**, and **AWS S3**
- Explored **Stable Diffusion v1.4 + LoRA / Textual Inversion** for style-consistent illustration generation under limited GPU resources

---

### 3) Truncation-Robust 3D Human Pose Estimation
**Research project** on robust monocular 3D human pose estimation under truncation and occlusion.

- Combined a **volumetric heatmap-based 2D pose detector** with temporal **2D-to-3D lifting models**
- Built a reproducible truncation benchmark across **VideoPose3D, MHFormer, MixSTE, and P-STMO**
- Evaluated robustness under **random, fixed, and moving masking** settings on **Human3.6M**
- Achieved strong robustness gains under truncation across major backbones in MPJPE benchmarks

---

### 4) Real-Time Object Detection and Gesture-Controlled Robotics
**Edge AI project** for user-following and gesture-based control of a medical assistive robot on **NVIDIA Jetson Xavier**.

- Built a lightweight on-device perception pipeline with **YOLOv4-tiny + TensorRT**
- Used **DeepSORT** for reliable user tracking and re-identification in crowded indoor scenes
- Implemented **body / hand skeleton estimation** with **trt_pose** and **trt_pose_hand**
- Added **depth-aware hand separation** and gesture-based state control using RGB-D sensing
- Validated the full pipeline at **~10–15 FPS** on Jetson

---

### 5) Real-time AKI Prediction System
**Team project** for deploying an acute kidney injury prediction model in a realistic hospital-style streaming environment.

- Built an inference pipeline to process **HL7/MLLP** admission and lab messages in real time
- Designed the real-time inference flow by combining new creatinine test results with patient history
- Sent automated HTTP alerts to a pager system on positive predictions
- Contributed Docker-based runtime setup, **HL7/MLLP protocol handling**, and **Kubernetes deployment**
- Detected **15/15 positive AKI cases** in scenario validation with **~0.06 s average inference latency**

---

## 📄 Education
- **MSc Computing (Artificial Intelligence and Machine Learning), Imperial College London — Distinction**  
  Thesis: *Diversify Guided 3D Generation via Repulsive 3D Gaussian Splatting*

- **BSc Computer Science and Engineering, Ewha Womans University — Summa Cum Laude (GPA: 4.2/4.3)**

---

## 🌱 Currently Focusing On
- Building reliable and deployable AI systems
- Expanding from vision and 3D AI into broader multimodal and generative AI applications
- Turning research prototypes into practical user-facing products

> **Note:** Some project repositories and materials are kept private due to research, privacy, or collaboration constraints. If helpful for evaluation, I would be happy to share additional technical details or selected materials upon request.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=wave&section=footer&color=CAFCEA&height=120" alt="footer">
</p>

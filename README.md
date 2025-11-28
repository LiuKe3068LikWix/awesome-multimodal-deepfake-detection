# 🔥 Awesome Multimodal Deepfake Detection  
A curated list of **multimodal deepfake detection** resources — datasets, papers, benchmarks, taxonomies, and open-source code.

Focus on **audio–visual / multimodal deepfake forensics**, including but not limited to:
- Face manipulation (visual forgery) detection  
- Lip-sync / audio-visual synchronization deepfake detection  
- Audio spoofing detection (voice cloning, TTS, etc.)  
- Cross-modal consistency & fusion-based detection  
- Self-/contrastive-learning based A/V representation detection  

---

## 📌 Contents
- [📚 Papers](#-papers)  
- [📀 Datasets](#-datasets)  
- [🏆 Leaderboard & Recent Advances](#-leaderboard--recent-advances)  
- [🧩 Code Repositories](#-open-source-code)  

---

# 📚 Papers  

| Year | Title / Summary | Modality / Note / Contribution |
|------|----------------|-------------------------------|
| 2025 | KLASSify to Verify: Audio-Visual Deepfake Detection Using SSL-based Audio and Handcrafted Visual Features  [Paper](https://arxiv.org/abs/2508.07337?utm_source=chatgpt.com) | Audio-Visual – Self-supervised + interpretable features |
| 2025 | Multiscale Adaptive Conflict-Balancing Model For Multimedia Deepfake Detection (MACB-DF)  [Paper](https://arxiv.org/abs/2505.12966?utm_source=chatgpt.com) | Audio-Visual joint fusion, contrastive + cross-modal fusion |
| 2025 | ERF-BA-TFD+: A Multimodal Model for Audio-Visual Deepfake Detection  [Paper](https://arxiv.org/abs/2508.17282?utm_source=chatgpt.com) | Audio-Visual fusion with long-range modeling, evaluated on realistic datasets |
| 2025 | Audio-Visual Deepfake Detection With Local Temporal Inconsistencies  [Paper](https://arxiv.org/abs/2501.08137?utm_source=chatgpt.com) | Temporal-inconsistency detection in A/V deepfakes |
| 2024 | Audio–visual deepfake detection using articulatory representation learning (ART-AVDF)  [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1077314224002145?utm_source=chatgpt.com) | Audio-visual articulatory representation + fusion for forgery detection |
| 2023 | DF-TransFusion: Multimodal Deepfake Detection via Lip-Audio Cross-Attention & Facial Self-Attention  [Paper](https://www.emergentmind.com/papers/2309.06511?utm_source=chatgpt.com) | Lip-audio cross attention + visual attention fusion, strong results on DFDC etc. |


---

## 📀 Datasets  

| Dataset / Source | Modality(s) | Approx. Size / Notes | Description / Use Case |
|------------------|-------------|----------------------|------------------------|
| **DFDC** | Audio-Visual (video + audio) | Large-scale (100k+ videos) | Widely used benchmark for face-swap / manipulated video detection |
| **FaceForensics++** | Visual (video) | ~1,000+ originals + manipulated versions | Classic face manipulation dataset (DeepFakes, FaceSwap, Face2Face, NeuralTextures)  [DFDC](https://www.mdpi.com/2227-7390/13/12/2024?utm_source=chatgpt.com) |  
| **Celeb-DF (v2)** | Visual | 590 real + ~5,639 deepfake videos | Higher-quality deepfakes for realistic evaluation  [Celeb-DF](https://cse.buffalo.edu/~siweilyu/celeb-deepfakeforensics.html?utm_source=chatgpt.com) |  
| **ASVspoof** | Audio (speech spoof) | Varies (depending on challenge) | Audio spoofing / synthesized voice detection — useful for audio-only or multimodal pipelines  [ASVspoof](https://proceedings.iclr.cc/paper_files/paper/2025/file/08f9de0232c0b485110237f6e6cf88f1-Paper-Conference.pdf?utm_source=chatgpt.com) |  
| **AV-Deepfake1M / Recent Multimodal Datasets** | Audio-Visual | New multimodal deepfake datasets (2024/2025) | Datasets designed for audio-visual forged video detection across modalities  [Dataset](https://proceedings.iclr.cc/paper_files/paper/2025/file/08f9de0232c0b485110237f6e6cf88f1-Paper-Conference.pdf?utm_source=chatgpt.com) |  
| **DeeperForensics-1.0** | Visual | Large-scale realistic face forgery dataset | Focus on robustness under distortions / real-world conditions  [DeeperForensics-1.0](https://www.sciencedirect.com/science/article/abs/pii/S0957417424030173?utm_source=chatgpt.com) |  

---

## 🏆 Leaderboard & Recent Advances (2023–2025)  
Some of the state-of-the-art / promising multimodal deepfake detection works:

- **KLASSify to Verify** (2025): uses SSL-based audio + handcrafted visual features for robust detection.  [KLASSify to Verify](https://arxiv.org/abs/2508.07337?utm_source=chatgpt.com)  
- **MACB-DF** (2025): addresses modality imbalance and cross-modal fusion in audio-visual detection.  [MACB-D](https://arxiv.org/abs/2505.12966?utm_source=chatgpt.com)  
- **ERF-BA-TFD+** (2025): enhanced-fusion model for long-range dependency modeling in A/V deepfakes.  [ERF-BA-TFD+](https://arxiv.org/abs/2508.17282?utm_source=chatgpt.com)  
- **ART-AVDF** (2024): articulatory representation learning for A/V deepfake detection; improves over multiple benchmarks.  [ART-AVDF](https://www.sciencedirect.com/science/article/abs/pii/S1077314224002145?utm_source=chatgpt.com)  
- **DF-TransFusion** (2023): cross-attention + self-attention fusion for lip-audio & visual signals; delivers strong AUC / F1 performance.  [DF-TransFusion](https://www.emergentmind.com/papers/2309.06511?utm_source=chatgpt.com)  

---

## 🧩 Open-Source Code / Implementations (include recent ones)  

| Task / Method | Repository / Link / Note |
|---------------|--------------------------|
| DF-TransFusion (A/V multimodal) | [DF-TransFusion](https://www.emergentmind.com/papers/2309.06511?utm_source=chatgpt.com) |
| Typical visual-only detection (FaceForensics++, Celeb-DF) | Many repos (see dataset pages) |
| Audio-only / spoofing detection (ASVspoof) | See ASVspoof official / community repos |
| Multimodal detection with articulatory / fusion (e.g. ART-AVDF) | [Multimodal detection](https://www.sciencedirect.com/science/article/abs/pii/S1077314224002145?utm_source=chatgpt.com) |

---

# 🌍 Awesome Geospatial Embeddings 

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](../../pulls)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](../../graphs/commit-activity)

A curated list of papers that **define, analyze, or evaluate geospatial embeddings** — how spatial, temporal, or semantic Earth data are represented in embedding space, and how those embeddings behave or are applied.

> This list intentionally excludes generic pretraining or downstream models where embeddings are incidental.

> **Note:** In this list, the *Dataset* column refers to publicly released **embedding datasets or products**, not the datasets used for model training or inference.

---

## 📖 1. Surveys and Concept Papers
*Reviews, taxonomies, and position papers discussing geospatial embeddings conceptually or systematically.*


| Abbr. | Title | Publication | Paper |
|-------|--------|-------------|--------|
| **LossyNeuralCompression** | **Lossy Neural Compression for Geospatial Analytics: A Review** | GRSM 2025 | [Lossy Neural Compression](https://ieeexplore.ieee.org/document/10934749) |
| **EarthEmbeddings** | **Earth Embeddings: Harnessing the Information in Earth Observation Data with Machine Learning** | SIGGRAPH Frontiers 2025 | [Earth Embeddings](https://dl.acm.org/doi/full/10.1145/3736539.3754446) |

---

## 📡 2. Location Embeddings
*Methods that learn embeddings for coordinates, regions, or spatial contexts.*


| Abbr. | Title | Publication | Paper | Code | Dataset |
|-------|--------|-------------|--------|------|------|
| **GeoCLIP** | **GeoCLIP: Clip-Inspired Alignment between Locations and Images for Effective Worldwide Geo-localization** | NeurIPS 2023 | [GeoCLIP](https://arxiv.org/abs/2309.16020) | [Code](https://github.com/VicenteVivan/geo-clip) | null |
| **LocationEncoder** | **Geographic Location Encoding with Spherical Harmonics and Sinusoidal Representation Networks** | ICLR 2024 | [LocationEncoder](https://arxiv.org/abs/2310.06743) | [Code](https://github.com/marccoru/locationencoder) | null |
| **SatCLIP** | **SatCLIP: Global, General-Purpose Location Embeddings with Satellite Imagery** | AAAI 2025 | [SatCLIP](https://ojs.aaai.org/index.php/AAAI/article/view/32457) | [Code](https://github.com/microsoft/satclip) | null |


---
## 🖼 3. Product Embeddings
*Methods that embed or represent individual data products into latent spaces suitable for geospatial analysis.*

| Abbr. | Title | Publication | Paper | Code | Dataset |
|-------|--------|-------------|--------|------|------|
| **CLAY Embeddings** | **Clay Model v0 Embeddings** | Source Cooperative 2024 | null | [Code](https://github.com/Clay-foundation) | [Dataset](https://source.coop/clay/clay-model-v0-embeddings) |
| **Major TOM Embeddings** | **Global and Dense Embeddings of Earth: Major TOM Floating in the Latent Space** | Arxiv 2024 | [Arxiv Paper](https://arxiv.org/abs/2412.05600) | [Code](https://github.com/ESA-PhiLab/Major-TOM) | [Dataset](https://huggingface.co/Major-TOM) |
| **Earth Genome Embeddings** | **Embeddings for all** | null | [Medium 2025](https://medium.com/earthrisemedia/embeddings-for-all-0e0a29415b26) | null | [Dataset](https://source.coop/earthgenome/earthindexembeddings) |


<!-- ## ⏱️ 4. Temporal / Time-Series Embeddings
*Methods that embed or represent temporal sequences (e.g., satellite time-series) into latent spaces suitable for geospatial analysis.* -->

## 🧩 4. Aggregate / Multi-Observation Embeddings  
*Methods that aggregate multiple observations — over time, sensors, or modalities — into a unified embedding representation (e.g., temporal sequences or multimodal stacks).*

| Abbr. | Title | Publication | Paper | Code | Dataset |
|-------|--------|-------------|--------|------|------|
| **PRESTO**| **Lightweight, Pre-trained Transformers for Remote Sensing Timeseries** | Arxiv 2023 | [PRESTO](https://arxiv.org/abs/2304.14065) | [Code](https://github.com/nasaharvest/presto) | null |
| **Copernicus-FM** | **Towards a Unified Copernicus Foundation Model for Earth Vision** | ICCV 2025 Oral | [Copernicus-FM](https://arxiv.org/abs/2503.11849) | [Code](https://github.com/zhu-xlab/Copernicus-FM) | [Copernicus-Embed-025deg](https://huggingface.co/datasets/wangyi111/Copernicus-Embed-025deg) |
| **TESSERA** | **TESSERA: Precomputed FAIR Global Pixel Embeddings for Earth Representation and Analysis** | Arxiv 2025 | [TESSERA](https://arxiv.org/abs/2506.20380) | [Code](https://github.com/ucam-eo/tessera) | [Python Library](https://github.com/ucam-eo/geotessera) |
| **AlphaEarth** | **AlphaEarth Foundations: An embedding field model for accurate and efficient global mapping from sparse label data** | Arxiv 2025 | [AlphaEarth](https://arxiv.org/abs/2507.22291) | null | [Google Satellite Embedding](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_SATELLITE_EMBEDDING_V1_ANNUAL) |

---

## 🧠 5. Evaluation and Analysis of Embeddings
*Works that probe, benchmark, or visualize the behavior and quality of geospatial embeddings.*


| Abbr. | Title | Publication | Paper | Code / Benchmark |
|-------|--------|-------------|--------|------------------|
| **NeuCo-Bench** | **NeuCo-Bench: A Novel Benchmark Framework for Neural Embeddings in Earth Observation** | Arxiv 2025 | [NeuCo-Bench](https://arxiv.org/abs/2510.17914) | [Code](https://github.com/embed2scale/NeuCo-Bench) | null |
| **GeoINRID** | **Measuring the Intrinsic Dimension of Earth Representations** | Arxiv 2025 | [GeoINRID](https://arxiv.org/abs/2511.02101) | [Code](https://github.com/arjunarao619/GeoINRID) | [AlphaEarth on S2-100K dataset](https://drive.google.com/drive/folders/1USlgi7nRMqnsiJebLI4cplknVt9jWhpU?usp=sharing) |

---

## 🏆 6. Open Challenges and Competitions
*Active or past public challenges focused on geospatial embedding learning or evaluation.*


| Year | Challenge | Host / Platform | Link |
|------|------------|----------------|------|
| 2025 | **CVPR EARTHVISION: Embed2Scale Challenge** | CVPR EarthVision | [Embed2Scale](https://eval.ai/web/challenges/challenge-page/2465/overview) |
| 2025 | **TerraMind Blue-Sky Challenge Round 2: Team Urban Embeddings** | IBM & ESA Φ-lab | [TerraMind Challenge](https://huggingface.co/spaces/ibm-esa-geospatial/challenge) |

---

## 🌎 7. Applications of Geospatial Embeddings
*Papers that use existing embeddings for mapping, retrieval, similarity search, or reasoning tasks.*


| Abbr. | Title | Publication | Paper | Code / Dataset |
|-------|--------|-------------|--------|----------------|
| - | **Cropland Mapping using Geospatial Embeddings** | Arxiv 2025 | [Paper](https://arxiv.org/abs/2511.02923) | [Code](https://nasaharvest.github.io/presto-embeddings/) |

---

## 🌐 8. Related Works (for context)
<!-- *Representation learning or foundation model papers that produce embeddings but are not embedding-centric.* -->
*Broader studies on representation learning and multimodal embeddings that provide conceptual context for geospatial embedding research.*  

### 🛰️ 7.1 Remote Sensing Representation Learning  
*Selected examples of representation learning works in EO and remote sensing.*

> For a more comprehensive collection of remote sensing foundation models, see  
> **[Awesome Remote Sensing Foundation Models](https://github.com/Jack-bo1220/Awesome-Remote-Sensing-Foundation-Models)**.

| Abbr. | Title | Publication | Paper | Code |
|-------|--------|-------------|--------|------|
| **SeCo** | **Seasonal Contrast: Unsupervised Pre-Training from Uncurated Remote Sensing Data** | ICCV 2021 | [SeCo](https://arxiv.org/abs/2103.16607) | [Code](https://github.com/ServiceNow/seasonal-contrast) |
| **SatMAE** | **SatMAE: Pre-training Transformers for Temporal and Multi-Spectral Satellite Imagery** | NeurIPS 2022 | [SatMAE](https://arxiv.org/abs/2207.08051) | [Code](https://github.com/sustainlab-group/SatMAE) |
| **GAIR** | **GAIR: Improving Multimodal Geo-Foundation Model with Geo-Aligned Implicit Representations** | Arxiv 2025 | [GAIR](https://arxiv.org/abs/2503.16683) | null |

### 🔄 8.2 General Multimodal Embedding and Modality Gap Studies  
*Works that investigate or analyze the latent space gap between visual and textual modalities — relevant for understanding cross-modal geospatial embeddings.*

| Abbr. | Title | Publication | Paper | Code |
|-------|--------|-------------|--------|------|
| **ModalityGap** | **Mind the Gap: Understanding the Modality Gap in Multi-modal Contrastive Representation Learning** | NeurIPS 2022 | [ModalityGap](https://openreview.net/forum?id=S7Evzt9uit3) | [Code](https://github.com/Weixin-Liang/Modality-Gap) |
| **DinoVision** | **Into the Rabbit Hull: From Task-Relevant Concepts in DINO to Minkowski Geometry** | Arxiv 2025 | [DinoVision](https://arxiv.org/abs/2510.08638) | [Code](https://github.com/KempnerInstitute/dinovision) |


### 🌋 8.3 Potentially Interesting Works  
*Applied or thematic studies that are not embedding-centric but highlight promising directions or use cases for geospatial representation learning (e.g., disaster response, environmental monitoring, planetary mapping).*

| Abbr. | Title | Publication | Paper | Code |
|-------|--------|-------------|--------|------|
| - | **The Potential of Copernicus Satellites for Disaster Response: Retrieving Building Damage from Sentinel-1 and Sentinel-2** | Arxiv 2025 | [Paper](https://arxiv.org/abs/2511.05461) | [Code](https://github.com/olidietrich/xbd-s12) |
| - | **Landslide Hazard Mapping with Geospatial Foundation Models: Geographical Generalizability, Data Scarcity, and Band Adaptability** | Arxiv 2025 | [Paper](https://arxiv.org/abs/2511.04474) | null |
| - | **On the Generalizability of Foundation Models for Crop Type Mapping** | IGARSS 2025 | [Paper](https://arxiv.org/abs/2409.09451) | [Code](https://github.com/yichiac/crop-type-transfer-learning) |


---

## 🤝 Contributing
Pull requests welcome!

Please add only works that **explicitly discuss or apply geospatial embeddings** — their definition, analysis, evaluation, or use.

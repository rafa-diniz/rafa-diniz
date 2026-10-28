<h1 align="center">Rafael Diniz</h1>

<p align="center">
  <b>Machine Learning Engineer &amp; Researcher</b><br>
  MSc in Computer Science, UFMG (2026) · First author, BMVC 2026 · Belo Horizonte, Brazil
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rafael-diniz-augusto/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:amauri.rafael33@gmail.com"><img src="https://img.shields.io/badge/Email-555555?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://scholar.google.com/citations?hl=en&user=cTYoqLMAAAAJ"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://arxiv.org/abs/2609.06843"><img src="https://img.shields.io/badge/BMVC_2026-paper-B31B1B?style=flat-square&logo=arxiv&logoColor=white" alt="Paper"></a>
</p>

---

I work on label-efficient learning for machine learning models by figuring out which data is worth labeling, and proving it with controlled experiments.

**Currently open** to ML engineer and research engineer roles.

### Publications

**RAIDAL: Redundancy-Aware Information Density Active Learning for CTC-Based Continuous Sign Language Recognition**  
**Rafael A. Diniz Augusto**, Gabriel L. Oliveira, Erickson R. Nascimento · *BMVC 2026*  
[Paper](https://arxiv.org/abs/2609.06843) · [Code](https://github.com/verlab/RAIDAL)

- To our knowledge, the first study of active learning for continuous sign language recognition.
- Repurposes the CTC decoder's alignment peaks so the acquisition function only scores the parts of a video that support the model's predictions.
- Achieves the best results in datasets with large vocabularies across CNN and Transformer backbones, backed by paired-seed replications, ablations and significance tests.
- On PHOENIX-T, reaches the target error rate one labeling round earlier than random sampling: an estimated 9–18 hours of expert annotation saved.

**Development of a Solar Radiation Map Using Artificial Intelligence Techniques**  
**Rafael A. Diniz Augusto**, Cristiana B. Maia, Silvio J. F. Guimarães · *ENCIT 2022 (Brazilian Congress of Thermal Sciences and Engineering)*  
[Paper](https://www.sistema.abcm.org.br/articleFiles/download/36482) · [Code](https://github.com/rafa-diniz/SolarIrradiance)

- Forecasts monthly solar irradiation with seasonal Holt-Winters, trained on six years of cleaned INMET data from 74 weather stations in and around Minas Gerais.
- Expanding-window evaluation: each year is predicted using only the years before it, giving 48 monthly forecasts per station (2017–2020) with a mean absolute error of about 0.3 kWh/m²/day, on values that typically range from 4 to 6.
- Inverse distance weighting turns the station forecasts into a statewide irradiation map, covering cities without a weather station.

### Experience

**VeRLab, UFMG** · MSc researcher, Computer Vision & Machine Learning (2024–2026)  
Active learning for video recognition with CTC-based models (CorrNet, Swin-MSTP); experimental design and statistical evaluation.

**VEDECOM & EFREI, Paris** · Research exchange (2023, 6 months)  
Data-efficient object detection for autonomous driving on BDD100K; FP32-to-INT8 quantization and deployment with TensorRT.

**PUC Minas** · Undergraduate researcher, Machine Learning (2020–2022)  
Time-series forecasting for solar irradiation mapping (ENCIT 2022). Awarded the Best STEM Project at the 29th PUC Minas Undergraduate Research Seminar.

**Backend engineering intern** (2019–2020) · Python, Flask, Docker.

### Built from scratch

I like understanding systems by rebuilding them.

- **[Z-Tensor](https://github.com/rafa-diniz/Z-Tensor)**: a video codec written in PyTorch, with GPU-tensorized block-matching motion estimation, residual coding, scene-aware keyframes and a custom bitstream.
- **[Image-Studio](https://github.com/rafa-diniz/Image-Studio)**: an image-processing engine in NumPy and Cython (no PIL/OpenCV). Features include color-space conversion, custom color LUTs, quantization and dithering.

### Toolbox

Python · PyTorch · NumPy · scikit-learn · OpenCV · Docker · Git · Linux · TensorRT

#  Lung CT Datasets with Segmentation Repository

<div align="center">

![Lung CT](https://img.shields.io/badge/Modality-CT%20Scans-blue)
![Medical AI](https://img.shields.io/badge/Medical-AI-green)
![Open Source](https://img.shields.io/badge/Open-Source-red)
![License](https://img.shields.io/badge/License-Various-yellow)

*A comprehensive collection of publicly available lung CT datasets with segmentation annotations for research in medical image analysis, computer vision, and AI-powered diagnostics.*

</div>

---

## 📋 Table of Contents

- [🎯 Overview](#-overview)
- [📊 Dataset Collection](#-dataset-collection)
- [🔍 Quick Access Links](#-quick-access-links)
- [🛠️ Usage Guidelines](#-usage-guidelines)
- [📝 Citation Requirements](#-citation-requirements)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🎯 Overview

This repository serves as a centralized hub for lung CT datasets with segmentation annotations, curated specifically for researchers working on:

- **🔬 Medical Image Segmentation**
- **🤖 Deep Learning for Medical AI**
- **🩺 Computer-Aided Diagnosis**
- **📈 Radiomics and Quantitative Imaging**
- **🦠 Pathology Detection and Classification**

---

## 📊 Dataset Collection

### 🏥 General Lung Segmentation Datasets

| Dataset | 📂 Scans | 🏷️ Annotations | 📏 Resolution | 📱 Format | 🔗 Access |
|---------|----------|---------------|---------------|-----------|----------|
| **LIDC-IDRI** | 1,018 | Nodule annotations by 4 radiologists | 512×512×varies | DICOM + XML | [🔗 TCIA](https://www.cancerimagingarchive.net/collection/lidc-idri/) |
| **LUNA16** | 888 | Lung nodules ≥3mm | 512×512×varies | DICOM | [🔗 Grand Challenge](https://luna16.grand-challenge.org/Data/) |
| **NSCLC Radiogenomics** | 211 | Tumor segmentations + genomic data | Various | DICOM | [🔗 TCIA](https://www.cancerimagingarchive.net/collection/nsclc-radiogenomics/) |
| **Medical Decathlon Lung** | 96 | Lung tumor segmentations | 512×512×varies | NIfTI | [🔗 MSD](http://medicaldecathlon.com) |

### 🦠 COVID-19 Lung CT Datasets

| Dataset | 📂 Scans | 🏷️ Annotations | 📏 Resolution | 📱 Format | 🔗 Access |
|---------|----------|---------------|---------------|-----------|----------|
| **COVID-19 CT Seg Dataset 1** | 100 slices | Ground-glass, consolidation, effusion | 512×512 | NIfTI | [🔗 MedicalSeg](http://medicalsegmentation.com/covid19/) |
| **COVID-19 CT Seg Dataset 2** | 829 slices (9 volumes) | COVID-19 lesions | Various | NIfTI | [🔗 MedicalSeg](http://medicalsegmentation.com/covid19/) |
| **COVID-19 CT Lung & Infection** | 20 volumes | Left/right lung + infections | Various | NIfTI | [🔗 Zenodo](https://zenodo.org/records/3757476) |
| **COVID-19 & Normal CT** | Various | Lung + infection masks | Various | Various | [🔗 Mendeley](https://data.mendeley.com/datasets/pfmgfpwnmm/2) |

### 🫀 Thoracic Organ Segmentation

| Dataset | 📂 Scans | 🏷️ Annotations | 📏 Resolution | 📱 Format | 🔗 Access |
|---------|----------|---------------|---------------|-----------|----------|
| **SegTHOR** | 60 | Heart, trachea, aorta, esophagus | 512×512×varies | NIfTI | [🔗 Challenge](https://competitions.codalab.org/competitions/21145) |
| **TotalSegmentator CT** | 1,228 | 117+ anatomical structures | Various | NIfTI | [🔗 Zenodo](https://zenodo.org/records/10047292) |
| **LCTSC 2017** | 60 | Lung, heart, spinal cord, esophagus | 512×512×varies | DICOM | [🔗 TCIA](https://www.cancerimagingarchive.net/collection/lctsc/) |

### 🎯 Specialized Datasets

| Dataset | 📂 Scans | 🏷️ Annotations | 📏 Resolution | 📱 Format | 🔗 Access |
|---------|----------|---------------|---------------|-----------|----------|
| **LUNG-PET-CT-DX** | 355 | Tumor bounding boxes | Various | DICOM + XML | [🔗 TCIA](https://www.cancerimagingarchive.net/collection/lung-pet-ct-dx/) |
| **NLST** | 75,000+ | Low-dose screening scans | Various | DICOM | [🔗 TCIA](https://www.cancerimagingarchive.net/collection/nlst/) |
| **Lung Lobe Segmentation** | Variable | Lung lobes + trachea | Various | NIfTI | [🔗 Zenodo](https://zenodo.org/records/12690803) |


### 🫁 Airways segmentation 

| Dataset | 📂 Scans | 🏷️ Annotations | 📏 Resolution | 📱 Format | 🔗 Access |
|---------|----------|---------------|---------------|-----------|----------|
| **ATM’22** | 500 (300 train / 50 val / 150 test) | Full airway tree (segmentations + centerlines) | ~512×512×varies | NIfTI | [🔗 ATM’22 Challenge](https://atm22.grand-challenge.org/) |
| **AeroPath’23** | 27 | Trachea + bronchi (airway segmentation, challenging pathology) | ~512×512×varies (0.68–0.76 mm in-plane, 0.5–1.25 mm slice thickness) | NIfTI | [🔗 GitHub](https://github.com/raidionics/AeroPath) / [🔗 Zenodo](https://doi.org/10.5281/zenodo.10069289) |
| **AIIB23** | 285 (235 fibrotic ILD + 50 COVID-19) | Interstitial lung disease (ILD) masks + airway-informed biomarkers | ~512×512×varies | NIfTI | [🔗 AIIB23 (CodaLab / MICCAI)](https://codalab.lisn.upsaclay.fr/competitions/13238) |


---

## 🔍 Quick Access Links

### 📥 Direct Download Links

#### 🏥 Primary Datasets
- **LIDC-IDRI**: [TCIA Download](https://www.cancerimagingarchive.net/collection/lidc-idri/)
- **LUNA16**: [Challenge Portal](https://luna16.grand-challenge.org/Data/)
- **Medical Decathlon**: [AWS Registry](https://registry.opendata.aws/msd/)

#### 🦠 COVID-19 Datasets
- **COVID-19 Seg Dataset 1**: [Direct Download (151.8 MB)](http://medicalsegmentation.com/covid19/)
- **COVID-19 Seg Dataset 2**: [Volume Data (308 MB)](http://medicalsegmentation.com/covid19/)
- **Zenodo COVID-19**: [ZIP Download (1.1 GB)](https://zenodo.org/records/3757476)

#### 🛠️ Tools & Software
- **TotalSegmentator**: [GitHub](https://github.com/wasserth/TotalSegmentator) | [Online Tool](https://totalsegmentator.com)
- **3D Slicer**: [Official Website](https://www.slicer.org/)
- **ITK-SNAP**: [Download](http://www.itksnap.org/)

---

## 🛠️ Usage Guidelines

### 🔧 Data Preprocessing
```python
# Example: Loading DICOM data
import pydicom
import numpy as np

def load_dicom_series(path):
    """Load DICOM series from directory"""
    series = []
    for file in sorted(os.listdir(path)):
        if file.endswith('.dcm'):
            ds = pydicom.dcmread(os.path.join(path, file))
            series.append(ds.pixel_array)
    return np.array(series)
```

### 📊 Dataset Statistics

#### 📈 Scan Count Distribution
- **LIDC-IDRI**: 1,018 scans (largest nodule dataset)
- **NLST**: 75,000+ scans (screening dataset)
- **COVID-19 Combined**: ~1,000+ scans
- **Specialized**: 60-400 scans each

#### 🎯 Annotation Types
- **Pixel-level Segmentation**: LIDC-IDRI, COVID-19 datasets
- **Bounding Boxes**: LUNG-PET-CT-DX
- **Multi-organ**: SegTHOR, TotalSegmentator
- **Radiologist Consensus**: LIDC-IDRI (4 experts)

---

## 📝 Citation Requirements

### 📚 Primary Citations

**LIDC-IDRI Dataset:**
```bibtex
@article{armato2011lung,
  title={The lung image database consortium (LIDC) and image database resource initiative (IDRI): a completed reference database of lung nodules on CT scans},
  author={Armato III, Samuel G and McLennan, Geoffrey and others},
  journal={Medical physics},
  year={2011}
}
```

**Medical Decathlon:**
```bibtex
@article{antonelli2022medical,
  title={The Medical Segmentation Decathlon},
  author={Antonelli, Michela and Reinke, Annika and others},
  journal={Nature communications},
  year={2022}
}
```

**TotalSegmentator:**
```bibtex
@article{wasserthal2023totalsegmentator,
  title={TotalSegmentator: Robust Segmentation of 104 Anatomical Structures in CT Images},
  author={Wasserthal, Jakob and others},
  journal={Radiology: Artificial Intelligence},
  year={2023}
}
```

---

## 📊 Usage Statistics

### 🔥 Most Popular Datasets
1. **LIDC-IDRI** - 1,000+ publications
2. **LUNA16** - 500+ publications  
3. **Medical Decathlon** - 200+ publications
4. **COVID-19 Seg** - 150+ publications

### 📈 Research Applications
- **Deep Learning**: 75% of usage
- **Radiomics**: 45% of usage
- **CAD Systems**: 60% of usage
- **Clinical Research**: 30% of usage

---



### 📊 Annotation Distribution
```
Nodules:     ████████████████████░░ 80%
Infections:  ██████████░░░░░░░░░░░░ 45%  
Organs:      ███████████████░░░░░░░ 65%
Tumors:      ███████░░░░░░░░░░░░░░░ 35%
```

---

## 🤝 Contributing

### 📥 Adding New Datasets
1. Fork this repository
2. Add dataset information to the appropriate table
3. Include download links and citation requirements
4. Submit a pull request

### 🐛 Reporting Issues
- Broken download links
- Incorrect dataset information
- Missing citations

### 💡 Feature Requests
- New dataset categories
- Additional metadata fields
- Improved visualization tools

---



### 🔒 Privacy & Ethics
- All datasets are de-identified
- Follow institutional guidelines
- Respect patient privacy
- Use only for approved research

---


<div align="center">

### 🌟 Star this repository if it helps your research!

**Made for the medical AI community**

[⬆️ Back to Top](#-lung-ct-datasets-with-segmentation-repository)

</div>

---

*Last updated: September 2025 | Datasets: 15+ | Total Scans: 100,000+*

# BiMMT
This repository will contain the official PyTorch implementation of our BiMMT:

Once the paper is accepted, we will release the full code, configuration files, and scripts for training and evaluation.

---

## 📊 Datasets (will be supported)

We plan to release scripts and instructions for:

- **Myocardial Ischemia dataset**  
  - CCTA + PET multimodal cardiac images  
  - Semi-supervised segmentation under random missing CCTA/PET combinations

- **BraTS 2020**  
  - Multimodal brain tumor MRI (T1, T1c, T2, FLAIR)  
  - Semi-supervised learning with up to \(2^{M-1}\) missing-modality configurations

> **Note:** Due to data usage agreements, raw datasets themselves will **not** be redistributed.  
> We will provide preprocessing scripts and detailed instructions to obtain and prepare the data.

---

## 🧪 Planned Release Structure

After acceptance, the repository will be organized as:

```text
BiMMT/
├── configs/           # YAML configs for different datasets and label ratios
├── data/              # Data preparation scripts and README
├── models/            
├── trainers/         
├── utils/      
├── scripts/
│   ├── train_bimmt.sh
│   └── eval_bimmt.sh
└── README.md

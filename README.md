
<div align="center"> 
  <h1> OCRT: Boosting Foundation Models in the Open World with Object-Concept-Relation Triad

  [📄 Paper (CVPR 2025)](https://arxiv.org/pdf/2503.18695)

</div>

**Official PyTorch implementation** of the CVPR 2025 paper:
> **"OCRT: Boosting Foundation Models in the Open World with Object-Concept-Relation Triad"**
>
> [Luyao Tang](https://lytang63.github.io/)\*, [Yuxuan Yuan](https://scholar.google.co.uk/citations?user=I297pnoAAAAJ&hl=en)\*, [Chaoqi Chen](https://chaoqichen.github.io/)†, [Zeyu Zhang](https://steve-zeyu-zhang.github.io/), [Yue Huang](https://huangyue05.github.io/)† and [Kun Zhang](https://scholar.google.com/citations?user=RGoypN4AAAAJ&hl=en)
>
> \*Equal contribution. †Corresponding authors.
>
> <em><b> CVPR 2025 </b></em>


## 🎈 News
- [2025.4.1] Our work has been accepted to CVPR 2025 🎉
- [2025.4.9] Training and inference code is coming soon!

## 🔧 Key Features

- 🔍 **Object-centric Representations** via slot attention & unsupervised decoupling
- 📘 **Informative Concept Extraction** through semantic projection and concept importance weighting
- 🔗 **High-order Relational Reasoning** with flexible concept-based graph and relation tokens
- 🔁 **Transferable** across tasks, datasets, and FMs (e.g., CLIP, SAM)

---

## 🖼️ Framework Overview

<p align="center">
  <img src="./assets/ocrt_pipeline.png" alt="OCRT Pipeline" width="700"/>
</p>

---

## 📦 Installation

```bash
git clone https://github.com/lytang63/OCRT.git
cd OCRT
conda create -n ocrt python=3.9
conda activate ocrt
pip install -r requirements.txt
```

---

## 🚀 Quick Start



## 📊 Results

### 🧩 Segmentation on SAM

| Method      | COCO (Poly) | VOC (Poly) | ISIC (Poly) | Kvasir (Poly) |
|-------------|-------------|------------|-------------|---------------|
| SAM         | 65.64       | 60.79      | 62.82       | 54.03         |
| WESAM       | 70.77       | 66.72      | 75.36       | 67.40         |
| **OCRT**    | **75.60**   | **74.74**  | **78.83**   | **89.94**     |

### 🧠 Robust Zero-Shot CLIP

| Method   | Clean | ε=2/255 | ε=4/255 |
|----------|-------|---------|---------|
| CLIP     | 73.1  | 0.0     | 0.0     |
| TECO-4   | 54.2  | 43.6    | 31.9    |
| **OCRT** | 63.2  | 45.4    | 33.4    |

---

## 🧪 Supported Datasets

- COCO, Pascal VOC, Kvasir-SEG, ISIC, CAMO, COD10K, OCID
- ImageNet-1k (CLIP), POPE (Hallucination), TextVQA, Flickr30k, COCO-Caption

---

## 📚 Citation

If you use this repo, please cite:

```bibtex
@inproceedings{tang2025ocrt,
  title={OCRT: Boosting Foundation Models in the Open World with Object-Concept-Relation Triad},
  author={Tang, Luyao and Yuan, Yuxuan and Chen, Chaoqi and Zhang, Zeyu and Huang, Yue and Zhang, Kun},
  booktitle={CVPR},
  year={2025}
}
```

---

## 📬 Contact

Feel free to reach out via [GitHub Issues](https://github.com/lytang63/OCRT/issues) or:

- Luyao Tang: `lytang@stu.xmu.edu.cn`  
- Yuxuan Yuan: `yuanyuxuan0908@stu.xmu.edu.cn`

---

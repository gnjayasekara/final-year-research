<h1 align="center">
Balancing Privacy, Accuracy, and Fairness: A Comparative Study of Privacy-Preserving Techniques in Pedestrian Detection Models for Public Surveillance
</h1>

<p align="center">
  <!-- Replace with your GIF -->
  <img src="assets/demo.gif" alt="Research Demonstration" width="900">
</p>

---

## 🎯 Research Objectives

### Main Objective

Evaluate and improve privacy-preserving techniques for pedestrian detection to identify the optimal trade-off between **privacy protection**, **detection accuracy**, and **fairness** in public surveillance systems.

### Sub Objectives

- Assess the impact of different privacy-preserving techniques (e.g., **head blurring, pixelation, masking, and face swapping**) on pedestrian detection performance.
- Investigate how varying privacy intensity levels influence the balance between privacy and detection accuracy.
- Explore **hybrid privacy-preserving techniques** to identify configurations that maximize privacy while minimizing performance degradation.
- Analyze the fairness of pedestrian detection models across different demographic subgroups after privacy transformations.

---

## 🧪 Methodology

1. **Literature Review**
   - Review existing privacy-preserving techniques, pedestrian detection methods, and fairness-aware AI approaches.

2. **Dataset Preparation**
   - Use the **WiderPerson** benchmark dataset.
   - Apply multiple privacy-preserving transformations (blurring, pixelation, masking, face swapping, etc.) at different intensity levels to generate transformed datasets.

3. **Model Training & Evaluation**
   - Train and evaluate deep learning-based pedestrian detection models such as **YOLOv8** and **Faster R-CNN** using both original and transformed datasets.

4. **Performance Evaluation**
   - Evaluate detection performance using:
     - Mean Average Precision (**mAP**)
     - Precision
     - Recall
     - F1-score

5. **Privacy & Fairness Assessment**
   - Measure privacy effectiveness and fairness using frameworks such as **FairLearn** and **AIF360**.

6. **Comparative Analysis**
   - Compare privacy, accuracy, and fairness across different privacy-preserving techniques and hybrid configurations.
   - Identify the configuration that provides the best overall trade-off.

7. **Documentation & Reproducibility**
   - Document experiments, implementation details, and evaluation results.
   - Publish source code, datasets, and findings to support reproducible research.

---

## 📊 Research Workflow

<p align="center">
  <img src="https://github.com/user-attachments/assets/dcec0b79-e6ee-4d9c-ae60-1c7839660849" alt="Research Workflow" width="1000">
</p>

---

## 📚 References

### 1. WiderPerson Dataset

S. Zhang, Y. Xie, J. Wan, H. Xia, S. Z. Li, and G. Guo,

*"WiderPerson: A Diverse Dataset for Dense Pedestrian Detection in the Wild,"*

**IEEE Transactions on Multimedia**, vol. 22, no. 2, pp. 380–393, Feb. 2020.

**DOI:** https://doi.org/10.1109/TMM.2019.2929005

### 2. Dataset Download

🌐 **WiderPerson Official Website**

http://www.cbsr.ia.ac.cn/users/sfzhang/WiderPerson/

---

## 🛠️ Technologies

- Python
- PyTorch
- Ultralytics YOLOv8
- Faster R-CNN
- OpenCV
- NumPy
- Pandas
- FairLearn
- AIF360
- Matplotlib

---

## 📈 Evaluation Metrics

### Detection Performance
- Mean Average Precision (mAP)
- Precision
- Recall
- F1-score

### Privacy Metrics
- Structural Similarity Index Measure (SSIM)
- Privacy Score

### Fairness Metrics
- Demographic Parity
- Equal Opportunity
- Equalized Odds

---

## 📂 Repository Structure

```text
.
├── assets/
│   ├── demo.gif
│   └── workflow.png
├── dataset/
├── models/
├── notebooks/
├── results/
├── scripts/
├── src/
├── README.md
└── requirements.txt
```

---

## 📜 Citation

If you use this repository in your research, please cite:

```bibtex
@article{zhang2020widerperson,
  title={WiderPerson: A Diverse Dataset for Dense Pedestrian Detection in the Wild},
  author={Zhang, Shanshan and Xie, Yongqin and Wan, Jian and Xia, Hong and Li, Stan Z. and Guo, Guodong},
  journal={IEEE Transactions on Multimedia},
  volume={22},
  number={2},
  pages={380--393},
  year={2020},
  doi={10.1109/TMM.2019.2929005}
}
```

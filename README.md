This project addresses a 12-class plant species image classification task using three approaches:
    1. An end-to-end Convolutional Neural Network (CNN),
    2. A tuned CNN with improved hyperparameters, and
    3. Classical machine learning models — Support Vector Machines (SVM) and XGBoost (XGB) — trained on features extracted by a compact CNN backbone.

Experiments were conducted on Google Colab (T4 GPU) with reproducibility ensured through version control and caching. Validation results show CNN improvements with Leaky ReLU and larger kernels, while SVM and XGB achieved strong accuracy on extracted features.

Folder Structure
ASSIGNMENT_1_CNN/
├─ README.md
├─ requirements.txt
├─ scripts/
│  ├─ 0_1GetMetadata.py
│  ├─ 0_2ImageResize.py
│  ├─ 0_3AugmentationAndSplit.py
│  └─ 0_4COS_801_CNN_&_SVM_&_XGB.py
└─ docs/
   ├─ COS801_Assignment_1.pdf
   ├─ COS801_HW1_rubric.pdf
   └─ HW_DL_1.pdf
   └─ (Latex) COS801_Assignment_1

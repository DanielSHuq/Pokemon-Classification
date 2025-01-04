# **Pokemon Image Classification with ResNet50**

This project demonstrates an image classification task using **ResNet50** to classify 1000 Pokemon species, achieving a validation accuracy of **99.9%**.

---

## **Dataset**
- **Classes**: 1000 Pokemon species.
- **Images per Class**: ~40.
- **Train Split**: 80% for training.
- **Validation Split**: 20% for validation.

---

## **Model**
- **Architecture**: ResNet50 with an additional Dropout layer to improve generalization.
- **Optimizer**: AdamW with weight decay.
- **Scheduler**: OneCycleLR.
- **Loss Function**: CrossEntropyLoss.
- **Batch Size**: 32.

---

## **Results**
- **Validation Accuracy**: **99.9%** after 20 epochs.
- **Training and Validation Loss**: Smooth convergence over epochs.
- **Training and Validation Accuracy**: Reached high performance with minimal overfitting.

---

## **Next Steps**
- Add more data visualization between steps
- Perform more inference tests and show results
- Attempt using Image Transformers

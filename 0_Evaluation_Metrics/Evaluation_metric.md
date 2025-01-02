
# Evaluation Metrics example: Spam Classification

## 1. Confusion Matrix

|                 | Predicted Spam | Predicted Not Spam | Total |
|-----------------|----------------|---------------------|-------|
| **Actual Spam** | True Positives (TP): 35 | False Negatives (FN): 10 | 45    |
| **Actual Not Spam** | False Positives (FP): 10 | True Negatives (TN): 45 | 55    |
| **Total**       | 45             | 55                  | 100   |

---

## 2. Accuracy

**Formula**:  
$\text{Accuracy} = \frac{TP + TN}{TP + TN + FP + FN}$

**Calculation**:  
$\text{Accuracy} = \frac{35 + 45}{35 + 45 + 10 + 10} = \frac{80}{100} = 0.8$

**Accuracy**: **80%**

---

## 3. Precision

**Formula**:  
$\text{Precision} = \frac{TP}{TP + FP}$

**Calculation**:  
$\text{Precision} = \frac{35}{35 + 10} = \frac{35}{45} \approx 0.778$

**Precision**: **77.8%**

---

## 4. Recall (Sensitivity)

**Formula**:  
$\text{Recall} = \frac{TP}{TP + FN}$

**Calculation**:  
$\text{Recall} = \frac{35}{35 + 10} = \frac{35}{45} \approx 0.778$

**Recall**: **77.8%**

---

## 5. F1-Score

**Formula**:  
$F1 = 2 \cdot \frac{\text{Precision} \cdot \text{Recall}}{\text{Precision} + \text{Recall}}$

**Calculation**:  
$F1 = 2 \cdot \frac{0.778 \cdot 0.778}{0.778 + 0.778} = 2 \cdot \frac{0.605}{1.556} \approx 0.777$

**F1-Score**: **77.7%**

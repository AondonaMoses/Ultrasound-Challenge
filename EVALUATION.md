# 🧪 Evaluation Criteria

Models will be evaluated on a **hidden test set** using:

### Metrics:
1. **Dice Similarity Coefficient (DSC)**
2. **Hausdorff Distance 95 (HD95)**

The final score will be a weighted average:

```text
Final Score = 0.7 * DSC + 0.3 * (1 - normalized HD95)

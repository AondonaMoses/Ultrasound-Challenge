# 🚀 Submission Guidelines

All submissions must be made through **GitHub Classroom** using a **COG-compliant Docker container**.

Your submission should:
- Accept an ultrasound image as input
- Return a predicted binary segmentation mask (tumor vs background)
- Follow the input/output format exactly

---

## 📦 COG Container Requirements

Your submission must include:

- A valid `.cog.yaml` file
- An `inference.py` or `predict.py` script that performs prediction
- A `Dockerfile` (if additional customization is needed)
- All required dependencies

---

## 🧠 Input/Output Format

- **Input**: A single `.png` ultrasound image
- **Output**: A single `.png` binary mask (same name with `_mask` suffix)

Example:

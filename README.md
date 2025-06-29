# 🧠 Ultrasound Tumor Segmentation Challenge 2025

Welcome to the **Ultrasound Image Segmentation Challenge**, focused on tumor localization in low-resource medical imaging settings. This challenge aims to benchmark AI models on ultrasound data using a fair and reproducible evaluation framework.

## 📅 Important Dates
- 📢 Challenge Opens: July 15, 2025
- 🛠 Submission Deadline: August 30, 2025
- 🏆 Winners Announced: September 10, 2025

## 💡 Objective
Participants must build a model that performs **tumor segmentation** on ultrasound images and submit a **COG-compliant container** for blind inference on unseen data.

## 📂 Dataset
The dataset contains:
- `training_data/` — raw ultrasound images
- `training_label/` — corresponding segmentation masks (`*_mask.png`)

🔗 [Download Dataset on Google Drive](https://drive.google.com/...)

More details can be found in [`docs/dataset_description.md`](docs/dataset_description.md).

## ✅ How to Participate

1. Join the [GitHub Classroom Assignment Link](https://classroom.github.com/...) to receive your starter repository.
2. Fork it and start developing your model.
3. Ensure your final submission is a **COG-compliant container**.
4. Push your submission before the deadline.

## 🧪 Evaluation
Evaluation will be done using Dice Score and HD95 on a private test set. Full details are in [`EVALUATION.md`](EVALUATION.md).

## 🚀 Submission Rules
- Max 2 submissions per team per day.
- Submissions must be via GitHub Classroom only.
- No manual post-processing during evaluation.

See [`SUBMISSION.md`](SUBMISSION.md) for container requirements and format.

## 💬 Contact
For questions or issues, please open an [Issue](https://github.com/your-org/ultrasound-segmentation-challenge/issues) or email `challenge-organizers@example.com`.

---

> Organized by **SPARK** — SPrint AI training for AfRican medical imaging Knowledge translation (SPARK).

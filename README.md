# Responsible Assignment #01

This repository contains the work submitted by **Abdullah Kaif** for a responsible AI assignment. The core deliverable is a Jupyter notebook demonstrating an end‑to‑end experiment in explainable machine learning, with a particular emphasis on comparing three feature‑attribution techniques.

## 📂 Project Structure

- **`Clinical_Explainable_AI`** – principal notebook covering data preprocessing, model training, and explanation routines.
- **`stroke_triage.csv`** – dataset used for training and evaluation.
- **`Best_Model.pth`** – serialized PyTorch model weights.
- **`requirements.txt`** – Python dependencies required to run the notebook.

## 🧠 Attribution Methods Explored

The notebook implements and contrasts the following explainability methods:

1. **LIME (Local Interpretable Model‑agnostic Explanations)** – builds local surrogate models via input perturbations.
2. **SHAP (SHapley Additive exPlanations)** – employs a game‑theoretic framework producing Shapley values with additivity guarantees.
3. **Integrated Gradients** – a gradient‑based method that computes contributions by integrating gradients from a baseline.

Each method is applied to a set of test instances, with output printed and various consistency/additivity properties verified. A dedicated markdown section provides a comparative evaluation of ranking consistency, computational cost, and theoretical distinctions, culminating in a recommendation for clinical deployment.

## 🚀 Setup and Usage

1. Clone or download this repository.
2. (Optional) Create and activate a virtual environment.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch the notebook with Jupyter or via VS Code and execute cells sequentially. The notebook will train the model (if not pre‑trained) and generate explanations for the provided examples.

## 👤 Author

Abdullah Kaif – student at FAST NUCES.

## 📝 License

This code is provided for academic and educational purposes only. No warranty is offered regarding correctness or suitability for production use.

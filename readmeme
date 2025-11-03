🍔 Food Classification System (MindSpore + ResNet50)
📘 Overview

This project is a Food Image Classification System built using MindSpore and a fine-tuned ResNet-50 model from MindCV.
It classifies images of food items into predefined categories (e.g., french fries, hamburger, pancakes, tiramisu, etc.) through a FastAPI backend and an interactive Flet desktop interface.

The system demonstrates a full workflow:

Model training and fine-tuning in Jupyter Notebook.

Model inference served through a FastAPI server.

Frontend visualization using Flet UI.

🎯 Objectives

Fine-tune ResNet-50 using a custom food dataset in MindSpore.

Build an inference API that automatically loads the best checkpoint.

Provide a lightweight local app interface for image upload and real-time prediction.

Demonstrate an end-to-end machine learning deployment workflow.

⚙️ System Components
🧠 Model Training (Jupyter Notebook)

Fine-tunes the pretrained ResNet-50 from MindCV.

Two-phase training:

Phase 1: Train the classification head.

Phase 2: Fine-tune all layers with a smaller learning rate.

The best model is automatically saved as
models/resnet50_food_best.ckpt.

📍*(show Cell 14 in notebook)* — this cell contains the final fine-tuning loop and checkpoint save code.

🖥️ Backend — FastAPI (server/main.py)

Runs the model inference and exposes an endpoint /predict:

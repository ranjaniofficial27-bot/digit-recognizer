#  Handwritten Digit Recognizer

A deep learning project that recognizes handwritten digits (0–9) using the **MNIST dataset** and a **Convolutional Neural Network (CNN)**.  
Includes a real‑time drawing pad built with **Tkinter** to test predictions interactively.

---

##  Project Description
This project trains a CNN on the MNIST dataset to achieve ~99% accuracy in digit recognition.  
It demonstrates:
- Image preprocessing
- CNN architecture design
- Model training and evaluation
- Confusion matrix and accuracy plots
- Real‑time digit drawing and prediction using Tkinter GUI

Extra features:
- Save and load trained models (`.h5`)
- Deployable with Flask/Streamlit for web apps
- Generates PDF report with accuracy and confusion matrix

---


Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
Run the training script:
   ```bash
   python train_model.py
   ```
 Launch the Tkinter app for real‑time digit recognition:
   ```bash
   python digit_app.py
   ```

---

## Sample Outputs

### Training Accuracy
```
Epoch 10/10
loss: 0.0251 - accuracy: 0.9921 - val_loss: 0.0354 - val_accuracy: 0.9890
```

### Confusion Matrix Screenshot
- Shows correct classification of digits with minimal misclassifications.

### Tkinter GUI
- Draw a digit on the canvas → Model predicts instantly.  
  Example: Draw “7” → Output: `Predicted Digit: 7`

---

##  Project Structure
```
handwritten-digit-recognizer/
│── train_model.py        # CNN training script
│── digit_app.py          # Tkinter GUI for real-time recognition
│── mnist_cnn.h5          # Saved trained model
│── requirements.txt      # Dependencies
│── README.md             # Documentation
│── outputs/              # Accuracy plots, confusion matrix screenshots
```

---

##  Author Info
Developed by **Ranjani**  
- Aspiring Machine Learning Engineer  
- Interests: Deep Learning, Computer Vision, AI Applications  
- Contact: ranjaniofficial27@gmail.com
```


 Classifier + Digit Recognizer) so you can showcase them together in one polished update?


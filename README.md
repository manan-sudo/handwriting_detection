# **Handwritten Digit Recognition**

### **Overview**  
This project implements a Handwritten Digit Recognition system using deep learning. It trains a neural network on the MNIST dataset and allows users to draw custom digits using an interactive interface. The drawn digits are classified by the trained model in real time.  

### **Features**  
- **Interactive Drawing Canvas**: Draw digits directly using a GUI interface.  
- **Deep Learning Model**: A PyTorch-based neural network trained on the MNIST dataset.  
- **Real-Time Classification**: Custom-drawn digits are resized, preprocessed, and classified instantly.  

---

### **Technologies Used**  
- **Python**  
- **PyTorch**: For training and testing the neural network.  
- **OpenCV**: For handling the drawing canvas and preprocessing the images.  
- **scikit-learn**: For data preprocessing and evaluation.  
- **Matplotlib**: For interactive canvas visualization (Colab-compatible).  

---

### **Setup Instructions**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/handwritten-digit-recognition.git
   cd handwritten-digit-recognition
   ```

2. **Install Dependencies**
   Install all required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Code**
   Open the `main.ipynb` file in Jupyter or Google Colab and execute the cells.

---

### **How It Works**

1. **Train the Model**  
   The model is trained using the MNIST dataset, which consists of 70,000 images of handwritten digits (0-9).  
   - **Architecture**: A simple convolutional neural network (CNN) is implemented with PyTorch.  

2. **Draw and Classify**  
   - Draw a digit using the interactive canvas.  
   - The drawn digit is resized to `28x28`, normalized, and passed to the trained model.  
   - The model predicts the digit with high accuracy.  

---

### **Future Improvements**
- Add more sophisticated models for improved accuracy.
- Implement real-time feedback during drawing.
- Deploy the application as a web app using Flask or Streamlit.

---

### **Contributions**  
Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions and improvements.


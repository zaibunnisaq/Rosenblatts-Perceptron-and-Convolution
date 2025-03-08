## **This project consists of two key implementations from scratch:**

1. **Rosenblatt's Perceptron** - A single-layer perceptron used for binary classification.
2. **2D Convolution** - A manually implemented convolution function to process grayscale images.

Both implementations provide insights into fundamental machine learning and computer vision techniques.

---

## **1. Implementing Rosenblatt’s Perceptron from Scratch**

### **1.1 Methodology**
- A synthetic dataset of **500 samples** (with two features) was generated.
- A **binary classification** problem was defined based on a **linear decision boundary**.
- The dataset was split into **training (80%)** and **testing (20%)** subsets.
- The perceptron algorithm was implemented by:
  - Computing the weighted sum of inputs plus bias.
  - Applying a **step activation function**.
  - Updating weights **only** when a misclassification occurred.

### **1.2 Visualizations**
- **Scatter Plot:** Displaying the two classes in the dataset.
- **Decision Boundary:** Overlaying the computed decision boundary on the test dataset.

### **1.3 Performance Analysis and Discussion**
- **Test Accuracy:** Achieved **99% accuracy** on the test set.
- **Discussion:**
  - The perceptron successfully learned a **linear separation** between the two classes.
  - Due to its **linear nature**, misclassifications occurred in regions where the classes overlapped.
  - Visualizations confirmed that while the decision boundary captured the overall trend, **ambiguous samples** were not classified perfectly.

---

## **2. Implementing 2D Convolution from Scratch**

### **2.1 Methodology**
A **generalized 2D convolution function** was implemented to process grayscale images. Various kernels were defined to perform specific tasks:

- **Edge Detection:** Highlighting image boundaries.
- **Blurring:** Using an averaging kernel to smooth the image.
- **Sharpening:** Enhancing image details.

### **2.2 Experiments and Observations**
- **Effects of Different Kernels**: Each kernel produced distinct transformations in the image.
- **Impact of Kernel Size, Stride, and Padding**:
  - Larger kernels and different stride/padding settings influenced output resolution and details.
  - Padding helped preserve spatial dimensions during convolution.
- **Comparison Between Convolution and Correlation**:
  - Symmetric kernels produced similar results for both operations.
  - Non-symmetric kernels led to distinct differences.
- **Manual vs NumPy-based Convolution**:
  - The manually implemented convolution produced results consistent with NumPy’s built-in function.
- **Sequential Application of Kernels**:
  - Applying multiple kernels sequentially (e.g., blurring before edge detection) helped reduce noise and emphasize prominent features.

---

## **Conclusion**
This project successfully demonstrates **two fundamental concepts** in machine learning and computer vision. The perceptron effectively classifies data with a **linear decision boundary**, while the 2D convolution implementation highlights the impact of **kernels, stride, and padding** on image processing.

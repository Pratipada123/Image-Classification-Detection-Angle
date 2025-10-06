# Image-Classification-Detection-Angle# 🧠 Image Classification + Detection + Angle

This project combines **image classification**, **object detection**, and **angle estimation** into one unified workflow.  
It allows a computer to **recognize what an object is**, **locate it in an image**, and **determine how it is oriented**.

---

## 📘 Project Overview
This system can:
- **Classify** objects (e.g., Cat or Dog)
- **Detect** where the object is located
- **Calculate** the **angle** or rotation of the object

Finally, the result is displayed on the image with:
- A **green bounding box**
- A **label** (e.g., Cat | 12.5° | tilted right)
- A **blue arrow** showing direction

---

## ⚙️ Tools and Libraries Used
| Library | Purpose |
|----------|----------|
| **OpenCV (cv2)** | Image processing, contour detection, drawing boxes |
| **NumPy** | Numerical and array operations |
| **Matplotlib** | Image visualization |
| **TensorFlow / Keras** | CNN model for classification |
| **Math** | Calculating rotation angle |

---

## 🧩 Project Workflow
1. **Import Libraries**  
   Load all necessary libraries such as OpenCV, NumPy, TensorFlow, and Matplotlib.

2. **Define Configurations**  
   Set constants like image size, contour area, and class names.

3. **Preprocessing**  
   Convert images to grayscale and find contours for object detection.

4. **Build CNN Model**  
   A simple Convolutional Neural Network (CNN) for Cat vs Dog classification.

5. **Angle Calculation**  
   Compute the object’s rotation using trigonometric functions.

6. **Detection and Annotation**  
   Draw bounding boxes, classify object type, and display angle + arrow direction.

7. **Demo Execution**  
   Run on sample images to visualize results.

---

## 📐 Example Output


# 📸 Face Detection with Haar Cascade Classifier (OpenCV)

This project provides a complete, working solution for detecting human faces in a batch of images using the classic **Haar Cascade Classifier** within the OpenCV framework. This approach is highly efficient for real-time detection in constrained environments.

---

## 🎯 Project Goals

The primary goal of this notebook is to execute an end-to-end face detection pipeline, which includes:

1.  **Data Acquisition:** Programmatically download a large face detection dataset from Kaggle.
2.  **Setup:** Load the necessary pre-trained Haar Cascade XML file.
3.  **Batch Processing:** Iterate through a directory of images.
4.  **Detection:** Apply the Haar Cascade model to detect faces in each image.
5.  **Visualization:** Draw bounding boxes around detected faces and display the results.

## ⚙️ Technology Stack and Dependencies

The project relies on core Python libraries for Computer Vision and file system handling.

| Library | Role |
| :--- | :--- |
| **`opencv-python (cv2)`** | Core Computer Vision library for image loading, processing, and Haar Cascade application. |
| **`os`** | Standard Python library for navigating and iterating through the dataset directory. |
| **`google.colab.patches.cv2_imshow`** | Utility used for displaying OpenCV images in a Colab/Jupyter environment. |

### Prerequisites

To run the notebook successfully, you must first configure the Kaggle API in your environment, as the first step uses the API to download the dataset (`fareselmenshawii/face-detection-dataset`).

```bash
pip install opencv-python
# Ensure Kaggle is set up for data download

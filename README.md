# Invoice_Detection_AI_Project

# 📌 Project Overview
AI Invoice Detection is an intelligent system designed to automatically identify and extract key information from invoices using computer vision and deep learning. This project leverages YOLOv11 for object detection and LabelMe for annotation to streamline invoice processing by reducing manual effort and improving accuracy.

# ✨ Features
- Automatic Key Field Detection: Identifies essential fields like invoice number, date, total amount, and vendor details.
- YOLOv11-Based Detection: Uses a trained last.pt model for object detection on invoices.
- LabelMe for Annotation: Enables manual labeling of key invoice fields to improve training accuracy.
- Multi-Format Support: Works with PDF, JPG, and PNG invoice formats.

#  🛠️ Tech Stack
- Programming Language: Python
- Libraries & Frameworks:
  - OpenCV (Image Processing)
  - LabelMe (Annotation Tool)
  - YOLOv11 (Deep Learning Model for Object Detection)
  - Tesseract OCR (Planned for Text Extraction)

# 🔥 How It Works
- Label the Invoice Fields: Using LabelMe, annotate key fields like invoice number, date, and total amount.
- Train YOLOv11 Model: Train the object detection model on annotated data to recognize invoice fields.
- Run Detection: The system detects labeled fields on test images.

# 📁 Dataset
The dataset used for training and testing is available on Google Drive. You can download it using the link below:<br>
🔗 **[Download Dataset](https://drive.google.com/drive/folders/147NKpgjdVNZpwR6RmHOPlXicEI5mqW23?usp=share_link)**

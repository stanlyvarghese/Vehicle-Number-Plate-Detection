# **Vehicle Number Plate Detection Using YOLOv9 and EasyOCR**

## **Overview**
This project aims to detect and recognize vehicle number plates in real-time using deep learning techniques. It leverages **YOLOv9** for high-speed and accurate number plate detection and **EasyOCR** for extracting text from detected plates. This application is ideal for traffic monitoring, automated toll systems, and parking management.

---

## **Features**
- Real-time number plate detection using a live camera feed or video files.
- Accurate text recognition using EasyOCR.
- Optimized for diverse lighting and environmental conditions.
- Easy integration for traffic management and monitoring systems.

---

## **Technologies Used**
- **Programming Language**: Python  
- **Frameworks and Libraries**:  
  - [YOLOv9](https://github.com/ultralytics/yolov5) for object detection  
  - [EasyOCR](https://github.com/JaidedAI/EasyOCR) for OCR  
  - OpenCV for video and image processing  
  - NumPy for numerical computations  

---

## **Installation and Setup**
### Prerequisites
- Python 3.8 or higher
- CUDA-enabled GPU (optional for faster performance)

### Steps to Set Up:
1. Clone the repository:
   ```bash
   git clone https://github.com/shubh972/vehicle-number-plate-detection.git
   cd vehicle-number-plate-detection
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download pre-trained YOLOv9 weights and place them in the `weights` directory.

4. Run the application:
   ```bash
   python main.py
   ```

---

## **Usage**
- **Live Camera Feed**: Use your system's webcam for real-time detection.  
- **Video Input**: Process a video file to detect and recognize number plates.  
- **Image Input**: Run detection and OCR on static images.  

---

## **Challenges Faced**
- Managing variations in lighting and blurry images.  
- Optimizing detection speed for real-time performance.  
- Handling different plate formats and languages.

---

## **Learning Outcomes**
- Improved understanding of deep learning and computer vision concepts.  
- Gained hands-on experience with YOLOv9 and OCR integration.  
- Enhanced skills in Python, OpenCV, and real-time video processing.

---

## **Contributions**
Feel free to fork this repository and contribute to the project by creating pull requests. Suggestions and improvements are always welcome!

---

## **License**
This project is licensed under the MIT License.

---

## **Acknowledgments**
- [YOLOv9 by Ultralytics](https://github.com/ultralytics/yolov5)  
- [EasyOCR by JaidedAI](https://github.com/JaidedAI/EasyOCR)  

---

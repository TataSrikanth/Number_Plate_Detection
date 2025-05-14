
# License Plate Recognition (LPR) 🔍🚘

This project implements a **License Plate Recognition** system using computer vision and OCR techniques. It is designed to detect license plates in vehicle images and extract the alphanumeric plate numbers using deep learning and text recognition pipelines.

## 📂 Project Structure

```
License_Plate_Recognition/
│
├── License_Plate.ipynb     # Main Jupyter notebook with all implementation steps
├── README.md               # Project documentation
├── requirements.txt        # Python dependencies
├── /images                 # Sample vehicle and license plate images
├── /models                 # Pretrained or trained models (YOLO, CRNN, etc.)
└── /output                 # Output results and predictions
```

## 🚀 Features

- Vehicle license plate detection using object detection (e.g., YOLOv5/YOLOv8).
- Character segmentation (if applicable).
- OCR using Tesseract or deep learning-based CRNN.
- Supports inference on custom test images.
- Results include plate number, bounding box, and confidence score.

## 🛠️ Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt
```

**Key Libraries:**

- Python ≥ 3.7  
- OpenCV  
- NumPy  
- pytesseract or EasyOCR  
- torch (for DL models)  
- matplotlib  

## 🧪 How to Run

1. Clone the repo or download the `.ipynb` file.
2. Place vehicle images in the `images/` folder.
3. Open the notebook:

```bash
jupyter notebook License_Plate.ipynb
```

4. Run all cells to perform detection and recognition.
5. View outputs in the `output/` folder or directly within the notebook.

## 📊 Example Output

```
Detected Plate: TS09EF1234
Confidence: 94%
Image with bounding box saved to /output/TS09EF1234.jpg
```

## 📈 Future Improvements

- Real-time video stream support
- Web app interface using Streamlit or Flask
- Integration with vehicle databases
- Improved accuracy using custom-trained OCR models

## 🧑‍💻 Author

**Srikanth Tata**  
Thanking you,  
Contact Number: 8374256933  
Email Address: srikanthtata2002@gmail.com  

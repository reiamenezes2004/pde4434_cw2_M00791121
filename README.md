# UNO Card Detection System 

A Python-based GUI application for detecting UNO cards from uploaded images or live webcam feed using OpenCV. Built for rapid testing and, real-time detection in computer vision and pattern recognition.

---

#### Features

- Upload single or multiple UNO card images for detection.
- Real-time webcam-based card detection (live feed or capture).
- Automatic bounding box placement with result annotation.
- Uses ORB feature matching and template comparison.
- GUI built using Tkinter for intuitive interaction.

---

#### How to Run the Code

1. **Clone the Repository** using the following command in your terminal:
    - git clone https://github.com/reiamenezes2004/pde4434_cw2_M00791121.git
2. Run all the cells from the python notebook named 'coursework2.ipynb'

---

#### Limitations
- Lighting Dependency: Detection may fail under low light or glare conditions.
- Color Similarity Confusion: Cards with similar hues and shapes may occasionally mismatch.
- Bounding Box Stability: In real-time mode, bounding boxes may flicker if the card is partially obscured.
- Template Reliance: Only cards available in the unocardimages folder can be matched.

---

#### Future Improvement
- Add OCR (Tesseract): Integrate text recognition for detecting numbers and letters dynamically.
- Use Deep Learning: Train a CNN on labeled UNO card images for more reliable and scalable classification.

---
### Folder Structure
- pde4434_cw2_M00791121/       # Main folder
    - unocardimages/           # Template images dataset of UNO cards
    - captured/                # Auto-generated folder to save webcam captures
    - coursework2.ipynb        # Main Python script
    - README.md                # GitHub Documentation file

---

### Links

1) GitHub Link:
https://github.com/reiamenezes2004/pde4434_cw2_M00791121.git

2) YouTube Link:



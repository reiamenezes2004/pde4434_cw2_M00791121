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
2. Run all the cells from the Python notebook named 'coursework2.ipynb'

---

#### Limitations
- Lighting Dependency: Detection may fail under low light or glare conditions.
- Color Similarity Confusion: Cards with similar hues and shapes may occasionally mismatch.
- Bounding Box Stability: In real-time mode, bounding boxes may flicker if the card is partially obscured.
- Template Reliance: Only cards available in the unocardimages folder can be matched.

---

#### Future Improvement
- Add OCR (Tesseract): Integrate text recognition to detect numbers and letters dynamically.
- Use Deep Learning: Train a CNN on labeled UNO card images for more reliable and scalable classification.

---
### Folder Structure
- pde4434_cw2_M00791121/       # Main folder
    - unocardimages/           # Template images dataset of UNO cards
    - captured/                # Auto-generated folder to save webcam captures
    - coursework2.ipynb        # Main Python script
    - README.md                # GitHub Documentation file

---

### Output Screenshots

One screenshot is taken for every color card, some from the internal camera and some from the external webcam.

Black Plus 4

![ss_laptop](https://github.com/user-attachments/assets/79f0cd72-90c0-4590-97d6-a67ce291dc9f)

Red 0

![ss_laptop2](https://github.com/user-attachments/assets/f0035ac8-2e31-4083-ad85-d3e6568d9cb1)

Blue Skip

![ss_laptop3](https://github.com/user-attachments/assets/00de2607-0b0d-4542-9545-b90c90705c3e)

Black Color Change

![ss_webcam](https://github.com/user-attachments/assets/d8bef9df-e41b-431a-8bd1-93ac8e8cbe0b)

Green 8

![ss_webcam2](https://github.com/user-attachments/assets/056796c2-8ac5-4072-8e61-bb8a4316ab87)

Yellow 0

![ss_webcam3](https://github.com/user-attachments/assets/9f4638b5-ad15-4927-ba86-7a2ed305c8c6)

---
### Links

1) GitHub Link:
https://github.com/reiamenezes2004/pde4434_cw2_M00791121.git

2) YouTube Link:



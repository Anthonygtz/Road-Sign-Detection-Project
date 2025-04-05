# Road Sign & Vehicle Detection with YOLOv8

This project contains two custom-trained object detection models using Ultralytics YOLOv8. One model is trained to detect **road signs** (stop signs, speed limits, traffic lights, crosswalks), and the other detects **vehicles** (cars, buses, trucks, motorcycles, ambulances).

---

## Requirements

- Python
- torch
- ultralytics
- opencv-python
- matplotlib


## Model Performance

| Model            | mAP@0.5 | Precision | Recall | Parameters |
|------------------|--------:|----------:|-------:|-----------:|
| Road Sign Model  | 0.995   | 0.999     | 0.997  | 25.8M      |
| Vehicle Model    | 0.665   | 0.881     | 0.999  | 25.8M      |

---

## Sample Output

Output Video:  
- Drive_Test_Output.mp4 — traffic footage showing both vehicle and road sign detections in real-time.

---

## Dataset Sources

- Road Sign Detection Dataset – Kaggle: https://www.kaggle.com/datasets/andrewmvd/road-sign-detection
- Cars and Vehicle Detection Dataset – Kaggle: https://www.kaggle.com/datasets/abdallahwagih/cars-detection

---

## Authors

- Zain Syed  
- G. Anthony Gutierrez Ricard  
---

## License

This project is intended for academic and educational use only. Images and labels were imported form the mentioned Kaggle Datasets.

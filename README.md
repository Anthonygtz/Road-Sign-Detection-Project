# Road Sign & Vehicle Detection with YOLOv8

This project contains two custom-trained object detection models using Ultralytics YOLOv8. One model is trained to detect **road signs** (stop signs, speed limits, traffic lights, crosswalks), and the other detects **vehicles** (cars, buses, trucks, motorcycles, ambulances).

---

## Requirements

- Python  
- torch  
- ultralytics  
- opencv-python  
- matplotlib  

---

## Model Performance

| Model            | mAP@0.5 | Precision | Recall | Parameters |
|------------------|--------:|----------:|-------:|-----------:|
| Road Sign Model  | 0.995   | 0.999     | 0.997  | 25.8M      |
| Vehicle Model    | 0.665   | 0.881     | 0.999  | 25.8M      |

---

## Sample Output

Output Video:  
- `Drive_Test_Output.mp4` — traffic footage showing both vehicle and road sign detections in real-time.

---

## How to Run

1. **Install Required Libraries**  
   Ensure all libraries listed in the requirements are installed.

2. **Upload Driving Test Video**  
   Use the included `Drive_test.mp4`, or upload your own video to the project folder.

3. **Update Paths**  
   In the code or notebook:
   - Set the correct path to your video file.
   - Update the dataset `.yaml` file paths to match your local project structure.

4. **Run the Code**  
   Open `main.ipynb` and run all cells.  
   The output (e.g., `Drive_Test_Output.mp4`) will show real-time detections of vehicles and road signs.

---

## Dataset Sources

- [Road Sign Detection Dataset – Kaggle](https://www.kaggle.com/datasets/andrewmvd/road-sign-detection)  
- [Cars and Vehicle Detection Dataset – Kaggle](https://www.kaggle.com/datasets/abdallahwagih/cars-detection)

---

## Authors

- Zain Syed  
- G. Anthony Gutierrez Ricard  

---

## License

This project is intended for academic and educational use only. Images and labels were imported from the mentioned Kaggle datasets.

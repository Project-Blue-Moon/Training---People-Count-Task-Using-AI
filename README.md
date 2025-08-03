# People Counting with YOLO & DeepSORT
This project is a Computer Vision task for people counting using YOLO for object detection and DeepSORT for object tracking. The implementation is provided in a Jupyter Notebook.

## 📌 Features
- Detects people in video streams or images using YOLO (Ultralytics).

- Tracks detected people across frames using DeepSORT.

- Counts the number of people in the frame over time.

- Runs fully on pre-trained YOLO weights (no additional dataset required).

## 📦 Dependencies
Make sure you have the following Python libraries installed:

```bash
pip install ultralytics deep_sort_realtime pillow numpy opencv-python
```
Additionally, the following built-in Python libraries are used:

```
shutil
warnings
cProfile
pstats
io
argparse
```

## 🚀 Usage
1- Open the Notebook

  - Launch Jupyter Notebook or JupyterLab:

  ```bash
  jupyter notebook
  ```
    
  - Open Acacus_Internship_Task.ipynb.

2- Run the Cells

  - The notebook will:

    1- Load YOLO and DeepSORT.

    2- Process input video or webcam.

    3- Display the tracking and counting results in real-time or save to a file.

3- Change Input Source

  - Update the notebook’s input path to your desired video file or webcam index (e.g., 0 for default webcam).

## 📂 Project Structure

```bash
Acacus_Internship_Task.ipynb   # Main notebook
```

## 📊 Output
- Annotated video with bounding boxes and tracking IDs.

- Console or cell output with people count.

## ⚡ Notes

- Ensure that your environment has GPU acceleration for faster inference.

- You can adjust YOLO and DeepSORT parameters (like confidence thresholds) directly in the notebook.

- For larger videos, consider profiling using cProfile to optimize performance.

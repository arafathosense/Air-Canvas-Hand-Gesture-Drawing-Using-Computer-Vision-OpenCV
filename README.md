# Air Canvas – Hand Gesture Drawing Using Computer Vision OpenCV

Air Canvas is a real-time computer vision application that enables users to draw on a virtual canvas using hand gestures captured through a webcam. The project uses OpenCV for video processing and MediaPipe Hands for accurate hand landmark detection. This application demonstrates practical implementation of gesture recognition, real-time image processing, and human–computer interaction using Python.

## Project Overview

Air Canvas removes the need for traditional input devices such as a mouse or touchscreen by allowing users to draw in mid-air using hand movements. The index finger is tracked and used as a drawing tool, while different hand gestures are used to switch between drawing modes and tools. The system processes live webcam input, detects hand landmarks, and renders drawings on a virtual canvas that is overlaid on the video feed in real time.

<img width="1365" height="728" alt="image" src="https://github.com/user-attachments/assets/8119200d-111c-4b10-bbed-01b1cecddff4" />
<img width="1365" height="728" alt="image" src="https://github.com/user-attachments/assets/c05217c7-2bc7-4117-aff7-1fce5a4750fb" />
<img width="1365" height="727" alt="image" src="https://github.com/user-attachments/assets/581a87e9-2402-4f73-aaa9-4af061267caa" />
<img width="1358" height="727" alt="image" src="https://github.com/user-attachments/assets/88b40fb0-55f1-44e4-8e07-dba6ae5621c2" />
<img width="1365" height="728" alt="image" src="https://github.com/user-attachments/assets/f21b1c52-4dd3-4f5c-bdeb-63c279a2a98b" />
<img width="1365" height="728" alt="image" src="https://github.com/user-attachments/assets/558f35e3-37eb-4386-bcd9-3d33d76b481d" />
<img width="1365" height="726" alt="image" src="https://github.com/user-attachments/assets/2aa7e56b-45e9-4130-9dd2-0b8c703f8635" />
<img width="1365" height="727" alt="image" src="https://github.com/user-attachments/assets/8cfd2fb7-d23f-4d4a-8efb-e375cd4e2aa4" />





## Features

* Real-time hand tracking using MediaPipe Hands
* Gesture-based drawing without physical input devices
* Index finger tracking for drawing
* Mode switching using finger gestures
* Multiple brush colors:

  * Red
  * Green
  * Blue
  * Yellow
* Eraser tool for clearing drawings
* Persistent canvas overlay
* Adjustable brush and eraser thickness


## Technologies Used

* Python 3
* OpenCV
* MediaPipe
* NumPy

### Selection Mode

* Raise **index finger and middle finger**
* Move the hand to the top toolbar
* Select a brush color or the eraser

### Drawing Mode

* Raise **only the index finger**
* Move the finger to draw on the canvas
* Uses the currently selected brush or eraser



## Configuration

The following parameters can be adjusted in the source code to customize the drawing experience:

```python
brush_size = 15
eraser_size = 50
draw_color = (255, 0, 255)
```

## Requirements

* Python 3.8 or higher
* Webcam
* Good lighting conditions
* Single visible hand (application is designed for one-hand tracking)


## Acknowledgements

* OpenCV
* MediaPipe

## 👤 Author

**HOSEN ARAFAT**  

**Software Engineer, China**  

**GitHub:** https://github.com/arafathosense

**Researcher: Artificial Intelligence, Machine Learning, Deep Learning, Computer Vision, Image Processing**

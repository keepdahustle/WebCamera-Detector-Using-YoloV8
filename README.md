
# WebCamera Detector Using YoloV8

YoloV8 is detector objects in static images, videos, and a live webcam using Python and Ultralytics.

## Software Requirements
Install New Release Python and PhyCharm Community Edition To Run This Code

- [Python](https://www.python.org/downloads/)
- [PhyCharm Community](https://www.jetbrains.com/pycharm/download/#section=windows)


## Install Requirements
Before start the program you must install the Requirements

```bash
    pip install -r requirements.txt
```
## Change The Resolution Camera
For Change the Resolution you can change whatever Ratio or Pixel did you want to use

```bash
cap = cv2.VideoCapture(0)
cap.set(3,  1024)   // Length of Resolution
cap.set(4,  600)    // Width of Resolution
```
## Change Scale And Thickness Of Border
You can Change scale or thickness of border at this line
```bash
cvzone.putTextRect(img, f'{classNames[cls]} {conf}', (max(0, x1), max(35, y1)),scale=0.9,thickness=2)
```

![Logo](https://i.pinimg.com/originals/7a/81/bf/7a81bf9cc1771a2409a7d2b38b2ba909.gif)


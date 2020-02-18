# Object Detection with YOLO
YOLO is a computer vision algorithm capable of identifying objects in videos. 
## Setting Up Object Detection with YOLO 
To run YOLO, download all the necessary libraries and dependencies using the Anaconda Navigator. You will need the OpenCV library. 
You will also need the pre-trained weights I used from the Darknet team which you can find here: https://drive.google.com/file/d/1FZfxrC-ROWBB2xftCVkMp7GSbforfDpL/view?usp=sharing. Drag these weights into the folder "yolo-coco". After doing this, you should be ready to go.
## Running YOLO
Within the Anaconda Prompt, navigate to the master folder. To process your own videos replace "example" with your own file's name
```bash
python yolo_video.py --input videos/example.mp4 --output output/example.avi --yolo yolo-coco
```
## Check out more on YOLO
Read my article on Medium: https://towardsdatascience.com/real-time-object-detection-with-yolo-9dc039a2596b
Watch my YouTube video: https://www.youtube.com/watch?v=K0fWqR5I1yo&t=15s

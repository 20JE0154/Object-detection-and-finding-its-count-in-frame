# Object-detection-and-finding-its-count-in-frame
Using open CV find the total count of object (in this code object is  bottle ) in the each frame of video. 

## Instruction to run code 
Upload the below  three files in the jupytor notebook
1. MobileNetSSD_deploy.caffemodel
2. MobileNetSSD_deploy.prototxt
3. Artenal task.ipynb

Now Run the "Artenal task.ipynb" file . The camera will open. Now bring bottles in camera frame the count of bottles per frame and in total will be Visible.


```cap = cv2.VideoCapture(0) ```
The above code will open Camera 
if You Want to use this algo on any video then chabge the value from 0 to video path

```cap = cv2.VideoCapture("VideoPath"")```

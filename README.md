# Sign-language-detection-Using-yolov5

We are performing real time object dection task over the sign language images.

We trained the yolov5 model with approx 500 epochs which give good mAP scores.
https://github.com/ultralytics/yolov5

Data:- 
1. We genrated the custom data of sign languages.
2. This folder also contains labels folder with annotated text file.
3. This annotation is done using an .exe file. (labelimg - https://pypi.org/project/labelImg/)

Training:-
1. We trained yolov5 with its yolov5s version.
2. The model is saved as best.pt file in yolov5 directory.

Steps:-
1. Clone this respository in your local.
2. Replace the model with your trained best.pt
3. Copy run.py and best.pt inside yolov5 directory.
4. Open your code editor.
5. Hit the python run.py in terminal.

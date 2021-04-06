# Indian-Vehicles-Number-Plate-Recognition

--- YOLO (v3,v4) has been used for number plate detection. You only look once (YOLO) is a state-of-the-art, real-time object detection system. A single neural network is applied to the full image. This network divides the image into regions and predicts bounding boxes and probabilities for each region. These bounding boxes are weighted by the predicted probabilities.

--- For number plate detection I have customized the dataset. The images of cars have been downloaded from Google’s Open Images Dataset and annotations have been done using CVAT and LabelImg.

--- For number plate detection on indian roads, I had used customized training using transfer learning. For this purpose, YOLO version v3 and v4 has been used.
YOLO v4 achieves state-of-the-art results at a real time speed on the MS COCO dataset with 43.5 % AP running at 65 FPS on a Tesla V100. 

![results2](https://user-images.githubusercontent.com/42817026/153755288-bacceafd-2735-48d3-98cb-c7e18544c9b3.gif)




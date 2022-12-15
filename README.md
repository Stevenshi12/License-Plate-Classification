# License-Plate-Classification
1. Run YOLOv5 (bounding box) to get license plate bounding boxes 
2. Run 3rd section of MLAI Character Splitting to save individual license plate characters  into a separate folder
     -> The folder name is the label of that license plate. Inside the folder are image files of each character split 
3. Run KNN, FNN, CNN on these split characters to predict. These models are fitted off EMNIST handwritten dataset.

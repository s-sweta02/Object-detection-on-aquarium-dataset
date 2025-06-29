# Object-detection-on-aquarium-dataset
In this work, YOLOv8 is used to detect the objects under the water. The base code trains on the custom dataset and it is trained with 10 epochs and 16 batches are used. For the improvised code, the code reduces batch size dynamically, by using cuda the model was able to improve training speed and optimize memory usage on GPU.  
The performance metrics used here are mAP@50 and mAP@50:
# Base code: mAP@50: 0.618 mAP@50-95: 0.35
# Improved code: mAP@50: 0.615 mAP@50-95: 0.360

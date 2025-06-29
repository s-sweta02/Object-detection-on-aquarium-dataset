# Object-detection-on-aquarium-dataset-using-YOLOv8
In this work, YOLOv8 is used to detect the objects under the water. The base code trains on the custom dataset and it is trained with 10 epochs and 16 batches are used. For the improvised code, the code reduces batch size dynamically, by using cuda the model was able to improve training speed and optimize memory usage on GPU.  
The model's performance was evaluated using mAP@50 and mAP@50–95, where the base code achieved mAP@50 of 0.618 and mAP@50–95 of 0.350, while the improved version recorded mAP@50 of 0.615 and mAP@50–95 of 0.360.



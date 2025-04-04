# RCNN_VS_YOLO

## Results

### Comparison Table
![Comparision_table](compare.png)

### YOLO Detection
![Yolo_detection](yolo_detection.png)

### Faster R-CNN Detection
![Faster_Rcnn_detection](fasterRCNN_detect.png)

## Key Findings and Observations
- **Faster R-CNN** shows a significant improvement in **mAP@0.5:0.95** after augmentation (**from 34.2% to 53.01%**), highlighting its sensitivity to data augmentation.
- **YOLOv8** also benefits from augmentation (**from 45% to 58.95%**) but to a lesser extent compared to Faster R-CNN.
- **YOLOv8** maintains a higher inference speed (**4.9 FPS**) compared to **Faster R-CNN (3.3 FPS)** & **Fast R-CNN (2.3 FPS)**, making it preferable for real-time applications.

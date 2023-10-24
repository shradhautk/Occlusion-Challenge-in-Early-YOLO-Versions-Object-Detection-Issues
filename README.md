# Occlusion-Challenge-in-Early-YOLO-Versions-Object-Detection-Issues
Dive into the occlusion challenges encountered by early YOLO (You Only Look Once) versions V1, V2, and V3, with a specific focus on issues related to object detection. See below as  we transition from figure 1 to figure 3, where figure 1 represents YOLO V1, figure 2 represents YOLO V2, and figure 3 represents YOLO V3, we can observe variations in their performance. In the yellow circle, YOLO V1 exhibits issues with an excessive number of bounding boxes at the location of occluded objects, as indicated by the marked yellow circle in the image. YOLO V2's results are not optimal, with some occluded bounding boxes missing. YOLO V3 shows further progress in addressing these challenges, although perfection has not been achieved. All the models were trained using the similar parameters. 
Enclosed within is a custom codebase primed for elevating the precision and resilience of such object detection models, especially when faced with scenarios involving partially hidden objects. It offers a suite of functions, meticulously crafted for tasks related to bounding boxes and object detection evaluation. These encompass functions for computing the intersection over union (IoU) between bounding boxes, discerning occlusion between boxes, and assessing the average precision of object detection outcomes.

![image](https://github.com/shradhautk/Occlusion-Challenge-in-Early-YOLO-Versions-Object-Detection-Issues/assets/101154495/33f8b33c-5f7d-4554-a54c-1e44567bcff6)

![image](https://github.com/shradhautk/Occlusion-Challenge-in-Early-YOLO-Versions-Object-Detection-Issues/assets/101154495/e4e1e374-a41d-4c39-8f67-f69cf4280f9f)

![image](https://github.com/shradhautk/Occlusion-Challenge-in-Early-YOLO-Versions-Object-Detection-Issues/assets/101154495/173efaf1-9618-4b81-b466-e2f63e290a4f)




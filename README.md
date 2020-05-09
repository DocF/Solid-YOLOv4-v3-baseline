# Solid-YOLOv3-v4-baseline
## Platform
Device RTX2080Ti

Input Size 416×416


YOLOv3 FPS 95.4

YOLOv3-spp FPS 94.0

YOLOv3 ARSF FPS 92.4

YOLOv3 ARSF(lite) FPS 107.2

YOLOv3 ARSF(lite+) FPS 112.1

## NWPU-VHR10

|Index| Model Name |Backbone |From Scratch|mAP* |FPS|BFlops|Model Size(MB)|
|:---:|:---------: |:-------:|:------:|:---:|:-:|:---:|:-------:|
|1|YOLOv4|CSPDarknet53|NO(COCO pretrained)|93.70%|79.0|59.628|256.2|
|2|YOLOv3|CSPResNeXt50(PANet-SPP)|NO(COCO pretrained)|92.27%|77.9|46.589|226.2|
|3|YOLOv3|Efficientnet_b0|YES|80.74%|67.1|3.677|18.9|
|4|YOLOv3|Efficientnet_b0|NO(COCO pretrained)|91.45%|67.1|3.677|18.9|
|5|YOLOv3-tiny|PRN|NO(COCO pretrained)|84.73%|553.9|3.412|19.4|
|6|YOLOv3-tiny-3l|-|NO(COCO pretrained)|86.50%|381.9|7.132|36.1|


mAP Details*
| Index| 1|2|3|4|5|6|
|:---:|:---:|:-:|:-:|:-:|:-:|:-:|
|airplane          |99.98|99.77|98.16|99.95|96.00|98.95|
|ship              |96.48|98.68|83.25|95.34|81.40|82.87|
|storage_tank      |95.58|98.63|83.40|91.20|81.24|97.62|
|baseball_diamond  |99.38|97.80|97.83|99.05|98.19|98.69|
|tennis_court      |88.96|75.11|74.13|90.10|75.33|77.98|
|basketball_court  |95.13|97.82|72.43|95.54|90.93|84.30|
|ground_track_field|98.52|98.43|95.59|99.63|99.58|98.29|
|harbor            |90.83|87.60|91.69|91.06|88.75|81.21|
|bridge            |85.73|83.92|75.15|83.11|92.16|83.37|
|vehicle           |86.40|84.92|35.78|69.57|43.72|61.71|
|mAP               |93.70|92.27|80.74|91.45|84.73|86.50|


## DIOR
Input Size 512x512
|Index| Model Name |Backbone |From Scratch|mAP* |FPS|BFlops|Model Size(MB)|
|:---:|:---------: |:-------:|:------:|:---:|:-:|:---:|:-------:|
|1|YOLOv4|CSPDarknet53|NO(COCO pretrained)|%||59.701|256.4|


## VisDrone2019
Input Size 512x512
|Index| Model Name |Backbone |From Scratch|mAP* |FPS|BFlops|Model Size(MB)|
|:---:|:---------: |:-------:|:------:|:---:|:-:|:---:|:-------:|
|1|YOLOv4|CSPDarknet53|NO(COCO pretrained)|35.74%|59.6|59.628|256.2|

mAP Details*
| Index| 1|
|:---:|:---:|
|awning_tricycle   |21.57|
|bicycle           |12.40|
|bus               |61.09|
|car               |74.05|
|motor             |30.47|
|pedestrian        |28.30|
|people            |17.43|
|tricycle          |23.84|
|truck             |46.81|
|van               |41.41|
|mAP               |35.74|


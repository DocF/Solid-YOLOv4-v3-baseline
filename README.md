# Solid-YOLOv3-v4-baseline
## Platform
Device RTX2080Ti

## Dataset
- NWPU-VHR10
- DIOR
- VisDrone2019

## NWPU-VHR10
Input Size 416×416
|Index| Model Name |Backbone |From Scratch|mAP* |FPS|BFlops|Model Size(MB)|
|:---:|:---------: |:-------:|:------:|:---:|:-:|:---:|:-------:|
|1|YOLOv4|CSPDarknet53|NO(COCO pretrained)|93.70%|79.0|59.628|256.2|
|2|YOLOv3|CSPResNeXt50(PANet-SPP)|NO(COCO pretrained)|92.27%|77.9|46.589|226.2|
|3|YOLOv3|Efficientnet_b0|YES|80.74%|67.1|3.677|18.9|
|4|YOLOv3|Efficientnet_b0|NO(COCO pretrained)|91.45%|67.1|3.677|18.9|
|5|YOLOv3-tiny|PRN|NO(COCO pretrained)|84.73%|553.9|3.412|19.4|
|6|YOLOv3-tiny-3l|-|NO(COCO pretrained)|86.50%|381.9|7.132|36.1|



## DIOR
Input Size 416×416
|Index| Model Name |Backbone |From Scratch|mAP* |FPS|BFlops|Model Size(MB)|
|:---:|:---------: |:-------:|:------:|:---:|:-:|:---:|:-------:|
|1|YOLOv4|CSPDarknet53|NO(COCO pretrained)|76.66%||59.701|256.4|
|2|YOLOv3|CSPResNeXt50(PANet-SPP)|NO(COCO pretrained)|69.16%|75.8|46.662|226.8|


## VisDrone2019
Index 1 Input Size 512x512

Index 2 Input Size 608×608
|Index| Model Name |Backbone |From Scratch|mAP* |FPS|BFlops|Model Size(MB)|
|:---:|:---------: |:-------:|:------:|:---:|:-:|:---:|:-------:|
|1|YOLOv4|CSPDarknet53|NO(COCO pretrained)|35.74%|59.6|59.628|256.2|
|2|YOLOv3|CSPResNeXt50(PANet-SPP)|NO(COCO pretrained)|33.15%|49.1|99.519|226.6|



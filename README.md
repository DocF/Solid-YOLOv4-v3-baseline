# Solid-YOLOv3-v4-baseline
Solid YOLOv3/v4-baseline on NWPU-VHR10

Device RTX2080Ti

Input Size 416×416
|Index| Model Name |Backbone |From Scratch|mAP* |FPS|BFlops|Model Size(MB)|
|:---:|:---------: |:-------:|:------:|:---:|:-:|:---:|:-------:|
|1|YOLOv4|CSPDarknet53|NO(COCO pretrain)|91.41%|79.0|59.628|256.2|
|2|YOLOv3|CSPResNeXt50(PANet-SPP)|NO(COCO pretrain)|92.27%|77.9|46.589|226.2|
|3|YOLOv3|Efficientnet_b0|YES|80.74%|67.1|3.677|18.9|
|4|YOLOv3-tiny|PRN|NO(COCO pretrain)|84.73%|553.9|3.412|19.4|
|5|YOLOv3-tiny-3l|-|NO(COCO pretrain)|86.50%|381.9|7.132|36.1|


mAP Details*
| Index| 1|2|3|4|5|
|:---:|:---:|:-:|:-:|:-:|:-:|
|airplane          ||99.77|98.16|96.00|98.95|
|ship              ||98.68|83.25|81.40|82.87|
|Storage-tank      ||98.63|83.40|81.24|97.62|
|Baseball_diamond  ||97.80|97.83|98.19|98.69|
|Tennis_court      ||75.11|74.13|75.33|77.98|
|Basketball_court  ||97.82|72.43|90.93|84.30|
|Ground_track_field||98.43|95.59|99.58|98.29|
|harbor            ||87.60|91.69|88.75|81.21|
|bridge            ||83.92|75.15|92.16|83.37|
|vehicle           ||84.92|35.78|43.72|61.71|
|mAP               |91.4%|92.27%|80.74%|84.73%|86.50%|

# Solid-YOLOv3-v4-baseline
Solid YOLOv3/v4-baseline on NWPU-VHR10

Device RTX2080Ti
|Index| Model Name |Backbone |Input Size | From Scratch|mAP* |FPS|BFlops|Model Size(MB)|
|:---:|:---------: |:-------:|:---------:|:------:|:---:|:-:|:---:|:-------:|
|1|YOLOv4|CSPDarknet53|416×416|NO(COCO pretrain)|91.41%|79.0|59.628|256.2|
|2|YOLOv3|Efficientnet_b0|416×416|YES|80.74%|67.1|3.677|18.9|



mAP Details*
| Index| 1|2|
|:---:|:---:|:-:|
|airplane          ||98.16|
|ship              ||83.25|
|Storage-tank      ||83.40|
|Baseball_diamond  ||97.83|
|Tennis_court      ||74.13|
|Basketball_court  ||72.43|
|Ground_track_field||95.59|
|harbor            ||91.69|
|bridge            ||75.15|
|vehicle           ||35.78|
|mAP               |91.4%|80.74%|

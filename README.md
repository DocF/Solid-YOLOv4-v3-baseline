# Solid-YOLOv3-v4-baseline
Solid YOLOv3/v4-baseline on NWPU-VHR10

Device RTX2080Ti
|Index| Model Name |Backbone |Input Size | From Scratch|mAP* |FPS|BFlops|Model Size(MB)|
|:---:|:---------: |:-------:|:---------:|:------:|:---:|:-:|:---:|:-------:|
|1|YOLOv4|CSPDarknet53|416×416|NO(COCO pretrain)|91.41%|||
|2|YOLOv3-tiny|Efficientnet_b0|416×416|YES|80.74%||3.677|18.9|



mAP Details*
| Index| 1|2|
|:---:|:---:|:-:|
|airplane          |||
|ship              |||
|Storage-tank      |||
|Baseball_diamond  |||
|Tennis_court      |||
|Basketball_court  |||
|Ground_track_field|||
|harbor            |||
|bridge            |||
|vehicle           |||
|mAP               |91.4%|80.74%|

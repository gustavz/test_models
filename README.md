# test_models
This repo contains frozen graphs of models i trained as part of my [deeptraining_hands](https://github.com/GustavZ/deeptraining_hands) project for benchmark testing my [realtime_detection_api](https://github.com/GustavZ/realtime_object_detection) <br />
> You need to have [git-LFS](https://git-lfs.github.com/) installed to properly use this repo
## Included Models
- `faster_rcnn_inception_v2_coco_2017_11_08` default model from tf's model zoo
- `frcnni_handsnet_200` faster rcnn retrained on the egohands dataset
- `ssd_handsnet600_165_s` ssd_mobilenet with trained from sratch on the egohands dataset with 600x600 as Input Dimensions
- `ssd_handsnet_200_s` ssd_mobilenet re-trained on the egohands dataset with modified `batch_non_max_supression`
- `ssd_mobilenet_v11_coco` default model with modified `batch_non_max_supression`
- `ssd_mobilenet_v1_coco_2017_11_17` default model from tf's model zoo
- `yolo_darknet_tf_handsnet_200_v2` rky0930's yoloV2 Model imported to the API trained on the egohands dataset

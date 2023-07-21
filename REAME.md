## yolov8 + deepsort

## get tart
`https://github.com/elith-co-jp/YOLOv8-DeepSORT-Object-Tracking/tree/naru_dev`  

branch naru_deepsortを使用する．

`pip install -r requirements.txt`  
`naru_src/ultralytics`のyolov8とは環境が違うので注意．  

`YOLOv8-DeepSORT-Object-Tracking/deep_sort_pytorch/configs
/deep_sort.yaml
`内の`REID_CKPT`の絶対pathを自分の環境に変更する．

## train
 `train.ipynb`

## test
`test.ipynb`
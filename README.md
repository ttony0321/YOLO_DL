# YOLO_DL
Detect AI

객체 탐지 AI
![다운로드](https://github.com/ttony0321/YOLO_DL/assets/48801180/f06420a0-10b9-453c-a016-32da6697dec8)
차종 탐지

Yolov5, Yolov8 사용하였으며 Yolov8의 성능이 더 좋았음
#
Yolov8 사용하는경우 CLI보다 Python에서의 성능이 더 좋게나왔음

학습하였던 모델을 load하여 re-train 하는 경우 warmup_epochs = 0으로 설정해서 학습하는것이 유의미한 성능향상이 있었으며

imgsize 는 32의 배수, 1280 같은 큰사이즈는 Yolov8l,x 모델에서 진행  

대회 참여중 사용중이던 Colab 사용자원을 다소모하여 추가 학습을 못함...

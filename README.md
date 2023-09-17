# Facial-Recognition
1. Safety Helmet Wearing Detection(안전모 탐지)
   - dataset
     - kaggle safety helmet dataset
     - VOC2028
   - model
     - YOLOv5
     - YOLOv8
        - for real-time service
   - learning from scratch
   - result
     - YOLOv8 > YOLOv5
   - optional
     - apply EigenCAM on model's layer
2. Facial Recognition Step(안면 인식 단계)
  - YOLO → 안전모 착용 객체 추려내기 → Siamese Network(metric learning) → DB와 비교
  - model
    - Siamese Network
      - Contrastive Loss(Euclidean)
      - learning from scratch(from PubFig Dataset)

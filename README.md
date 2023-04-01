# MobileNet V2

## 하이퍼 파라미터
- batch_size = 16
- epoch = 10
- optimizer = SGD
- learning rate = 0.001

## 결과
### 학습결과(수치)
cuda:0

Training : [1,  2500] loss: 0.649 accuracy: 0.798

Validation : [1,   313] loss: 0.331 accuracy: 0.816

Training : [2,  2500] loss: 0.288 accuracy: 0.902

Validation : [2,   313] loss: 0.268 accuracy: 0.904

Training : [3,  2500] loss: 0.197 accuracy: 0.933

Validation : [3,   313] loss: 0.230 accuracy: 0.931

Training : [4,  2500] loss: 0.143 accuracy: 0.950

Validation : [4,   313] loss: 0.223 accuracy: 0.945

Training : [5,  2500] loss: 0.107 accuracy: 0.963

Validation : [5,   313] loss: 0.222 accuracy: 0.956

Training : [6,  2500] loss: 0.090 accuracy: 0.968

Validation : [6,   313] loss: 0.233 accuracy: 0.961

Training : [7,  2500] loss: 0.075 accuracy: 0.974

Validation : [7,   313] loss: 0.223 accuracy: 0.965

Training : [8,  2500] loss: 0.061 accuracy: 0.978

Validation : [8,   313] loss: 0.232 accuracy: 0.968

Training : [9,  2500] loss: 0.048 accuracy: 0.983

Validation : [9,   313] loss: 0.228 accuracy: 0.973

Training : [10,  2500] loss: 0.041 accuracy: 0.986

Validation : [10,   313] loss: 0.220 accuracy: 0.976

Finished Training

## loss graph
![loss-epoch](https://user-images.githubusercontent.com/90898067/229273926-7051d005-3893-46a0-b27e-0a5a6eb4f9cf.PNG)


## class 별 accuracy

Accuracy for class: plane is 94.9 %

Accuracy for class: car   is 95.8 %

Accuracy for class: bird  is 89.9 %

Accuracy for class: cat   is 81.2 %

Accuracy for class: deer  is 91.8 %

Accuracy for class: dog   is 88.5 %

Accuracy for class: frog  is 96.4 %

Accuracy for class: horse is 97.1 %

Accuracy for class: ship  is 95.3 %

Accuracy for class: truck is 94.4 %

## class graph
![accuracy-epoch](https://user-images.githubusercontent.com/90898067/229274116-874a0b01-ce59-4cad-8352-2cc88c765c26.PNG)

## f1-score
Test F1 score: 0.9409

# 결론
--

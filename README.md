# MobileNet V2

## 하이퍼 파라미터
- batch_size = 16
- epoch = 30
- optimizer = SGD
- learning rate = 0.001

- 그래프상 최적의 epoch : 25
- 실행시간 : 1시간 58분

## 결과
### 학습결과(수치)
cuda:0  
Training : [1,  2500] loss: 0.638 accuracy: 0.803  
Validation : [1,   313] loss: 0.325 accuracy: 0.821  
Training : [2,  2500] loss: 0.287 accuracy: 0.902  
Validation : [2,   313] loss: 0.290 accuracy: 0.902  
Training : [3,  2500] loss: 0.200 accuracy: 0.931  
Validation : [3,   313] loss: 0.229 accuracy: 0.930  
Training : [4,  2500] loss: 0.145 accuracy: 0.949  
Validation : [4,   313] loss: 0.232 accuracy: 0.944  
Training : [5,  2500] loss: 0.114 accuracy: 0.961  
Validation : [5,   313] loss: 0.235 accuracy: 0.954  
Training : [6,  2500] loss: 0.088 accuracy: 0.969  
Validation : [6,   313] loss: 0.220 accuracy: 0.961  
Training : [7,  2500] loss: 0.071 accuracy: 0.976  
Validation : [7,   313] loss: 0.229 accuracy: 0.967  
Training : [8,  2500] loss: 0.062 accuracy: 0.979  
Validation : [8,   313] loss: 0.216 accuracy: 0.971  
Training : [9,  2500] loss: 0.054 accuracy: 0.982  
Validation : [9,   313] loss: 0.231 accuracy: 0.972  
Training : [10,  2500] loss: 0.042 accuracy: 0.987  
Validation : [10,   313] loss: 0.227 accuracy: 0.976  
Training : [11,  2500] loss: 0.041 accuracy: 0.986  
Validation : [11,   313] loss: 0.231 accuracy: 0.976  
Training : [12,  2500] loss: 0.034 accuracy: 0.989  
Validation : [12,   313] loss: 0.225 accuracy: 0.979  
Training : [13,  2500] loss: 0.035 accuracy: 0.988  
Validation : [13,   313] loss: 0.240 accuracy: 0.977  
Training : [14,  2500] loss: 0.029 accuracy: 0.990  
Validation : [14,   313] loss: 0.233 accuracy: 0.979  
Training : [15,  2500] loss: 0.030 accuracy: 0.989  
Validation : [15,   313] loss: 0.237 accuracy: 0.979  
Training : [16,  2500] loss: 0.026 accuracy: 0.991  
Validation : [16,   313] loss: 0.223 accuracy: 0.981  
Training : [17,  2500] loss: 0.023 accuracy: 0.993  
Validation : [17,   313] loss: 0.225 accuracy: 0.982  
Training : [18,  2500] loss: 0.020 accuracy: 0.993  
Validation : [18,   313] loss: 0.228 accuracy: 0.982  
Training : [19,  2500] loss: 0.017 accuracy: 0.995  
Validation : [19,   313] loss: 0.218 accuracy: 0.985  
Training : [20,  2500] loss: 0.014 accuracy: 0.996  
Validation : [20,   313] loss: 0.217 accuracy: 0.985  
Training : [21,  2500] loss: 0.014 accuracy: 0.996  
Validation : [21,   313] loss: 0.214 accuracy: 0.985  
Training : [22,  2500] loss: 0.011 accuracy: 0.997  
Validation : [22,   313] loss: 0.228 accuracy: 0.986  
Training : [23,  2500] loss: 0.012 accuracy: 0.996  
Validation : [23,   313] loss: 0.221 accuracy: 0.986  
Training : [24,  2500] loss: 0.010 accuracy: 0.997  
Validation : [24,   313] loss: 0.228 accuracy: 0.986  
Training : [25,  2500] loss: 0.009 accuracy: 0.997    
Validation : [25,   313] loss: 0.247 accuracy: 0.986   
Training : [26,  2500] loss: 0.010 accuracy: 0.997  
Validation : [26,   313] loss: 0.245 accuracy: 0.985  
Training : [27,  2500] loss: 0.009 accuracy: 0.997  
Validation : [27,   313] loss: 0.243 accuracy: 0.986  
Training : [28,  2500] loss: 0.008 accuracy: 0.998  
Validation : [28,   313] loss: 0.231 accuracy: 0.987  
Training : [29,  2500] loss: 0.010 accuracy: 0.997  
Validation : [29,   313] loss: 0.252 accuracy: 0.986  
Training : [30,  2500] loss: 0.010 accuracy: 0.997  
Validation : [30,   313] loss: 0.248 accuracy: 0.986  
Finished Training





## loss-epoch graph
![loss-epoch](https://user-images.githubusercontent.com/90898067/229288528-29f78415-d778-4a22-a688-ed300ba3fd7b.PNG)



## class 별 accuracy

Validation accuracy: 10.31%

Accuracy for class: plane is 95.2 %

Accuracy for class: car   is 96.8 %

Accuracy for class: bird  is 91.6 %

Accuracy for class: cat   is 84.6 %

Accuracy for class: deer  is 94.7 %

Accuracy for class: dog   is 88.8 %

Accuracy for class: frog  is 94.7 %

Accuracy for class: horse is 93.2 %

Accuracy for class: ship  is 95.2 %

Accuracy for class: truck is 96.7 %

##  accuracy-epoch graph
![accuracy-epoch](https://user-images.githubusercontent.com/90898067/229288623-ea3e2c7a-ae1a-4b1d-b59c-f6aa758bb609.PNG)


## f1-score
Test F1 score: 0.9432



# MobileNet V3

## 하이퍼 파라미터
- batch_size = 64
- epoch = 30
- optimizer = SGD
- learning rate = 0.001

- 그래프상 최적의 epoch : 30
- 실행시간 : 1시간

## 결과
### 학습결과(수치)
cuda:0  
Training : [1,   625] loss: 1.184 accuracy: 0.674  
Validation : [1,    79] loss: 0.514 accuracy: 0.704  
Training : [2,   625] loss: 0.435 accuracy: 0.854  
Validation : [2,    79] loss: 0.385 accuracy: 0.856  
Training : [3,   625] loss: 0.321 accuracy: 0.891  
Validation : [3,    79] loss: 0.321 accuracy: 0.891  
Training : [4,   625] loss: 0.258 accuracy: 0.911  
Validation : [4,    79] loss: 0.284 accuracy: 0.910  
Training : [5,   625] loss: 0.218 accuracy: 0.925  
Validation : [5,    79] loss: 0.267 accuracy: 0.922  
Training : [6,   625] loss: 0.186 accuracy: 0.936  
Validation : [6,    79] loss: 0.251 accuracy: 0.932  
Training : [7,   625] loss: 0.161 accuracy: 0.945  
Validation : [7,    79] loss: 0.241 accuracy: 0.939  
Training : [8,   625] loss: 0.139 accuracy: 0.952   
Validation : [8,    79] loss: 0.234 accuracy: 0.946  
Training : [9,   625] loss: 0.123 accuracy: 0.957  
Validation : [9,    79] loss: 0.228 accuracy: 0.951  
Training : [10,   625] loss: 0.108 accuracy: 0.962  
Validation : [10,    79] loss: 0.223 accuracy: 0.955  
Training : [11,   625] loss: 0.095 accuracy: 0.967  
Validation : [11,    79] loss: 0.221 accuracy: 0.959   
Training : [12,   625] loss: 0.081 accuracy: 0.973  
Validation : [12,    79] loss: 0.228 accuracy: 0.964  
Training : [13,   625] loss: 0.073 accuracy: 0.975  
Validation : [13,    79] loss: 0.214 accuracy: 0.967  
Training : [14,   625] loss: 0.066 accuracy: 0.978  
Validation : [14,    79] loss: 0.217 accuracy: 0.969  
Training : [15,   625] loss: 0.059 accuracy: 0.980  
Validation : [15,    79] loss: 0.222 accuracy: 0.971  
Training : [16,   625] loss: 0.052 accuracy: 0.983   
Validation : [16,    79] loss: 0.230 accuracy: 0.973  
Training : [17,   625] loss: 0.046 accuracy: 0.984   
Validation : [17,    79] loss: 0.225 accuracy: 0.974   
Training : [18,   625] loss: 0.042 accuracy: 0.987  
Validation : [18,    79] loss: 0.231 accuracy: 0.976  
Training : [19,   625] loss: 0.037 accuracy: 0.989  
Validation : [19,    79] loss: 0.229 accuracy: 0.978  
Training : [20,   625] loss: 0.034 accuracy: 0.990   
Validation : [20,    79] loss: 0.229 accuracy: 0.979  
Training : [21,   625] loss: 0.031 accuracy: 0.991  
Validation : [21,    79] loss: 0.237 accuracy: 0.979  
Training : [22,   625] loss: 0.027 accuracy: 0.992   
Validation : [22,    79] loss: 0.237 accuracy: 0.980  
Training : [23,   625] loss: 0.024 accuracy: 0.993  
Validation : [23,    79] loss: 0.240 accuracy: 0.981  
Training : [24,   625] loss: 0.024 accuracy: 0.993  
Validation : [24,    79] loss: 0.238 accuracy: 0.982  
Training : [25,   625] loss: 0.020 accuracy: 0.995   
Validation : [25,    79] loss: 0.245 accuracy: 0.982  
Training : [26,   625] loss: 0.019 accuracy: 0.995  
Validation : [26,    79] loss: 0.250 accuracy: 0.983  
Training : [27,   625] loss: 0.018 accuracy: 0.995  
Validation : [27,    79] loss: 0.248 accuracy: 0.983  
Training : [28,   625] loss: 0.017 accuracy: 0.995  
Validation : [28,    79] loss: 0.251 accuracy: 0.983  
Training : [29,   625] loss: 0.015 accuracy: 0.996  
Validation : [29,    79] loss: 0.257 accuracy: 0.984  
Training : [30,   625] loss: 0.015 accuracy: 0.996  
Validation : [30,    79] loss: 0.256 accuracy: 0.984  
Finished Training  


## loss-epoch graph
![loss-epoch](https://user-images.githubusercontent.com/90898067/229332162-8938e8ae-bbab-4366-9e54-cb28a6f3842b.PNG)


##  accuracy-epoch graph
![accuracy-epoch](https://user-images.githubusercontent.com/90898067/229332261-f0d8327c-70a1-4662-a011-50896f5ad3fc.PNG)


## f1-score
Test F1 score: 0.9366




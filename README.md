# GH-Mathpresso
2020/04~07 Growth Hackers Project with Mathpresso

Data Loading : dataset을 model에 적함한 형태로 modify
Modified Version : 논문에서 제시된 
-GMF
-MLP
-NeuMF
-Threshold Change : 0에서 1사이의 연속 변수를 0과 1의 이진변수로 구분할 때 기준이 될 threshold 수정할 수 있는 부분
Hyperparameter Tuning : model별로 서로 다른 hyperparameter를 조정할 수 있는 부분
-GMF latent vector dimension Tuning : min/max dim, learning rate
-MLP layer dimension Tuning : min/max/end layer number, learning rate
-NCF layer Tuning : min/max dim, min/max/end layer number, learning rate
Candidate List : 학습된 Model을 바탕으로 특정 user가 틀릴 것 같은 문제의 list 생성
Latent Vector analysis : PCA를 통해 정답률에 대한 경향성 확인
Baseline model : 틀린 비율이 높은 학생에 대해 무조건 틀릴 것이라고 예측하는 baseline model 구축, accuracy 측정
total

# fastcampus_deep
- Fastcampus 딥러닝 레벨원 - 반병현 강사님 강의

## 인공지능예제
 - 1-1 : student_classified : one-hot-vector를 사용하여 FNN 분류를 학습함 초등, 중등, 고등 3개로 분류. ==> 최종 출력은 3개임
 - 1-2 : iris_classified : iris_data를 이용해 setosa, versicolor, virginica 3개를 구별하는 FNN 분류를 학습함. ==> 최종 출력은 3개임
 - 1-3 : regression : 육군신체정보 13만개를 FNN을 이용해 회귀형식으로 분류를 실시함.
 - 1_4_MNIST_CV : MNIST_data를 0~9까지 분류를 하고 판단하는 인공지능 모델을 만듬. 하지만 overfitting이 일어났다.
 ----
 - 2_1_FNN_CIFAR : CIFAR-10 데이터를 FNN을 이용해 분류를 실시함. 하지만 FNN 인공지능의 한계로 정확도가 38% 밖에 나오지 않았다.
 - 2_2_CNN_CIFAR : CIFAR-10 데이터를 CNN을 이용해 분류를 실시함. CNN을 사용한 결과 FNN의 정확도의 두배인 86%가량 나왔다. FNN은 하지못하는 것을 CNN을 이용해서 성공하였다.
 - 2_3_CNN_Human_Horse_classified : CNN을 이용하여 분류를 하였고 이진분류로 말과 사람을 분류하였다.
 ---
 - 3_1_R_S_P_Game : CNN을 이용해 분류를 실시하였고, 가위바위보이기때문에 마지막 출력층에서 1개가 아닌 3으로 설정함.
 - 3_2_Paint_by_Gogh : Tensorflow_hub를 사용해서 image_data를 불러왔고, style transfer을 이용하여 일반 사진을 Gogh풍으로 변경하였다. Style transfer module을 검색해보고 정리하자.

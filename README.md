# 2024-ANN
## 데이터 목표
1. data 분석
2. ai 예측

서비스: 자고 있을 때 돈을 범

## 인공신경망의 발전 과정
퍼셉트론 -> 아달라인 -> 선형 회귀 -> 딥러닝

## 딥러닝 개발을 위해 필요한 세 가지
1. 데이터
2. 컴퓨터
3. 프로그램

### 1. 데이터
딥러닝은 데이터를 이용해 예측 또는 판별을 수행
이때 사용되는 데이터는 이름표가 달려 있는지에 따라 두 종류로 나뉨
예를 들어 개와 고양이 사진으로 이루어진 데이터가 있다고 해 보자
각각 사진에 ‘개’ 또는 ‘고양이’라고 이름표가 붙어 있다면, 개 사진을 보고 ‘개’라고 판별하고 고양이 사진을 ‘고양이’라고 판별하는 딥러닝 모델을 만들 수 있음
이렇게 이름표가 주어진 데이터를 이용해 그 이름표를 맞히는 것을 ‘지도 학습’이라고 함

반대로 이름표가 없이 개와 고양이 사진이 그냥 마구잡이로 섞여 있다고 생각해 보자
이때도 딥러닝을 활용할 수 있음
사진 속에서 개 사진들의 공통적인 특징을 찾아내고 고양이 사진들의 특징을 찾아내 이 두 그룹을 분류해 낼 수 있음
이렇게 이름표가 없는 데이터를 이용하는 것을 ‘비지도 학습’이라고 함

책 전반부에서는 지도 학습, 후반부에서는 비지도 학습 계열인 GAN과 오토인코더도 배울 예정

### 컴퓨터(CPU? GPU?)
딥러닝을 일반 CPU 컴퓨터에서 동작시킬지 아니면 고속 그래픽 처리에 특화된 전용 프로세서인 GPU에서 동작시킬지 선택할 수 있음
GPU 작업 환경을 갖추길 추천

### 프로그램
데이터와 컴퓨터 장비가 준비되었다면, 이제 딥러닝을 구동할 수 있게끔 프로그래밍을 해야 함
프로그래밍에 익숙하지 않아도, 수학에 자신이 없어도 구글 코랩(Google Colab)과 딥러닝 라이브러리를 활용하면 누구나 딥러닝을 어렵지 않게 구현할 수 있음

코랩 vs 아나콘다

|구분|코랩|아나콘다|
|---|---|---|
|장점|설치가 필요 없음, 구글의 GPU와 TPU를 사용 가능, 구글 드라이브와 연동 가능|세션 유지 시간의 제약이 없음|
|단점|90분 후 세션 종료, 무료 버전 최대 세션 유지 시간은 12시간|설치 필요, 컴퓨터 사양에 작업 성능이 종속됨|


### 시험

MSE 공식 공란 채우기
a,b 구하는 코드를 수식으로 바꾸기


# 2024-ANN
## 인공지능? 머신 러닝? 딥러닝?
바야흐로 딥러닝의 전성시대
딥러닝이 암을 대신 진단하고 생명 현상의 신비를 풀어내며, 각종 산업 전반에 커다란 변화를 가져오고 있음
딥러닝이 어느 날 갑자기 등장한 것은 아님
딥러닝은 사람을 닮은 인공지능을 만들기 위해 수십 년간 지속해 온 노력의 결실
사람이 할 수 있는 것과 유사한 판단을 컴퓨터가 해낼 수 있게끔 인공지능을 연구하던 중, 기존의 데이터를 이용해 앞으로 일을 예측하는 ‘머신 러닝(machine learning)’ 기법이 효과적임을 발견
이 머신 러닝 안에는 여러 알고리즘이 있는데, 이 중 가장 좋은 효과를 내는 것이 바로 딥러닝
인공지능, 머신 러닝, 딥러닝의 관계를 그림 1-1과 같이 표현할 수 있음
![image](https://github.com/user-attachments/assets/0c7e5f27-1d85-482b-92a8-84ed5fb84d1a)
인공지능의 큰 범주 안에 머신 러닝이 속하고, 머신 러닝의 일부분이 딥러닝인 것
만일 인공지능이 먹을 수 있는 모든 음식이라고 한다면 머신 러닝은 영양가 많은 고기 음식이라 할 수 있고, 딥러닝은 그중에서도 최고급 스테이크 요리쯤 된다고 할 수 있음
우리는 이 책을 통해 최고급 요리에 해당하는 딥러닝을 맛볼 것
고기 맛을 알아야 진정한 스테이크 맛을 음미할 수 있듯, 딥러닝을 충분히 음미하려면 먼저 머신 러닝 맛을 보아야 함
![image](https://github.com/user-attachments/assets/3be9a141-7a82-4f4e-babd-0a7f7c85f742)
머신 러닝은 많은 계산을 필요로 하기 때문에 여러 가지 수학 공식이 쏟아져 나오기도 함
꼭 필요한 머신 러닝만 골라 주면서 ‘진입 장벽’을 자연스럽게 뛰어넘게 만드는 숙련된 가이드가 필요함
![image](https://github.com/user-attachments/assets/c625edee-d266-4684-a4d4-4a3b48433e17)
이 책이 여러분의 가이드가 되어 줄 것
딥러닝 학습에 꼭 필요한 이론과 실습 예제가 난이도를 고려해 차례로 등장
한 챕터씩 공부하다 보면 선형 회귀, 로지스틱 회귀를 지나 자연스레 신경망을 만나게 되고, 실제 세상에 적용 가능한 딥러닝을 경험하게 될 것
책의 마지막 장을 넘길 때쯤, 여러분은 수술 환자의 사망률을 예측하고 아이리스의 품종을 맞추고 손으로 쓴 글씨를 판별하는 딥러닝의 주인이 되어 있을 것
딥러닝 이외에 종종 쓰이는 머신 러닝 알고리즘들은 별책으로 편성되어 있음
별책 부록에서 제공되는 ‘가장 많이 사용되는 머신 러닝 알고리즘 Top10’과 ‘판다스 사용법’까지 참조하면, 타인의 것으로만 보이던 인공지능, 머신 러닝, 딥러닝이 바로 여러분의 손에 쥐어질 것
![image](https://github.com/user-attachments/assets/29a6599d-3f45-4b55-b54d-9f582f29f295)


## 딥러닝 실행을 위해 필요한 세 가지
딥러닝을 실행하기 위해 반드시 갖추어야 할 세 가지 준비 사항이 있음
데이터, 컴퓨터, 그리고 프로그램
### 데이터
딥러닝은 데이터를 이용해 예측 또는 판별을 수행
이때 사용되는 데이터는 이름표가 달려 있는지에 따라 두 종류로 나뉨
예를 들어 개와 고양이 사진으로 이루어진 데이터가 있다고 해 보자
각각 사진에 ‘개’ 또는 ‘고양이’라고 이름표가 붙어 있다면, 개 사진을 보고 ‘개’라고 판별하고 고양이 사진을 ‘고양이’라고 판별하는 딥러닝 모델을 만들 수 있음
이렇게 이름표가 주어진 데이터를 이용해 그 이름표를 맞히는 것을 ‘지도 학습’이라고 함
![image](https://github.com/user-attachments/assets/6c6323d1-611c-423b-b98f-f730a1e1e205)
반대로 이름표가 없이 개와 고양이 사진이 그냥 마구잡이로 섞여 있다고 생각해 보자
이때도 딥러닝을 활용할 수 있음
사진 속에서 개 사진들의 공통적인 특징을 찾아내고 고양이 사진들의 특징을 찾아내 이 두 그룹을 분류해 낼 수 있음
이렇게 이름표가 없는 데이터를 이용하는 것을 ‘비지도 학습’이라고 함
딥러닝을 설계할 때는 이처럼 주어진 데이터에 이름표가 있는지 없는지에 따라 지도 학습을 사용할지, 아니면 비지도 학습을 사용할지 결정하게 됨
이 책은 CNN, RNN 등의 지도 학습과 GAN, 오토인코더 등의 비지도 학습 계열을 모두 다루게 됨
우리가 이 책에서 다루는 대부분의 예제는 이름표가 있는 지도 학습이지만, 책 후반부에서는 비지도 학습 계열인 GAN과 오토인코더도 배움
![image](https://github.com/user-attachments/assets/223f4efb-1d87-48e1-950b-54515f0caec1)
### 컴퓨터(CPU? GPU?)
딥러닝을 일반 CPU 컴퓨터에서 동작시킬지 아니면 고속 그래픽 처리에 특화된 전용 프로세서인 GPU에서 동작시킬지 선택할 수 있음
이 책 예제들은 대부분 CPU와 GPU, 어떤 환경에서도 잘 작동
다만 이 책에서 배운 내용을 자신이 가지고 있는 더 많은 데이터에 적용하려면 GPU 작업 환경을 갖추길 추천
![image](https://github.com/user-attachments/assets/2b254c0f-498a-4457-9760-98ee8dd7448d)
### 프로그램
데이터와 컴퓨터 장비가 준비되었다면, 이제 딥러닝을 구동할 수 있게끔 프로그래밍을 해야 함
프로그래밍에 익숙하지 않아도, 수학에 자신이 없어도 구글 코랩(Google Colab)과 딥러닝 라이브러리를 활용하면 누구나 딥러닝을 어렵지 않게 구현할 수 있음
![image](https://github.com/user-attachments/assets/9f9e1244-b6e5-4d0e-bd19-ca6dba0a7923)

# Machine-learning-study

<h3>1-week</h3>

<h6>기계학습의 정의</h6>

• Arthur Samuel(1959)

MachineLearning: Fieldof study that gives computers the ability to learn without being explicitly programmed.

• Tom Mitchell(1998)

Well-posedLearning Problem: A computer program is said to learn from experience E with respect to some task T and some performance measure P, if its performance on T, as measured by P, improves with experience E.
=> E에 의해서 T를 수행하는 P가 개선될 수 있다.

T = 컴퓨터 프로그램의 작업
E = 작업과 관련된 경험
P = 작업 수행 성능

<h6>기계학습의 분류</h6>

• 지도 학습
  - 입력 데이터와 출력 데이터 format이 정해져 있음 
  (회귀 - Linear Regression, 분류 - SVD벡터)
• 비지도 학습(자율학습)
  - 새로운 데이터 구조를 도출
  (Clustering, Non-clustering)

<h6>기계학습 대표모델(선형회귀)과 비용함수</h6>

함수 h : X → Y를 배우기 위한 학습문제. 
우리가 예측하려는 목표 변수가 연속적이면 학습 문제를 회귀 문제, 그렇지 않고 이산적인 값을 예측한다면 분류 문제라고합니다.

가설함수 : 주어진 데이터 Set에 대해 아래와 같은 선형함수를 예측하는 것
![image](https://user-images.githubusercontent.com/45285053/72239104-38079e00-3623-11ea-8efb-cf61901c2f5a.png)

비용함수 : Cost Function은 입력한 Training Set에 대하여 가장 적합한 직선을 가질 수 있게 해줍니다. 
(ℎ𝜃=𝜃0+𝜃1𝑥, 𝜃의 값들에 따라 함수의 개형이나 값이 아래의 그림처럼  달라지기 때문에 가장 𝑦 에 근사하도록 Training Set을 통해서 정해주어야합니다.)
![image](https://user-images.githubusercontent.com/45285053/72239108-3fc74280-3623-11ea-9d0e-27780f130bfc.png)

근사를 위한 비용함수 공식


비용함수를 통해서 입력된 데이터Set에 대한 가설함수의 정확성을 측정할 수 있습니다.







<h6>"기울기하강"알고리즘의 이해</h6>



<h6>선형대수 기초</h6>

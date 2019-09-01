# StudyMachineLearning

This repository is for studying machine learning with Python.

>1장-소개&첫번째 애플리케이션

1장에서 가볍게 붓꽃을 구별짓는 간단한 훈련을했다

지도학습을 하려면 각 데이터 들을 구분 지을수 있는 것들이 최대한 명확하게 구분되어야 할것같다(?)

* 추가

* 입력과 출력 샘플데이터가 있고, 주어진 입력으로 출력을 예측하고자 할때!

k-최근접 이웃 알고리즘(k-Nearest Neighbors, 이하 k-NN)을 사용했다.

객체를 생성할때 가까운 몇개의 이웃을 찾을지 정해줄수 있다.

ex)

```python
  knn = KNeighborsClassifier(n_neighbors = num)

```

k-NN을 사용하려면 명확하게 알고있는 데이터가 필요하다!(물론 지도학습이라면 명확하게 알고있는 데이터가 있어야 하겠지만 말이다)

>chapter1. Intro&FirstApp

In intro, I trained simply Classify iris

I think in Supervised-Learning, I have to clearly classify the set of datas that already figured out.

+add

When I have input and output sample data, and predict the output by given input

I used k-Nearest Neighbors Algorithm(k-NN)

when I make Object I choose how many neighbors to see.

ex)

```python
knn = KNeighborsClassifier(n_neighbors = num)
```
If I want to use k-NN algorithm, I need set of data that clearly classified or know.

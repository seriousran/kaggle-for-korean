# kaggle-for-korean in python
한국인을 위한 (파이썬) 캐글 튜토리얼
- Kaggle을 이제 막 시작하셨다면? 아래의 [Terminology](#terminology)와 numpy, pandas를 공부하시고 시작하시면 좋을 것 같습니다 :)

## 작성자 Profile
- https://www.kaggle.com/seriousran/
- kernel들 vote 부탁드립니다 :)

## Contents
1. [Terminology](#terminology): Kaggle의 kernel들과 discussion들을 이해하기 위한 용어 설명
2. [EDA](#eda): 데이터 시각화와 Feature Engineering (한글로 마땅한 단어를 모르겠네요)
3. [Model](#model): 기계 학습과 딥러닝 / 인공지능 모델들에 대해 소개 (Machine Learning and Deep Learning)

## Terminology
: kaggle에서 쓰이는 용어들
- CV = Cross-validation score
  - 모델을 trainining dataset을 validation split을 한 후에, cross-validation을 해서 구한 점수를 나타냅니다.
  - 한번의 validation을 통해 얻은 score라면, overfitting일 가능성이 높지만, CV 방식은 좀 더 객관적인 점수를 나타냅니다.
  - 하지만 test dataset으로 계산하지 않은, 로컬한 점수입니다. CV가 LB보다 많이 높을 경우, overfitting으로 간주합니다.
  - ~~Discussion에서 CV는 얼마인데, LB는 얼마가 나온다는 얘기를 많이 볼 수 있습니다.~~
  - LB = Leaderboard score
  - DAE = Denoising autoencoder
  - VAE = Variational autoencoder
  - [OverSampling/UnderSampling](https://www.kaggle.com/residentmario/undersampling-and-oversampling-imbalanced-data)
  - [OOF](https://stackoverflow.com/questions/52396191/what-is-oof-approach-in-machine-learning) = Out-Of-Fold
  - [leak](https://www.kaggle.com/c/santander-customer-transaction-prediction/discussion/84614)
  - [Stacking](https://www.kaggle.com/c/santander-customer-transaction-prediction/discussion/84612)
  - [Stacking2](https://www.kaggle.com/arthurtok/introduction-to-ensembling-stacking-in-python)
  - [Target encoding](https://www.kaggle.com/ogrellier/python-target-encoding-for-categorical-features)

## EDA
: Exploratory Data Analysis
- Main Point
  - Data Analysis
  - Inlier/Outlier
  - Feature Engineering
    - Feature Selection
    - Dimension Reduction
    - Feature Generation
- Libraries
  - Visualization
    - matplotlib
    - bokeh:
    - seaborn (as sns)
      - heatmap
        - variable/feature 간의 correlation matrix를 그릴 때 많이 사용됨.
      - pointplot, boxplot, lmplot(=scatterplot)
    - plotly
      - dots, lines, bars, pie, ...


## Model
- Machine Learning
  - SciKit-Learn
    - Regression
    - Classification
  - Light GBM
  - Catboost
- Deep Learning
  - tensorFlow
  - PyTorch
  - Caffe
  - Theano
  - Cahiner
  - Keras
    - kaggle의 강자는 keras인 것 같습니다. 코드가 간결하기 때문이죠.

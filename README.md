# 유전자 정보를 이용한 난소암 항암제 내성 예측
TensorFlow와 Keras 기반의 DNN 모델을 사용하여 난소암의 백금 성분 항암제 내성을 예측하는 프로젝트입니다.

## Contributors
? Lab, Harim Song, Jihyun Lee

## Motivation
- 저희 조는 생명 전공생 한 명, 전산 전공생 한 명으로 이루어져 있습니다. 인공지능 모델을 이용하여 난소암 항암제 내성 여부를 예측하는 것은 각자의 전공과 관심 분야를 모두 살릴 수 있는 주제라고 생각되어, 본 프로젝트를 선정하게 되었습니다.
- 또한, CNN이나 RNN 등의 복잡한 인공지능 모델을 사용하는 것이 아닌, 수업 시간에 배웠었던 Fully Connected Layer 만을 이용한 간단한 모델을 만들어 문제를 해결할 예정입니다. 이 과정을 통해 수업 때 배웠던 간단한 모델 만으로도 자신이 평소에 흥미를 가지고 있었던 전문 분야의 문제를 해결할 수 있다는 것을 공유하고 싶었습니다.


## Project Summary
1.  TCGA 에서 유전자 정보에 대한 공공 데이터를 다운받고, 전처리 과정을 거쳐 Train / Validation / Test Dataset을 생성합니다.
2.  Train Dataset을 이용하여 간단한 DNN 모델을 학습시킵니다.
3.  다양한 메트릭(Accuracy, Specificity, Sensitivity)을 이용하여 학습된 모델의 예측 정확도를 평가합니다.


## Goals
- 수업 때 배웠던 간단한 DNN 만으로도 자신이 평소에 흥미를 가지고 있었던 전문 분야의 문제를 해결할 수 있음을 알 수 있습니다.
- 수업 때 배웠던 내용을 전산 외의 다른 분야의 연구에 적용할 수 있음을 체험합니다.
- 항암제 (백금 성분) 저항성을 가지게 되는 환자들을 성공적으로 예측할 수 있다면, 그들에게 다른 치료법을 시행할 수 있어 환자들의 시간 및 비용이 절감될 것을 기대할 수 있습니다.

## Dataset

## Pre-Requisites
- tensorflow 1.10.0
- keras
- numpy
- pandas
- sklearn

## Setup Guide 
1. 수업시간에 
2. ` pip install tensorflow==1.10.0 numpy pandas keras sklearn `

## 

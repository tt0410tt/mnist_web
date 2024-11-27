# MNIST 손글씨 분류 프로젝트
## 목차 

## 프로젝트 개요

이 프로젝트는 MNIST 손글씨 데이터셋을 사용하여 딥러닝 모델을 학습하고 손글씨 숫자를 정확하게 분류하는 것을 목표로 합니다.  
딥러닝의 기초부터 구현하며, 추가적으로 데이터 증강 및 다양한 아키텍처를 실험하여 성능을 최적화합니다.

## 주요 기능

### 데이터 로드 및 시각화
- MNIST 데이터셋의 샘플을 로드하고 시각적으로 확인.  
### 딥러닝 모델 구현 
- 커스텀 신경망 아키텍처 설계 및 학습.  
### 성능 평가
- 정확도, 손실 그래프 시각화.  
### 데이터 증강
- 이미지 회전, 이동 등 데이터 증강을 적용하여 모델 성능 향상.  
### 모델 저장 및 로드
- 학습된 모델을 저장하고 불러와 재사용 가능.  
 
## 데이터셋
### 출처
- MNIST 데이터셋  

### 구성:
- 훈련 데이터 : 14,000개의 28x28 픽셀 손글씨 이미지  

각 이미지에는 0부터 9까지의 숫자 레이블이 포함되어 있습니다.  

## 프로젝트 구조


## 사용법

- 데이터 로드 및 전처리  
    python src/dataset.py

- 딥러닝 모델 학습  
    python src/train.py

모델 평가 및 결과 시각화:

python src/evaluate.py

## 결과

모델 정확도: XX%

손실 그래프: results/ 폴더에서 확인 가능.

데이터 증강 효과: [증강 전후 성능 비교]

향후 과제

Convolutional Neural Networks (CNN) 아키텍처 실험.

데이터 증강 기법 추가 및 최적화.

하이퍼파라미터 튜닝.

## 라이선스

[사용할 라이선스를 명시하세요. 예: MIT, Apache 2.0 등]




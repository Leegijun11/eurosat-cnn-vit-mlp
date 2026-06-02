# EuroSAT 위성 이미지 분류 모델 비교

CNN, Vision ViT(Transformer), MLP-Mixer 모델을 활용하여 EuroSAT 위성 이미지 데이터셋 분류 성능을 비교한 프로젝트입니다.

## 프로젝트 소개

딥러닝 기반 이미지 분류 모델들은 서로 다른 방식으로 특징을 추출합니다.

본 프로젝트에서는 위성 이미지 분류 데이터셋인 **EuroSAT**을 사용하여 다음 4가지 모델의 성능을 비교합니다.

* CNN
* Vision Transformer (ViT)
* MLP-Mixer

각 모델의 학습 결과를 비교하고, 정확도 및 손실 그래프를 통해 모델별 특징과 성능 차이를 분석합니다.

---

## 모델의 기본 설명

### 1. CNN

Convolution 연산을 통해 이미지의 지역적 특징을 추출하는 대표적인 이미지 분류 모델입니다.

**특징**

* 이미지 처리에 최적화
* 적은 파라미터로 높은 성능
* 학습 속도가 빠름

---

### 2. Vision Transformer (ViT)

이미지를 여러 개의 Patch로 분할한 후 Transformer 구조를 적용하는 모델입니다.

**특징**

* Self-Attention 기반
* 전역 정보 학습 가능
* 대규모 데이터셋에서 강력한 성능

---

### 3. MLP-Mixer

Patch 단위 입력에 대해 Token Mixing과 Channel Mixing을 수행하는 구조입니다.

**특징**

* Convolution 없이 이미지 처리
* Transformer의 Attention 없이도 경쟁력 있는 성능
* 단순한 구조와 높은 확장성

---

## 프로젝트 구조

```text
eurosat-cnn-vit-mlp/
│
├── notebooks/
│   ├── cnn.ipynb
│   ├── vit.ipynb
│   └── mlp_mixer.ipynb
│
├── results/
│   ├── cnn/
│   ├── vit/
│   └── mlp_mixer/
│
└── README.md
```
---

# 실험 결과

## CNN

### Accuracy & Loss

![CNN Result](results/CNN_loss_acc_visualize.PNG)

---

## Vision Transformer (ViT)

### Accuracy & Loss

![ViT Result](results/ViT_loss_acc_visualize.PNG)

---

## MLP-Mixer

### Accuracy & Loss

![MLP Mixer Result](results/MLP_loss_acc_visualize.PNG)

---

# 모델 성능 비교

| 모델        | 특징                   | 장점           | 단점           |
| --------- | -------------------- | ------------ | ------------ |
| CNN       | Convolution 기반       |    |   |
| ViT       | Self-Attention 기반    |      |     |
| MLP-Mixer | Token/Channel Mixing |  | |

---

## 분석

### CNN

* 
* 

### ViT

* 
* 


### MLP-Mixer

* 
* 

---

## 결론




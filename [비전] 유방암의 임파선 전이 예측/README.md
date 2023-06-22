# [DACON 유방암의 임파선 전이 예측 AI 경진대회](https://dacon.io/competitions/official/236011/overview/description)<br>

### 0. 필사를 하는 이유?
```
종료된 대회에 공유되어 있는 상위권 코드를 분석하며 아이디어, 실력 향상을 하기 위함
```

### 1. 프로젝트 Description
- 프로젝트 분야 : 컴퓨터 비전
- 프로젝트 주제
```
유방암 병리 슬라이드 영상과 임상 항목을 통한 유방암의 임파선 전이 여부 예측
```

- 프로젝트 설명
```
림프절(임파선)은 암의 전이, 암이 퍼지는데 매우 치명적인 역할을 함.<br>
병원에서 암진단을 받았을 시, 가장 많이 듣는 말은 림프절 전이임.<br>
따라서, 이러한 림프절 전이 여부에 따라 치료와 예후가 달라지므로 전이 여부와 전이 단계 파악은 암 치료와 예방에 있어 매우 핵심적임.<br>
```

- 평가 산식 : 샘플별 가중치가 존재하는 Macro F1 Score
샘플 별 가중치는 1.0과 1.2 두 가지 케이스만 존재.<br>
샘플 별 가중치가 부여되는 기준은 본 대회에서 공개하지 않음.<br>
```
from sklearn import metrics
score=metrics.f1_score(y_true=ture, y_pred=pred, average='macro', sample_weight=sample_weight.values)
```
- 디렉토리 구조 
추후 업뎃 예정


### 2. 프로젝트 정보
유방암 병리 슬라이드 영상과 임상 항목을 조합하여 유방암의 임파선 전이 여부 이진 분류

1) [Baseline] Multi-Modal(병리 슬라이드, 임상 항목) 이진 분류 모델 
2) 
### 3. 프로젝트 결과물


### 4. LICENSE
- 주최 : 연세대학교 의과대학, JLK, MTS
- 후원 : 보건산업진흥원
- 주관 : 데이콘

### 5. Code Status

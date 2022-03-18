데이콘 : 한국어 문장 관계 분류 경진대회 최종 8위

Model : klue Roberta-Large
klue-nli-dev 데이터를 추가하여 train 데이터 셋으로 활용했고, 
optimizer는 Adamp를 사용했고 k-fold 교차검증을 사용해 5-fold로 나누어 학습했습니다. 

최종 결과는 아래 4개의 결과의 최빈값을 사용해 최종 결과를 도출했습니다.

모델 1 : Klue/roberta - large ( epoch 10 )
모델 2 : Klue/roberta - large ( epoch 10 중 가장 높은 valid accuracy 모델을 저장)
모델 3 : Klue/roberta - large ( epoch 20 )
모델 4 : Klue/roberta - large ( epoch 20,  5번째 fold 제외 )


# DACON 전력사용량 예측 AI 경진대회

## train	 
train 데이터 : 60개 건물들의 2020년 6월 1일 부터 2020년 8월 24일까지의 데이터
1시간 단위로 제공
전력사용량(kWh) 포함
train.shape: (122400, 10)


## test
test 데이터 : 60개 건물들의 2020년 8월 25일 부터 2020년 8월 31일까지의 데이터
3시간 단위로 제공(강수량의 경우 6시간 단위로 제공, 예보데이터)
전력사용량(kWh) 미포함
test.shape: (10080, 9)



## submission 
sample_submission.csv : 
sample_submission 데이터 
sample_submission.shape: (10080, 2)

https://dacon.io/competitions/official/235736/data

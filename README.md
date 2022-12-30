# DACON_anomaly_detection_
## 월간 데이콘 기계 고장 진단 AI 경진대회
 2022.12.05 ~ 2023.01.16 까지 진행되는 DACON 의 <월간 데이콘 기계 고장 진단 AI 경진대회> 에 참여해 비지도 학습을 통한 이상치 탐지 알고리즘을 공부해 보도록 하겠습니다.

## DataSet
train [폴더]
총 1279개 팬(FAN) 소리 샘플
TRAIN_0000.wav ~ TRAIN_1278.wav


test [폴더]
추론을 위한 팬(FAN) 소리 샘플
TEST_0000.wav ~ TEST_...wav


train.csv [파일]
SAMPLE_ID : 샘플 별 고유 ID
SAMPLE_PATH : 음향 샘플 파일 경로
FAN_TYPE : 팬(FAN)의 모델 종류 (0, 2 존재)
LABEL : 팬(FAN) 고장 여부 (0 : 정상, 1 : 고장)
학습 데이터는 모두 정상 샘플만 존재


test.csv [파일]
SAMPLE_ID : 샘플 별 고유 ID
SAMPLE_PATH : 음향 샘플 파일 경로
FAN_TYPE : 팬(FAN)의 모델 종류 (0, 2 존재)

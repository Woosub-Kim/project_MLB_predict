# project_MLB_predict
MLB경기결과를 예측하는 프로젝트

# url...
https://www.baseballpress.com/lineups/2011-04-30
https://www.fangraphs.com/warleaders.aspx?season=1871&team=all&type=
https://www.fantasylabs.com/mlb/lineups/?date=07012011
https://www.mlb.com/scores/1990-04-30
# 사용데이터
### 투수
ERA 평균자책점
WHIP 이닝당 안타+볼넷 허용률
WAR
### 타자
SLG 장타율
OBP 출루율
WAR

## 성적

              precision    recall  f1-score   support

        away       0.52      0.27      0.36      5247
        home       0.56      0.79      0.66      6219
        near       0.00      0.00      0.00        13

    accuracy                           0.55     11479
   macro avg       0.36      0.35      0.34     11479
weighted avg       0.54      0.55      0.52     11479
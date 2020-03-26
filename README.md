# <한국직업전문학교 무재칠시프로젝트> with <a href='https://github.com/namwon94'>김남원</a>
#### project_MLB_predict 
MLB경기결과를 예측하는 프로젝트

## crwaling source
경기결과: https://www.espn.com/mlb/schedule/          
타자스탯: http://www.espn.com/mlb/stats/batting/         
투수스탯: http://www.espn.com/mlb/stats/pitching/           

# 사용데이터
### 투수
ERA 평균자책점      
WHIP 이닝당 안타+볼넷 허용률      
WAR      
### 타자
SLG 장타율      
OBP 출루율      
WAR      

# 성적
<img width="" height="" src="https://github.com/Woosub-Kim/project_MLB_predict/blob/master/MLB_result.PNG"> </img>

야구종목의 경우 무승부의 예측이 까다로워 전반적으로 성적이 높게 나오지않는다.       
Logistic Regression기법으로는 무승부를 예측하는 것이 거의 불가능하다.

# 개선방안
무승부 예측이 불가능한 이유로는 실력이 비슷한 팀의 승부를 예측하기 어려운 것 외에 무승부 경기 자체가 승부가 나는 경기보다 적은 것도 기인하는 것으로 보여 무승부 데이터를 제하고 다시 분석을 한다면 성적을 개선할 수 있을 것이다.

###### 한국직업전문학교 무재칠시 링크
|설명|링크|
|----|----|
|KBO경기 예측| https://github.com/Woosub-Kim/Project_KBO_Predict |            
|MLB경기 예측| https://github.com/Woosub-Kim/project_MLB_predict |                           
|NBA경기 예측| https://github.com/Woosub-Kim/project_NBA_predict |                    
|API| https://github.com/Woosub-Kim/sports_predict_api |                  
|WEB| https://github.com/namwon94/Project_Baseball |                      

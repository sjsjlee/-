## 따릉이대여량예측경진대회 제출 코드
 
* Dacon 에서 진행한 따릉이 예측경진대회에 제출한 코드입니다.
* 최종 22등/420명(상위 10% 이내)를 기록했습니다.
(https://dacon.io/competitions/official/235837/leaderboard)
닉네임 : 데숭이

### 사용한 데이터
* 2018-2020 Dacon 제작 따릉이대여량예측을 위한 데이터

### 사용 툴&언어
* 파이썬&구글 코랩

### 탐색적 EDA를 위해 사용한 기법
* 파생변수 추가
* 상관관계분석
* 회귀분석
* 변수 추가 타당성 검증

### 전처리
* scaler를 통한 데이터 스케일링 
    * standard scaler
    - minmax scaler
    - max abs scaler : 최종 선택
    - robust scaler

### 모델링
* Linear Regression
* XGBoost Regression
* Random Forest Regression
* Gradient Boosting : 최종 선택
* LSTM 

### 모델 평가
* NMAE (Normalized Mean Absolute Error)

### 기타
* Grid Search CV 를 통한 하이퍼파라미터 수정
 




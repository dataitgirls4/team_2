 # 대성걸즈
 "스토리텔링에 기반한 데이터 분석 및 시각화"에 강점을 가진 팀으로 **상권별 코로나 몸살 진단(서울시 상권분석) 프로젝트**와 **나홀로 홈즈(라이프스타일을 반영한 주거지역선정)프로젝트**를 함께 했습니다.    
 
  ### Team Member
| 이름  |      메일      |  
|----------|:-------------:|
 | 강지은 | cyanred9@gmail.com |   
 | 김나영 | nayoung5859@gmail.com |   
 | 신선주 | starsarah9055@gmail.com |   
 | 정우진 | jwjin0330@gmail.com |   
 | 조현주 | jesica08@naver.com |   

# 프로젝트 목록
## 삐용삐용! 어디가 아프세요? 상권별 코로나 몸살 진단! by 대성걸즈      
- 진행 기간 : 2020.09.15~2020.09.26   

### Background
대성걸즈만의 세분화된 상권 기준을 세우고, 가설검정 과정을 통해 각 상권의 특성 파악 및 대안 제시

### Summary
(1). Data Collection
- 우리마을가게 상권분석 서비스에서 제공하는 데이터셋 사용
- 주요 데이터셋: 서울시 우리마을가게 상권분석서비스(상권-추정매출)

(2). Data Preprocessing
- [min-max 정규화와 표준정규분포로 데이터 스케일링](https://github.com/dataitgirls4/team_2/blob/main/%5B%EC%83%81%EA%B6%8C%20%EB%B6%84%EC%84%9D%5D%201.%20preprocessing/%EB%8D%B0%EC%9D%B4%ED%84%B0%ED%91%9C%EC%A4%80%ED%99%94.ipynb)

(3). Model & Algorithms
- K-means clustering의 변수로 표준화 및 정규화한 유동인구 , 직장인구, 집객시설, 상주인구, 점포수 사용 
- [sklearn.cluster 의 KMeans 이용](https://github.com/dataitgirls4/team_2/blob/main/%5B%EC%83%81%EA%B6%8C%20%EB%B6%84%EC%84%9D%5D%202.%20modeling/%EB%B8%94%EB%9F%AD%EB%B3%84_%ED%81%B4%EB%9F%AC%EC%8A%A4%ED%84%B0%EB%A7%81.ipynb)

(4). Visualising
- 시각화 툴을 이용한 상권별 매출 비교

(5). Review(피드백)
- 클러스터링을 하면 각 클러스터 안에 몇개의 블록이 포함되는지 명시할 것
- 코로나 타임라인과 분석 과정을 함께 보여주는 것 우리가 가진 data set의 큰 그림을 보여주는 작업이라 좋았다

### 보러가기:    
- PPT: https://bit.ly/3mRjfLx
- 노션: https://www.notion.so/by-0fbb3f7acdd1474083d04532a820468f


## 구해줘! 나홀로 홈즈 [의뢰인:93년생 김지수편] with 대성걸즈
- 진행 기간 : 2020.11.04~2020.12.05
- **과학기술정보통신부 장관상 수상**


### Background
실제 라이프스타일을 반영하여 '93년생 김지수'씨를 위해 데이터에 기반한 주거지역 선정

### Summary
(1). Data Collection
- 지방행정 인허가 데이터, 국토교통부실거래가 데이터, 열린데이터 광장 등  
- [기존의 데이터에 행정동, X좌표, Y좌표 칼럼을 추가하기 위해 카카오 맵 API를 이용한 코드 작성](https://github.com/dataitgirls4/team_2/blob/main/%5B%EB%82%98%ED%99%80%EB%A1%9C%20%ED%99%88%EC%A6%88%5D%201.%20Preprocessing/%EC%B9%B4%EC%B9%B4%EC%98%A4api_%EC%B9%BC%EB%9F%BC%EC%B6%94%EA%B0%80%ED%95%98%EA%B8%B0.ipynb)

(2). Data Preprocessing
- ESD방식을 통한 이상치 처리
- [`sklearn.preprocessing` 의 `StandardScaler` 과 `log화`를 통한 데이터 정규화/표준화](https://github.com/dataitgirls4/team_2/blob/main/%5B%EB%82%98%ED%99%80%EB%A1%9C%20%ED%99%88%EC%A6%88%5D%201.%20Preprocessing/%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%8A%A4%EC%BC%80%EC%9D%BC%EB%A7%81.ipynb)
- [각 카테코리의 최소-최대 점수를 맞춰주기 위해 `sklearn.preprocessing` 의 `MinMaxScaler` 를 통한 min-max 정규화](https://github.com/dataitgirls4/team_2/blob/main/%5B%EB%82%98%ED%99%80%EB%A1%9C%20%ED%99%88%EC%A6%88%5D%201.%20Preprocessing/%EC%B9%B4%ED%85%8C%EA%B3%A0%EB%A6%AC%EC%A0%90%EC%88%98_minmax%EC%A0%95%EA%B7%9C%ED%99%94.ipynb)

(3). Visualising
- 시각화 툴(Tableau)를 이용하여 행정동별 데이터 시각화
- [plotly 와 matplotlib 을 통한 레이더 차트 작성](https://github.com/dataitgirls4/team_2/blob/main/%5B%EB%82%98%ED%99%80%EB%A1%9C%20%ED%99%88%EC%A6%88%5D%202.%20visualising/%EB%A0%88%EC%9D%B4%EB%8D%94%EC%B0%A8%ED%8A%B8%EC%8B%9C%EA%B0%81%ED%99%94_plotly.ipynb)

(5). Review(피드백)
- 대성걸즈의 분석을 비즈니스 가치로 연결시킬 수 있는 방법을 생각해보면 좋겠다.
- 페르소나로 진행했지만, 대상을 더 넓혀 만들 수 있을 것
- 대출을 받을 수 있다는 것도 보조적으로 넣으면 UX관점에서 도움 될 것
- 편의점, 헬스장, 음식점 등과 같은 실시간 데이터를 최대한 확보할 수 있는 방법 생각해보기


### 보러가기: 
https://bit.ly/33PSJur


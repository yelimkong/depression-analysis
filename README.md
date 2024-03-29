
## 🚀 프로젝트명

### ✔️ 우울증 지수 예측 프로젝트 😞
<br>

## 📃 프로젝트 소개

#### ✔️ 이 프로젝트는 2018년부터 2022년까지의 전국 자치구 단위 데이터를 활용하여 <br> &nbsp; &nbsp; &nbsp; 우울증 지수를 예측하는 것을 목표로 합니다.
<br>

## 📋 목차
- [1. 기술 스택](#-기술-스택)
- [2. 문제 정의](#-문제-정의)
- [3. 팀원 소개 및 역할](#-팀원-소개-및-역할)
- [4. 프로젝트 진행 기록](#-프로젝트-진행-기록)
- [5. 데이터 소개](#-데이터-소개)
- [6. 데이터 전처리](#-데이터-전처리)
- [7. 탐색적 데이터 분석(EDA)](#-탐색적-데이터-분석eda)
- [8. 모델링](#-모델링)
- [9. 결론](#-결론)
- [10. 한계점](#-한계점)
<br>

## 🛠 기술 스택

### ▪ 언어
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">

### ▪ 주요 라이브러리
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"> <img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white">  <img src="https://img.shields.io/badge/scikit learn-F7931E?style=for-the-badge&logo=scikit learn&logoColor=white">  <img src="https://img.shields.io/badge/matplotlib-0058CC?style=for-the-badge&logo=matplotlib&logoColor=white"> <img src="https://img.shields.io/badge/seaborn-99CC00?style=for-the-badge&logo=seaborn&logoColor=white"> <img src="https://img.shields.io/badge/statsmodels-181717?style=for-the-badge&logo=statsmodels&logoColor=white">
<!--
<img src="https://img.shields.io/badge/wordcloud-FF4F8B?style=for-the-badge&logo=wordcloud&logoColor=white">
<img src="https://img.shields.io/badge/konlpy-FF0000?style=for-the-badge&logo=konlpy&logoColor=white"> <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=collections&logoColor=white">-->


### ▪ 개발 툴
<img src="https://img.shields.io/badge/VS code-2F80ED?style=for-the-badge&logo=VS code&logoColor=white"> ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
### ▪ 협업 툴
<img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Google Slides&logoColor=white">
<br>
<br>

## ⚠️ 문제 정의

2022년 기준, 한국은 OECD 국가 중 우울증 유병률이 가장 높습니다.  
2003년부터 2016년, 그리고 2017년을 제외한 **18년 동안 OECD 국가 중 자살률은 1위를 기록했습니다.**    
통계청에 따르면 **자살 원인 중 우울증이 35.4%** 로 가장 큰 비율을 차지합니다.  
<br>
실제로 자살 관련 기사를 많이 접하고, 주변에서도 우울증으로 인해 병원을 찾는 사람들을 자주 볼 수 있습니다.   
국민건강보험공단에 따르면, 2020년 우울증 진료를 받은 인원은 100만 461명에 달합니다.   
국민 4명 중 1명이 정신 질환을 경험하지만, 정부의 정신건강 예산은 세계보건기구(WHO) 권장치의 절반에도 미치지 못합니다.   
<br>
이러한 배경을 바탕으로, 우울증 지수에 영향을 미치는 변수를 파악하고 이에 대한 정책적 해결책을 모색하기 위해 본 프로젝트를 기획하였습니다.  

<br>

## 👩🏻‍💻 팀원 소개 및 역할

### ✔️ 팀원
- [❤️ 공예림 ❤️](https://github.com/yelimkong)
- [💛 김란 💛](https://github.com/raneeKim)
- [💙 한수빈 💙](https://github.com/bonasoobin)

### ✔️ 역할 분담
프로젝트를 진행하며 모든 팀원이 머신러닝 프로세스에 대한 경험을 쌓기 위해 데이터 수집 및 전처리, 탐색적 데이터 분석(EDA), 모델링, 파라미터 튜닝, 그리고 인사이트 도출과 같은 다양한 단계들을 함께 수행했습니다. 
작업의 관리를 용이하게 하기 위해, 각 팀원의 이름을 사용하여 별도의 브랜치(yelim, ranee, soobin)를 만들어 기록했습니다. 
<br>

### ✔️ 담당 모델
- GradientBoost : 공예림   
- Polynomial Regression / Ridge: 김란  
- SVR / RandomForest: 한수빈  
<br>



## 📅 프로젝트 진행 기록

### ✔️ 수행 기간
2023.12.29 ~ 2024.01.18 (3주)

### ✔️ 세부 진행 기록
- 23-12-29 : 주제 정하기
- 24-01-02 : 데이터 수집  
- 24-01-04 : 데이터 수집 및 전처리
- 24-01-07 : 데이터 전처리
- 24-01-11 : 데이터 전처리 및 EDA
- 24-01-15 : 모델링
- 24-01-16 : 최종 모델 선정 및 결론 정리
- 24-01-18 : 깃허브 readme 작성 및 노션 정리
<br>


## 📊 데이터 소개
### ✔️ 원본 데이터
- 우울증 환자 수 &nbsp; [출처](https://www.data.go.kr/data/15118810/fileData.do)
- 평균연령 &nbsp; [출처](https://jumin.mois.go.kr/etcStatAvgAge.do)
- 총인구수 &nbsp; [출처](https://jumin.mois.go.kr/)
- 스트레스 인지율 &nbsp; [출처](https://kosis.kr/statHtml/statHtml.do?orgId=101&tblId=DT_1YL0000_1&vw_cd=MT_GTITLE02&list_id=11_21&obj_var_id=A&itm_id=11110&seqNo=&conn_path=MT_GTITLE02&path=%252FstatisticsList%252FstatisticsListIndex.do)
- 고용률 &nbsp; [출처](https://kosis.kr/statHtml/statHtml.do?orgId=101&tblId=DT_1DA7004S&vw_cd=MT_ZTITLE&list_id=B11&seqNo=&lang_mode=ko&language=kor&obj_var_id=&itm_id=&conn_path=MT_ZTITLE)
- 코로나 확진자 수 &nbsp; [출처](https://www.data.go.kr/data/15124288/fileData.do)
- 인구 1인당 지역사회 정신건강 예산 &nbsp; [출처](https://kosis.kr/statHtml/statHtml.do?orgId=117&tblId=DT_920023_A010)
- 전국 도시 공원 정보 표준 데이터 &nbsp; [출처](https://www.data.go.kr/data/15012890/standard.do)
- 공공시설 운영 현황 &nbsp; [출처](https://www.lofin365.go.kr/portal/LF5110000.do?pdtaId=9YJWO8ESQV63PIUNS62Q1211398&rdIncrYn=Y&frstParamYn=Y)
- 정신건강검사 결과  &nbsp; [출처](https://kosis.kr/statHtml/statHtml.do?orgId=350&tblId=DT_35007_N1180&vw_cd=MT_ZTITLE&list_id=350_35007_A001&seqNo=&lang_mode=ko&language=kor&obj_var_id=&itm_id=&conn_path=MT_ZTITLE)

### ✔️ 변수 선정 이유
여러 논문과 기사, 정부 기관에서 발표된 통계 결과들을 바탕으로 우울증의 발생과 관련이 있을 것으로 예상되는 **평균연령, 총인구수, 스트레스인지율, 고용률, 코로나 확진자 수, 1인당 정신건강 예산, 공공시설 개수**를 독립변수로 선택하여 분석에 활용하기로 결정하였습니다. <br>

### ✔️ 데이터 세부 사항
+ 기준 : 자치구 단위<br>
+ 데이터 기간 : 2018년 ~ 2022년
+ 데이터 개수 : 1250개<br>
1. 시도 <br>
2. 자치구 <br>
3. 행정번호 <br>
4. 년도 <br>
5. 우울증 환자 수<br>
6. 평균연령 <br>
7. 총인구수 <br>
8. 스트레스 인지율 <br>
9. 고용률 <br>
10. 코로나 확진자 수<br>
11. 1인당 정신건강 예산(원) <br>
12. 공공시설 개수 <br>
13. 우울증 지수  ----> 종속변수 <br> (자치구별 인구 수 / 시도별 인구 수) * ((가벼운 우울증상 * 0.2  ) + (중간정도 우울증 의심 * 0.3) + (심한 우울증 의심 * 0.5 )) * 0.01
<br>



## 💡 데이터 전처리
+ (1) `int`형이었던 행정번호 컬럼은 `object`형으로 형변환
+ (2) 2018년, 2019년의 코로나 확진자 수 0명으로 대체 
+ (3) 공공시설 데이터와 공원 데이터 자치구 단위로 통합(공원 데이터 내 묘지공원(기피시설) 제외)
+ (4) 공원 데이터는 2023년 기준 누적 데이터이므로 자치구명 변경된 데이터는 자체 수정(대구광역시 군위군 -> 경상북도 군위군)
+ (5) 시도, 자치구, 행정번호 컬럼은 식별자 컬럼이기 때문에 삭제 <br><br>
**결측값 처리**
+ (6-1) 서울, 부산, 대구, 인천, 광주, 대전, 울산 등 7개 광역시의 2018-2020년 자치구별 고용률 데이터 결측치는 시도 데이터로 대체 처리
+ (6-2) 1인당 정신건강 예산 데이터는 자치구별 정신건강 예산 데이터가 부재하여, 시도별 데이터로 대체 처리
+ (6-3) 세종특별자치시, 제주특별자치도의 5년간 스트레스 인지율 데이터는 시도 데이터로 대체 처리
+ (6-4) 공공시설 데이터 중 2021년 데이터 부재로 2020년과 2022년의 평균값으로 대체
<br>

## 💡 탐색적 데이터 분석(EDA)
+ (1) 변수 간 상관관계 행렬과 산점도 확인 → 선형관계가 없다는 것을 확인
+ (2) `VIF` 분석을 통한 다중공선성 확인 → **다중공선성 없는 것으로 확인**
+ (3) `boxplot`을 통해 이상치 확인 후, 이상치에 민감하지 않은 `RobustScaler`을 진행
+ (4) **`ACF` 그래프를 통해 년도 변수가 독립적임을 확인** → 년도 변수 삭제


  <p align="center"><img src="https://github.com/yelimkong/depression-analysis/assets/48948604/d5cccbb7-b31c-4f37-ac8c-a73d8b5745a4"></p>

raw 데이터에서 변수별 히스토그램을 그려보았을 때, 스트레스 인지율과 고용률 변수는 비교적 정규분포와 유사한 형태를 보이며, 평균 연령 변수는 비교적 균등하게 퍼져있으며 중앙값 주위에 집중된 모습을 보입니다. 다른 대부분의 변수들은 낮은 값에서 높은 빈도를 보이고 오른쪽으로 긴 꼬리를 가지고 있습니다. 
<br>
<br>

<p align="center"><img src="https://github.com/yelimkong/depression-analysis/assets/48948604/0b93b44f-3669-40b9-9d46-0d5464eddadb"></p>


변수 간의 상관관계를 분석한 결과, 우울증 지수와 우울증 환자 수는 강한 상관관계를, 우울증 지수와 고용률은 중간 정도의 음의 상관관계를 띄는 것을 확인할 수 있었습니다.
<br>
<br>

<p align="center"><img src="https://github.com/yelimkong/depression-analysis/assets/48948604/2f65e7e2-c1f5-4e28-bfed-a9f29e083e8c"></p>

독립변수들과 종속변수(우울증 지수)간의 산점도를 확인하였을때 모두 비선형관계를 보이고 있습니다.
<br>
<br>
<br>

<table class="tg">
<thead>
  <tr>
    <th class="tg-nbj5">VIF Factor</th>
    <th class="tg-nbj5">features</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-t1ow">5.39</td>
    <td class="tg-t1ow">총 인구 수</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3.09</td>
    <td class="tg-c3ow">우울증 환자 수</td>
  </tr>
  <tr>
    <td class="tg-t1ow">2.72</td>
    <td class="tg-t1ow">평균 연령</td>
  </tr>
  <tr>
    <td class="tg-c3ow">2.26</td>
    <td class="tg-c3ow">공공시설 개수</td>
  </tr>
  <tr>
    <td class="tg-t1ow">1.88</td>
    <td class="tg-t1ow">고용률</td>
  </tr>
  <tr>
    <td class="tg-c3ow">1.44</td>
    <td class="tg-c3ow">코로나 확진자 수</td>
  </tr>
  <tr>
    <td class="tg-x2zk">1.32</td>
    <td class="tg-x2zk">1인당 정신건강 예산(원)</td>
  </tr>
  <tr>
    <td class="tg-c3ow">1.29</td>
    <td class="tg-c3ow">스트레스 인지율</td>
  </tr>
</tbody>
</table>
VIF 분석을 통해 다중공선성이 없음을 확인하였습니다.
<br>
<br>
<br>
<br>

<p align="center"><img src="https://github.com/yelimkong/depression-analysis/assets/48948604/74b45506-a71b-48fa-9a32-29b94ab1420a"></p>
박스플롯을 확인한 결과, 이상치가 존재하지만 모두 필요한 값이기에 이상치에 민감하지 않은 RobustScaling 을 진행하였습니다.
<br>
<br>
<br>
<br>

<p align="center"><img src="https://github.com/yelimkong/depression-analysis/assets/48948604/e8dbbf60-8ee8-422f-bc04-e3a5351013b4"></p>
코로나 확진자 수는 해마다 증가하였고, 공공시설개수는 누적 데이터이므로 자가상관관계가 있을거라고 추측하였습니다.   <br>
실제로 결과 그래프들을 보면 다른 데이터들 보다는 자가상관관계가 있는걸로 나타내어지나, 그 계수가 0.2로 아주 약한 상관관계를 보이므로 다른 변수와 동일하게 각 데이터들을 독립적인 데이터로 보아도 무관하다고 판단하였습니다.  <br>
따라서 이후 년도 변수를 삭제하였습니다.

<br>
<br>
<br>

## 💡 모델링
#### ✔️ 변수 간 비선형 관계임을 확인한 후 비선형 모델로 모델링

<table class="tg">
<thead>
  <tr>
    <th class="tg-y698" rowspan="2">알고리즘 모델</th>
    <th class="tg-y698" colspan="2">모델 성능 평가 지표</th>
    <th class="tg-y698" rowspan="2">비고</th>
  </tr>
  <tr>
    <th class="tg-y698">r²</th>
    <th class="tg-y698">rmse</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-y698">GradientBoost</td>
    <td class="tg-c6of">0.987</td>
    <td class="tg-c6of">0.131</td>
    <td class="tg-c6of">train/test (train의r² : 0.999)</td>
  </tr>
  <tr>
    <td class="tg-y698">Polynomial Regression</td>
    <td class="tg-c6of">0.734</td>
    <td class="tg-c6of">0.626</td>
    <td class="tg-c6of">cross_validation (cv=10)</td>
  </tr>
  <tr>
    <td class="tg-y698">Ridge Polynomial Regression</td>
    <td class="tg-c6of">0.835</td>
    <td class="tg-c6of">0.492</td>
    <td class="tg-c6of">cross_validation (cv=10), alpha=1</td>
  </tr>
  <tr>
    <td class="tg-y698">SVR</td>
    <td class="tg-c6of">0.752</td>
    <td class="tg-c6of">0.458</td>
    <td class="tg-c6of">cross_validation (cv=5)</td>
  </tr>
  <tr>
    <td class="tg-y698">RandomForest</td>
    <td class="tg-c6of">0.713</td>
    <td class="tg-c6of">0.586</td>
    <td class="tg-c6of">train/test</td>
  </tr>
</tbody>
</table>

👉 가장 성능 평가가 높은 `GradientBoost`는 overfiting의 양상이 보였으므로(`cross validation`에서의 r²값은 0이하) <br> &nbsp; &nbsp; &nbsp; 최종 모델은 `Ridge Polynomial Regression` 으로 선정
<br>
<br>

### ✔️ 결과 해석
<p align="center"><img src=https://github.com/yelimkong/depression-analysis/assets/131862831/744fc37e-2241-49cc-a2e9-8ca9afe1ba7b></p>

<br>

#### 
그래프를 보았을 때 `ridge penalty`가 1일때 가장 낮은 RMSE값과 가장 높은 R²값을 보였습니다. <br>
또한,  cv값을 5와 10으로 조정하여 `cross validation` 진행하였고 그 결과 cv값이 10일 때 더 좋은 성능을 확인할 수 있었습니다.  <br>
결론적으로 cv값은 10, `ridge penalty` 1로 모델 성능 평가를 최종적으로 선정하였습니다.
<br>

<p align="center"><img src=https://github.com/yelimkong/depression-analysis/assets/131862831/c120c433-3a70-4600-9c6e-42cdcd74f998></p>

<br>
잔차의 등분산성 그래프(왼쪽)를 보았을때, 잔차 플롯에서 어느 정도 0 주변에서 관측 되는, 기울기가 0인 빨간 선을 확인하였습니다. <br>
이 중 0에서 많이 벗어나는 몇몇의 데이터는 이상치로 판단하였고(실제 데이터에서 제거되지 않은 이상치),<br>
0을 중심으로 특정한 패턴을 가지고 있지 않음을 확인할 수 있으며 잔차가 0을 중심으로 크게 벗어나지 않음을 확인할 수 있습니다.<br><br>
잔차의 Q-Q(Quantile-Quantile)플롯(오른쪽)을 보았을때, 데이터의 대부분은 빨간색 선 주변에 잘 위치해 있어 중앙 부분에서는 정규분포를 잘 따르는 것처럼 보입니다. 그러나 양쪽 끝에서는 점들이 선에서 벗어나는 것을 볼 수 있습니다. 이는 앞 경우와 마찬가지로 이상치로 판단할 수 있습니다.
<br>
<br>

## ✔️ 결론
지난 5년간의 전반적인 우울증 수치는 증가하였습니다.<br><br>
이에 보건복지부에서는 지난 12월 정신건강 증진을 위해 100만 명 대상을 목표로 전문 심리상담을 지원 등을 포함한 4대 전략을 추진할 것이라 발표하였습니다. 이러한 다양한 정책을 바탕으로 저희는 우리나라의 우울증 수치를 낮추는 데 기여할 수 있는 정책에 대해 고민하였습니다.<br><br>
최근 어린이 돌봄의 중요성이 부각되면서 등하굣길에서 어린이와 함께하는 어른이 필요한 경우가 많아지고 있습니다. 해당 부분에 대한 일자리 창출을 통해 우울증 환자를 포함한 다양한 사람들에게 사회 활동 기회를 제공할 것을 제안합니다. 사회 활동과 고용률 제고가 우울증 수치를 완화 시키는 데 도움이 될 것으로 판단했기 때문입니다.<br><br>
이러한 정책과 저희가 제안한 노력이 함께 이루어짐으로써 우리 사회는 더욱 건강하고 안정된 환경으로 발전할 것으로 기대됩니다.
<br>
<br>

## ✔️ 한계점
이 프로젝트는 우울증 지수를 객관적인 지표들로 이해하기 위한 방법으로써 전국의 각 자치구별로 선정된 지표들을 이용하였는데, 이러한 한정된 데이터를 이용한 예측은 한계가 명확하다는 결론을 내릴 수 있다고 생각합니다. <br><br>
즉, 개인의 지표의 값이 변화하게 된 근본 요인들을 추적할 수 없었으며, 이를 극복하기 위해서 개인의 설문조사로 진행된 자료의 지표로 모델링을 진행했으면 보다 효율적인 관계성 분석으로 진행이 되었을 것이라 생각합니다.<br>
<br>


    

## 🔍 참고 자료

### ✔️ 논문
1) 박병선, 2012, 자살성에 영향을 미치는 스트레스와 우울의 상호적 관계에 대한 경로분석: 성별 및 연령집단별 비교
2) 이연수, 2020, 도시환경요소와 우울증과의 상호관계에 관한 연구 - COVID-19 시대의 도시계획전략을 중심으로

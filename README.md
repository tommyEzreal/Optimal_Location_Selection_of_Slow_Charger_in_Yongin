# 용인시 전기차 완속충전소 입지선정 
> 2022.09 - 2022.11   
> 한국지능정보사회진흥원 주관 2022 빅콘테스트 데이터분석리그 챔피언부문 대상(과학기술정보통신부 장관상)  
> 길잃은아이들팀 

<br/>

## Team 
🧑🏻‍💼 **Seo Kwang Wook**   
👨🏻‍💻 **Lee Ji Hwan    
👨🏻‍💻 Ryu Seung Gi    
👩🏻‍💻 Lee Ju Yeong    
👩🏻‍💻 Yoon Hye Ju**    

<br/>

## 분석 배경

- 화석연료의 가격 상승과 환경문제 심화로 인한 정부의 전기차 보급정책 마련
- 국내 전기차 대수의 증가추세에 비해 부족한 현재의 충전관련 인프라
- 충전기의 설치 속도가 전기차 보급 확산의 추세를 따라가지 못함
- 경기도와 용인시 또한 정부의 정책과 동일하게 다양한 보급정책을 시행하며 충전 인프라 확충에 나서는 중 
- 최적의 충전소 입지선정을 위해 설치 장소별 수요의 스코어링과 수익성계산을 통한 과학적인 입지선정 근거가 필요  

## 대회 과제
- 용인시 지역의 완속충전 입지선정 모델 개발 
- 충전시간이 긴 완속충전 특성을 고려해 일정시간 이상 머무르는 생활거점에 집중적으로 완속충전 거점이 요구됨
- 각 목적지의 정확한 기종점 수요분석을 위해 입지선정을 거주지 기준과 활동지 기준으로 나누어 제시
- 적절한 외부데이터의 홣용 및 충전입지 선정의 타당한 근거제시를 위한 지수식 및 모델의 완성도
- 사업적 목적을 고려하여 최대수요 최소비용등의 수익성원칙을 고려

<br/>

## 분석과정 

### 분석흐름도 
<img width="1058" alt="image" src="https://user-images.githubusercontent.com/100064247/209634651-ee5f392c-6285-4aea-bba2-2cda2cbf0357.png">

- 대회에서 설정한 조건들을 꼼꼼하게 이행하는 결과물을 도출하는 것을 우선적인 목표로 설정
- 급속이 아닌 완속충전의 입지선정이기 떄문에 입지가 사용자가 일정시간 이상 머무를 수 있는 특정위치로 제한
- 거주지와 활동지를 구분하여 제시하기 위해 아파트/공동주택등이 포함된 거주지기준 입지후보, 공공시설/대규모점포/직장 등이 포함된 활동지기준 입지후보 선정 
- 선정한 후보들 중 "어느곳이 충전소 입지 우선순위를 부여받아야할까"를 알 수 있는 지수를 개발
- 전기차 충전기 설치는 인프라 구축사업이기 때문에 미래에 증가할 수요까지 종합적으로 고려할 필요성
  * 이미 입지가 확정된 위치를 변경하기 어렵고
  * 상대적으로 유지비용에 비해 초기비용이 많이 필요한 사업이기 때문
- 각 입지의 현재수요와 잠재수요를 종합적으로 고려 후 주어진 또다른 과제인 수익성 고려를 위해 각 입지가 최소비용의 조건을 만족하도록 최종결과 도출 

### 분석에 활용된 외부데이터 목록 
<img width="1223" alt="image" src="https://user-images.githubusercontent.com/100064247/209635967-037261a6-eb87-48e6-8064-a9ff314159e4.png">






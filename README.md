# Elderly_people_living_alone
Prediction of population of "elderly people living alone" in Seoul

## 개요
고령화 사회 문제 중 가장 심각한 노인의 고독사이다.
이 문제를 해결하기 위해 앞으로 독거노인이 어디에 주거하게 될 것인지 예측이 필요하다고 생각했다.
그래서 먼저 데이터가 잘 갖추어진 서울시 내의 독거노인을 예측해보고자 했고
서울시 공공데이터를 활용해 간접적으로 독거노인의 주거를 예측하고자 했다.

## 프로젝트 목표
서울시 공공데이터로 서울시 내 동별 독거노인 수를 예측할 수 있는 모형을 설계

### DATA SET (2012년 , 서울시 동별 자료)
- 출처 : 서울 열린데이터 광장 (http://data.seoul.go.kr/)
- Y(target)  : 독거노인 수
- X(feature) : 장애인, 화재 발생 건수, 은행 지점, 노인 복지시설, 전입인구, 전출인구
- Samples : 422

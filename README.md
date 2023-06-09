<p align = "center"><img src="https://user-images.githubusercontent.com/109575863/203251753-4d6cfc25-2ee0-4c28-8dff-d9478c7f294e.png" width="350" height="350"/></p>
<h3><p align = "center">개인의 입맛과 성향에 맞는 빵 맛집 추천서비스</p>

<br>

## 프로젝트 기간
2022/10/16 - 2022/11/10  

<br>

## 프로젝트 개요
- 나의 빵 입맛을 찾고, 개인의 취향을 저격한 빵집 추천 시스템을 만들기 위해 웹스크래핑, 텍스트분석으로 빵과 빵집의 특성 추출 및 군집화
- 서비스 이용자는 취향을 쉽게 입력할 수 있고, 서비스 제공자는 적절한 결과를 추천할 수 있는 유형 테스트 방식으로 구현
- 베타서비스를 통해 서비스 분석 및 개선 진행

<br>

## 빵BTI 프로젝트 소개
<br>

<p align = "center">MBTI 테스트 유형을 차용하여 쉽고, 재미있고, 편하게 <br> 
<b>빵 입맛 유형을 알아보고 추천 빵집 리스트 받아보기</b></p>


<br>

<p align = "center"><a href = "https://bbangbti.waveon.io/">🥐 빵BTI 유형테스트 하러가기 🥐</a></p>



<br>

<p align = "center"><img src="https://user-images.githubusercontent.com/109575863/203253394-5d33736c-0e95-446c-913e-ce5d68867f69.gif" width="350"/></p>

<br>


## 서비스 제작 방법
마켓컬리 베이커리 카테고리 상품 설명과 네이버 플레이스 빵집 리뷰 텍스트를 분석

- K-means 군집분석을 활용하여, 추출된 빵 특성(e.g. 달달, 바삭, 짭짤, 꾸덕)에 따라 그룹핑
- 네이버 플레이스 빵집 리뷰 텍스트 분석을 통해, 빵집의 특성(e.g. 인기 많은, 선물 하기 좋은) 추출 및 그룹핑

<br>

## 서비스 제작에 사용한 데이터의 범위
- 인스타그램 최근 3개월(22.07~22.10)언급량 순위 반영헤 트렌디한 18 종류의 빵 선정
- 서울 내의 빵집으로 한정하여, 빵 종류 마다 네이버 플레이스 영수증 리뷰 500개 이상의 인기 빵집만을 선별

<br>

## 사용 툴

Microsoft Excel | `Python` (Kiwi, koNLPy 토크나이저) | `Tableau` (빵집 지도 시각화)

<br>

### 팀원
권우리
박지혜
안연경
유혜승
최단비
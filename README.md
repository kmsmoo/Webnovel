# Naver Webnovel recommand system
* 현재의 웹소설 계는 개인화된 추천 시스템이 없다
* Content-based 추천 시스템의 경우 유저의 정보를 얻을 수 있어야 한다
  - 실질적으로 데이터 분석을 할만한 분류 정보를 얻을 수 없음
* Collaborative filtering을 통한 추천 시스템
  - memory-based의 방식
  - user-based, item-based을 둘 다 분석에 활용
  
* 여기에 유저가 소설을 선택하는 것에 있어서의 특징을 포함
  - make model에서 해보았던 회귀 분석과 Classification을 통한 인사이트 도출

# novelcrawling
* 네이버 웹소설 크롤링
  - 크롤링의 경우 최대한 손이 안가도록 함수화
  - 클래스화를 할 예정

# make model
* OLS 분석(회귀 분석)
  - 작가와 장르의 경우 하트 수와 관심 수에 유의미한 영향을 끼친다.
* 장르 간 classification
  - SF&판타지와 퓨전의 경우 서로 Classification이 잘 안된다.
  - 소설 자체를 읽어봐도 실제로 사람도 분류하기 애매하다 

# Recommand system
* 위에서 진행했던 프로그램의 재현
  - 전처리와 실제 기능 제작

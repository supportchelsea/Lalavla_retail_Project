# 랄라블라 프로젝트

1. 사용 데이터
- 기상 데이터 (20180101~20181231) : 지역 별 기온, 강수량, 풍량 등
- 랄라블라 데이터(20180101~20181231) : 지역 별 카테고리 판매량
- SNS 데이터 (20180101~20181231) : 카테고리 별 search keyword 에 대한 18년도 트위터 크롤링 데이터

2. 사용 기술
- Selenium과 Chromecast를 이용하여 데이터 크롤링 (colab 사용)
- Gensim 패키지를 사용하여 word2vec 모형을 생성, 시각화
- Surprise 패키지를 사용하여 item-based recommendation system 구축

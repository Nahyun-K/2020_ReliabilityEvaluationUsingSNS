# 2020_ReliabilityEvaluationUsingSNS


## Description
SNS(Instagram) 계정을 검색하여 199개의 데이터 중 해당 계정의 발전 가능성을 확인할 수 있습니다

![gradeproject1](https://github.com/Nahyun-K/2020_ReliabilityEvaluationUsingSNS/assets/80201895/7e89d81a-d684-41a5-9480-6191ff2ffea1)


## Environment
Library : jquery, d3.js, chart.js, os, pandas, numpy

Framework : Selenium

DB : MySQL

IDE : vscode, Jupyter Notebook, rstudio

SNS : Instagram

## Usage

![gradeproject2](https://github.com/Nahyun-K/2020_ReliabilityEvaluationUsingSNS/assets/80201895/13e3b250-237a-4494-b57c-0885cf3ebdff)

검색창에 ID(인스타그램 계정 ex) yuna131 ) 검색

해당 계정의 팔로워 수, 팔로잉 수, 게시글 수, 랭킹을 알 수 있습니다

![gradeproject3](https://github.com/Nahyun-K/2020_ReliabilityEvaluationUsingSNS/assets/80201895/7ec314dd-83a8-4e37-9844-0145286b56d1)

해당 계정의 발전 가능성 랭킹을 확인할 수 있습니다

현재 팔로워 수와 다음주 예측 팔로워 수를 알 수 있습니다

![gradeproject4](https://github.com/Nahyun-K/2020_ReliabilityEvaluationUsingSNS/assets/80201895/9065e40f-d34b-441a-9978-0fac600048d8)


![gradeproject5](https://github.com/Nahyun-K/2020_ReliabilityEvaluationUsingSNS/assets/80201895/e49927a7-d71b-43a1-930f-5ed0c1f096c9)


- 4주간 순위 변화
- 포스팅한 게시물
- 지난 7일간 받은 좋아요 개수
- 포스트 업로드 주기
- 지난 8주간 팔로워 수 변화
- 지난 8주간 팔로잉 수 변화
- 지난 8주간 작성한 전체 게시글 수 변화


## Files

jsondata
- sns 계정의 데이터를 json 형식으로 저장

python_coding
- 데이터 수집
- instagram을 크롤링하여 데이터를 수집

R
- 데이터 전처리

UI
- d3.js, chart.js로 데이터 분석한 결과를 웹으로 제작
- html, css, js



24-2 프로그래밍
데이터 분석 프로젝트
<h2>진로 탐색을 위한 직업 추천 시스템:고용24와 NCS 매핑을 통한 맞춤형 정보 제공</h2>

1. 고용24 사이트의 직업 소개 페이지를 웹스크래핑하여 직업 관련 데이터 수집
   -. 직업, 직업이 하는 일, 관련 학과, 전망
   -. 고용노동부 직업코드를 활용하여 모든 직업 페이지를 스크래핑 진행
2. NCS 직무 능력 요소 데이터 전처리 작업 진행
   -. 시트 통합 및 중복 데이터 제거
3. 유사도 계산식을 이용해 고용24 직업 데이터와 NCS 직무 능력 요소 매핑
   -. 유사도 계산식 : TF-IDF 벡터화, 코사인 유사도
   -. 직업 : 직무 능력 요소 = 1:N
4. 학과 검색 및 학과 연관 직업/직무 능력 요소 페이지 구축
   -. 3번 데이터를 json으로 추출하여 활용 

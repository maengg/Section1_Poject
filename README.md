# Section1_Poject

데이터 분석을 통해 다음 분기 어떤 게임을 설계하는 것이 유리한지 예측. <br>

## 문제정의 <br>

1. 게임 장르와 출고량간에는 관계가 있을 것이라는 가설 설정.
2. 게임 장르와 플랫폼간에는 관계가 있을 것이라는 가설 설정.

*위 두가지 가설을 기준으로 높은 출고량을 기록하는 장르를 선택하고 해당 장르에 어울리는 플랫폼을 선택.* <br>

## 진행 과정 <br>

1. Pandas, Numpy 활용하여 데이터 전처리.
2. 카이제곱 검정 통해 설정한 가설 검정.
3. matplotlib를 활용한 시각화로 연도별 장르 트렌드, 장르 진입장벽 등 데이터 분석.
4. 시각화와 통계 테스트 결과로 결론 도출.
<br>

## 문제점 및 한계점 <br>
1. 데이터 중복 확인 등의 절차를 거치지 않았다.
2. 전체 지역 출고량을 기준으로 분석을 시도했는데, 이는 일본 지역의 선호도를 반영하지 못하는 방식이었다.
3. 연도별 트렌드 분석 중 2015~2020년의 데이터가 부족하여 이를 잘 반영하지 못했다.

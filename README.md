# San Francisco Crime Data Analysis

### Data
Kaggle의 San Francisco Crime Classification 대회에서 제공한 데이터<br>
: https://www.kaggle.com/c/sf-crime

<br>

### Object
샌프란시스코의 범죄 건수를 줄이기 위한 효율적인 경찰 배치 제시

<br>

### EDA
<li><strong>Date 기준으로 범죄 발생 건수, 범죄 현황 분석</strong></li>
- 전체 기간, 연도별, 계절별, 월별, 요일별 범죄 발생 현황 분석 <br>
- 일출, 일몰 데이터를 수집하여 낮과 밤 각각에 많이 발생하는 범죄 분석<br>
    (일출, 일몰 데이터 수집: https://sunrise.maplogs.com/san_francisco_county_ca_usa.727.html?year=2003)
</p>
<li><strong>범죄 발생 위치를 기준으로 범죄  신고 건수, 범죄 현황 분석</strong></li>
- 범죄 건수가 가장 많은 '절도'에 대해 dstrict별 범죄 발생 건수 파악<br>
- 범죄 건수가 많은 위치를 시각화

<br>

### Result
금요일 낮에 Union Square 주변에서 절도 범죄가 많이 발생함을 확인. 이를 기준으로 경찰 배치를 제안
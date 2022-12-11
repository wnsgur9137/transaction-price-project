# **transaction-price-project**

서울과 부산의 아파트 값을 예측한다.  


<br>
<br>
<br>


# **목차**

## [0. 사용 데이터](#0-사용-데이터)
## [1. 데이터 전처리](#1-데이터-전처리)  
## [2. 특성 선택](#2-특성-선택)  
## [3. 모델 훈련](#3-모델-훈련)  
## [4. 파라미터 최적화](#4-파라미터-최적화)  
## [5. 모델 합치기](#5-모델-합치기)  

<br>
<br>
<br>

# **0. 사용 데이터**

1. tran.csv
2. test.csv
3. park.csv
4. day_care_center.csv
5. 서울_행정구역_경계.json
6. 부산_행정구역_경계.json
7. 서울시_소득분위.xls

<br>
<br>


## **train.csv, test.csv**
<table border='1'>
<thead border='2'>
<tr>
<td>컬럼명</td><td>컬럼 설명</td>
</tr>
</thead>
<tbody>
<tr><td>apartment_id</td><td>아파트 아이디</td></tr>
<tr><td>city</td><td>도시(서울특별시, 부산광역시)</td></tr>
<tr><td>dong</td><td>동(주소)</td></tr>
<tr><td>jibun</td><td>지번(주소)</td></tr>
<tr><td>apt</td><td>아파트단지 이름</td></tr>
<tr><td>addr_kr</td><td>주소</td></tr>
<tr><td>exclusive_use_area</td><td>전용면적</td></tr>
<tr><td>year_of_completion</td><td>설립일자</td></tr>
<tr><td>transaction_year_month</td><td>거래년월</td></tr>
<tr><td>transaction_date</td><td>거래날짜</td></tr>
<tr><td>floor</td><td>층</td></tr>
<tr><td>transaction_real_price</td><td>실거래가</td></tr>
</tbody>
</table>

<br>
<br>

## **park.csv**
<table border='1'>
<thead border='2'>
<tr>
<td>컬럼명</td><td>컬럼 설명</td>
</tr>
</thead>
<tbody>
<tr><td>city</td><td>도시(서울특별시, 부산광역시)</td></tr>
<tr><td>gu</td><td>지번(주소)</td></tr>
<tr><td>dong</td><td>동(주소)</td></tr>
<tr><td>park_name</td><td>공원 이름</td></tr>
<tr><td>park_type</td><td>공원 종류</td></tr>
<tr><td>park_area</td><td>공원 넓이</td></tr>
<tr><td>park_exercise_facility</td><td>공원 보유 운동시설</td></tr>
<tr><td>park_entertrainment_facility</td><td>공원 보유 유희시설</td></tr>
<tr><td>park_benefit_facility</td><td>공원 보유 편의시설</td></tr>
<tr><td>park_cultural_facility</td><td>공원 교양시설</td></tr>
<tr><td>park_facility_other</td><td>공원 보유 기타시설</td></tr>
<tr><td>park_open_year</td><td>개장년도</td></tr>
<tr><td>reference_date</td><td>데이터 기준 일자</td></tr>
</tbody>
</table>

<br>
<br>
<br>

# **1. 데이터 전처리**



<br>
<br>
<br>

# **2. 특성 선택**



<br>
<br>
<br>

# **3. 모델 훈련**



<br>
<br>
<br>

# **4. 파라미터 최적화**



<br>
<br>
<br>

# 5. 모델 합치기


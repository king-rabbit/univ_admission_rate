# univ_admission_rate
대학 신입생 충원율 분석(데이터카우)


데이터 출처
- '대학알리미'(www.academyinfo.go.kr): 대학 신입생 충원율 현황 (대학별/학과별)
- '교육통계서비스'(kess.kedi.re.kr): 대학 학교/학과별 데이터셋

주소-좌표 변환
- Geocoder-Xr 활용 (http://www.gisdeveloper.co.kr/?p=4784)

데이터셋
- 2020년_대학_통계.csv: 2020년 4월 집계한 데이터로, 대학 학제, 학교명, 시도, 주소, 입학정원(정원내 및 정원외), 모집인원_정원내, 신입생_충원율 등 데이터. 일반대학은 '분류' 칼럼이 'university'로, 전문대학은 'junior_college'로 라벨링 되어 있음.
- 2020년_대학_학과별_통계.csv: 학과별 세부 통계 제공.
- 3개년_대학_신입생_충원율.csv: 2018-2020년 대학별 신입생 충원율 데이터
- 대학_신입생_충원_현황_2018.xlsx, 대학_신입생_충원_현황_2019.xlsx: 대학알리미 출처의 2018, 2019년도 통계. (교육통계서비스 데이터셋과 결합하지 않음)

기타
- 주피터 노트북에서 mapbox 시각화는 개별적으로 token을 발급받아 입력 후 실행하시면 됩니다.

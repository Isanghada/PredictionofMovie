# 데이터 저장용 공간

### 1. 영화 데이터
- KOBIS 공식 통계 : https://www.kobis.or.kr/kobis/business/stat/offc/searchOfficHitTotList.do?searchMode=year
- 한국영화연감(1971~2010) 통계를 기준으로 정리한 것이며, 2011년부터는 통합전산망을 기준으로 일정한 주기(매월, 매년)로 마감처리하여 산출되는 통계정보
- 컬럼 정보 
  - 순번 : 인덱스, 수치형
  - 영화명 : 영화명, 범주형
  - 감독 : 감독명, 범주형(다수일 경우 ', '로 구분)
  - 제작사 : 제작사명, 범주형(다수일 경우 ', '로 구분)
  - 수입사 : 수입사명, 범주형(다수일 경우 ', '로 구분)
  - 배급사 : 배급사명, 범주형(다수일 경우 ', '로 구분)
  - 개봉일 : 개봉일, 날짜형('YYYY-MM-DD')
  - 영화유형 : 영화 유형, 범주형
  - 영화형태 : 영화 형태, 범주형('장편', '단편', '옴니버스')
  - 국적 : 영화 제작 국가, 범주형
  - 전국스크린수 : 개봉 첫 주 최대 스크린 수, 수치형
  - 전국매출액 : 전국 매출액, 수치형
  - 전국관객수 : 전국 관객수, 수치형
  - 서울매출액 : 서울 매출액, 수치형
  - 서울관객수 : 서울 관객수, 수치형
  - 장르 : 대표 장르, 범주형
    - 21개의 유형(<a href = 'https://www.kobis.or.kr/kobis/business/stat/online/onlineGenreStat.do?CSRFToken=yOhFhXI1uvJrdJ_SERa8YxZhVjS9tKCERgIId5CsBXA&loadEnd=0&searchType=search&sSearchYearFrom=2021&sSearchMonthFrom=02&sSearchYearTo=2021&sSearchMonthTo=08' target='_blink'>KOBIS 장르별 통계 기준</a>)
  - 등급 : 영화 시청 등급, 범주형
  - 영화구분 : 영화 구분, 범주형('일반 영화', '독립/예술영화')
---
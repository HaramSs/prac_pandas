# 10 minutes to pandas

- https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html#minutes-to-pandas

- date_range()
- 서로 다른 dtype
- tab 자동완성
- df.head(), df.tail(3)
- df.index / df.columns
- df.tp_numpy() : index나 열 레이블 없는 기본 데이터의 numpy 표현
- Numpy 배열은 배열 전체에 하나의 dtype, Pandas df는 열당 하나의 dtype
- df.describe() : 간단한 통계 요약
- df.T : 데이터 transposing
- df.sort_index() : 축에 따라 정렬
 axis : 값 0은 행을 식별, 1은 열을 식별
- df.sort_values() : 값에 따라 정렬
- 단일 레이블을 통과하면 열이 선택, df에 해당하는 시리즈가 생성
- df.loc[dates[0]] : 라벨과 일치하는 행 선택
- df.loc[:, ["A","B"]] : 선택된 열 레이블이 있는 모든 행 선택
- DataFrame.iloc[row_index, column_index]
- isin() : 필터링 방법 사용

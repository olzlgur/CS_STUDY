### 조인(Join)
- 데이터베이스 내의 여러 테이블의 레코드를 조합하여 하나의 열로 표현한 것
- 테이블로서 저장되거나 그 자체로 이용 가능한 결과 셋을 만들어낸다.
- 관계형 데이터베이스에서 서로 관계있는 데이터가 나뉘어 저장되므로 효과적인 검색을 위해 필요하다.

#### 조인의 종류
- 내부 조인(LEFT JOIN, 기본 조인)
  - 두 테이블의 공통된 레코드만 반환 ex) ```SELECT * FROM A INNER JOIN B ON A.ID = B.ID```
  - 암시적으로도 사용 가능 ex) ```SELECT * FROM A, B WHERE A.ID = B.ID```
- 외부 조인(OUTER JOIN)
  - 특정 테이블의 데이터가 모두 필요한 상황에서 사용한다.
  - LEFT (OUTER) JOIN
    - 좌측 테이블의 모든 데이터를 포함하는 결과 집합 생성 LEFT + 교집합
  - RIGHT (OUTER) JOIN
    - 우측 테이블의 모든 데이터를 포함하는 결과 집합 생성 RIGHT + 교집합
  - FULL OUTER JOIN
    - 오른쪽, 왼쪽 레코드의 합집합





참고자료
```
https://velog.io/@ragnarok_code/DataBase-조인Join이란
```

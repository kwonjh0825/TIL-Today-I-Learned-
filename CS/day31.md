## 제 1정규화

- 테이블의 컬럼이 원자값(Atomic Value), 즉 하나의 값을 갖도록 테이블을 분해
- 다음과 같은 규칙을 만족해야 함
    1. 각 컬럼은 하나의 속성만을 가져야 함
    2. 하나의 컬럼은 같은 종류나 타입의 값을 가져야 함
    3. 각 컬럼은 유일한 이름을 가져야 함
    4. 컬럼의 순서가 상관 없어야 함

## 제 2정규화

- 테이블의 컬럼이 완전 함수 종속을 만족하도록 테이블을 분해
    - 완전함수 종속: 기본키의 부분집합이 결정자가 되지 않는 것
- 다음과 같은 규칙을 만족해야 함
    1. 제1 정규형을 모두 만족해야 함
    2. 모든 컬럼에 부분 함수 종속이 없어야 함
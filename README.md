# python

## 가상환경 설정

1. 생성
```bash
python -m venv venv
```

2. 활성화
```bash
# linux / macOS
source venv/bin/activate
```

3. 비활성화
```bash
deactivate
```

4. jupyter lab 설치
```bash
pip install jupyterlab
```

5. jupyter lab 실행
```bash
jupyter lab
```

## [python 기초정보](01_intro.ipynb)

- 1. 데이터 타입
    - 1-1 Number
    - 1-2 Boolean
    - 1-3. String

- 2. 자료구조
    - 2-1. 시퀀스 자료형

        - 2-1-1. [list] : mutable
        - 2-1-2. (Tuple) : immutable
        - 2-1-3. range() : immutable
        - 2-1-4. 'String' : immutable

    - 2-2. 시퀀스 자료형

        - 2-2-1. {set} : mutable
        - 2-2-2. {Dict: ionary} : mutable

## [제어문](02_control_of_flow.ipynb)

- 1. 조건문
    - 1-1 if문
        - 1-1-1 else문
        - 1-1-2. 조건표현식

- 2. 반복문
    - 2-1. while문
    - 2-2. for문
        - 2-2-1. Dictionary반복
        - 2-2-2. break
        - 2-2-3. continue
        - 2-2-4. else
        - 2-2-5. pass
        - 2-2-6. match

## [함수](03_function.ipynb)

- 1. 함수의 선언과 호출
- 2. 함수의 return
- 3. 함수의 인수
    - 3-1. 위치인수
    - 3-2. 기본값
- 4. 키워드 인수
    - 4-1. 가변인자 리스트
    - 4-2. 정의되지 않은 키워드 인자 처리하기
    - 4-3. dictionary를 인자로 넣기(unpacking)
    - 4-4. lambda표현식
    - 4-5. 타입힌트
- 5. 이름공간(space)
- 6. 재귀

## [메소드](04_datastructure.ipynb)

- 1. 문자열(string) 메소드
- 2. 리스트(list) 메소드
    - 2-1. 리스트 복사(copy)
    - 2-2. 리스트 comprehension
- 3. 사전(dictionary) 메소드
    - 3-1. 사전 comprehension
- 4. 세트(set) 메소드
- 5. map, filter, zip
    - 5-1. map
    - 5-2. filter
    - 5-3. zip



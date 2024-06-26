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

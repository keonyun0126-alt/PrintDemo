# Python Print Examples — Quick Guide

이 저장소는 Python의 다양한 `print()` 사용법과 라이브러리를 활용한 출력 형식을 보여주고, VS Code, 터미널 및 Jupyter 환경에서의 실행법을 정리한 모듈입니다.

## 과제 파일 목록 (총 4개 요약)

### 1) `main_print_v1.py`
- **설명**: 파이썬 표준 `print()` 함수를 활용한 기초 출력 예제 코드 파일.
- **주요 기능 및 동작**:
  - 기본 문자열 및 변수 출력, 여러 값 출력 (`sep`, `end` 옵션 활용)
  - f-string, `format()` 함수, `%` 포맷팅 방식 비교
  - 딕셔너리 출력, 줄바꿈(`\n`) 및 삼중따옴표(`"""`)를 이용한 멀티라인 출력
  - f-string 내부 계산식 및 함수 호출 연산
- **실행 방법**:
  - VS Code 상단 **Run Python File** (▶️) 클릭
  - 터미널: `python main_print_v1.py`

### 2) `main_print_v1.ipynb`
- **설명**: `main_print_v1.py`와 동일한 실습 내용을 셀(Cell) 단위로 실행/확인할 수 있는 Jupyter Notebook 파일.
- **주요 기능 및 동작**:
  - 대화형 인터페이스(Jupyter Engine)를 통한 파이썬 코드 셀 실행
  - 셀별 실시간 출력 및 마크다운(Markdown) 문서 작성 기능 제공
- **실행 방법**:
  - VS Code에서 파일 오픈 후 커널(.venv) 지정 및 `Shift + Enter` 또는 **Run All** 클릭

### 3) `main_print_v2.py`
- **설명**: 외부 라이브러리인 `rich` 모듈을 활용하여 콘솔 출력을 시각적으로 꾸민 예제 파일.
- **주요 기능 및 동작**:
  - `rich.print`: 스타일 태그를 사용한 색상 및 폰트 스타일 적용
  - `Panel`: 박스 형태의 멀티라인 프로필 출력
  - `Table`: 딕셔너리 데이터를 깔끔한 표(Table) 형태로 시각화
- **실행 방법**:
  - 터미널에서 패키지 설치: `pip install rich`
  - 실행: `python main_print_v2.py`

### 4) `requirements.txt`
- **설명**: 현재 파이썬 가상환경에 설치된 전체 패키지 목록 및 버전 정보를 기록한 환경 정보 파일.
- **주요 기능 및 동작**:
  - 개발 환경 재현성 보장 (`rich`, `ipykernel` 등 필요한 패키지 명시)
- **생성 및 설치 방법**:
  - 저장: `pip freeze > requirements.txt`
  - 복원 설치: `pip install -r requirements.txt`
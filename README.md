# FastAPI 할일목록 웹 개발

## 사용한 기술
- fastapi: 백엔드
- jinja2: 프론트엔드
- pydantic: 모델 검증
- uvicorn: 서버

## 설명
- FastAPI 애플리케이션을 개발하기 위한 개발환경 구축을 학습(docker, venv, github)
- 기본적인 CRUD 학습
- jinja2 템플릿을 사용한 뷰 생성 방법과 API 응답 렌더링 방법 학습
- 응답 모델, 오류 처리, 상태 코드 학습

## 구조
- 모델: model.py        (게시판 모델)
- 메인: api.py          (초기 url)
- 라우터: todo.py       (CRUD를 구현한 라우터)
- 템플릿: templates     (템플릿 파일들)

## 스크린샷
메인화면
![main](https://github.com/koreanjys/todos/blob/main/screenshot/main.png)


---
입력
![input](https://github.com/koreanjys/todos/blob/main/screenshot/input.png)


***
추가
![add](https://github.com/koreanjys/todos/blob/main/screenshot/add.png)


___
리스트
![list](https://github.com/koreanjys/todos/blob/main/screenshot/list.png)


---
디테일
![detail](https://github.com/koreanjys/todos/blob/main/screenshot/detail.png)
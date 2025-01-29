## Flask를 활용한 To-Do List 프로젝트


### 가상 환경 설정
```zsh
$ python -m venv .venv
$ source .venv/bin/activate
```

### 패키지 설치
```zsh
$ pip install -r requirements.txt
```

### Flask 앱 배포
```zsh
myenv.eba-zpjpw7rh.ap-northeast-2.elasticbeanstalk.com
```

### 디렉토리 구조

```
flask-todo/
│── .venv/            # 가상 환경
│── app.py            # Flask 백엔드 애플리케이션
│── templates/
│   ├── index.html    # 프론트 메인 페이지
│── static/
│   ├── style.css     # 스타일 파일 (선택사항)
│── database.db       # SQLite 데이터베이스 (앱 실행 후 자동 생성)

```
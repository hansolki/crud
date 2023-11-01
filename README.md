# CRUD

## 프로젝트 구조 작성

1. 프로젝트 폴더 생성

2. 프젝트 폴더를 vscode로 열기
    - `gitignore`, `README.md` 만들기

3. django 프로젝트 생성
```
django-admin startproject <pjt-name> .
```

4. 가상환경 설정
```
python -m venv venv
```

5. 가상환경 활성화
```
source venv/bin/activate   
```
6. 가상환경에 django 설치
```
pip install django
```
7. 서버 실행 확인 
```
python manage.py runserver
```
8. 앱 생성
```
django-admin startapp <app-name>
```
9. 앱 등록 => `settings.py`

10. 


## Model 
1. 모델 정의(`models.py`)
    - 모델의 이름은 기본적으로 단수형태

2. 번역본 생성

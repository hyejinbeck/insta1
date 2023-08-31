프로젝트이름 : orange 

APP이름: articles 

# 기본셋팅 
```bash
python -m venv venv
source venv/bin/activate
pip install django
django-admin startproject insta .
django-admin startapp articles
settings.py 의 INSTALLED_APPS 추가 
settings.py 의 TEMPLATES [BASE_DIR/'templates'], 추가 
상위폴더 > templates폴더 생성 > base.html 생성 
.gitignore생성 
README.md생성
```

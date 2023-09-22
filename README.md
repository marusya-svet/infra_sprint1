# KITTYGRAM_PROJECT
Social network for people who love cats. Here you can upload photos of your cats and attach their achievements 

### Run project in dev
```
cd infra_sprint1/backend/
```
- Install and activate virtual environment
```
python3 -m venv venv
source venv/bin/activate
```
- Install dependencies from the file requirements.txt
```
pip install -r requirements.txt
``` 
- In the folder with the file manage.py make migrations
```
python3 manage.py migrate
``` 
- In the same folder run command:
```
python3 manage.py runserver
```

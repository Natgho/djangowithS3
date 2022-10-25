# Using S3 as File storage in Django
## How to use?
1. Install the dependencies
```shell
pip install -r requirements.txt
```
2. Change settings.py these lines;
```python
AWS_ACCESS_KEY_ID = '########'  # don't forget the update
AWS_SECRET_ACCESS_KEY = '#######'  # don't forget the update
AWS_STORAGE_BUCKET_NAME = '######'  # don't forget the update
```
3. Collect your static files and upload to S3:
```shell
python manage.py collectstatic
```
4. Create superuser for testing:
```shell
python manage.py createsuperuser
```
5. Runserver for testing:
```shell
python manage.py runserver
```
Detailed articles are here:  
[Turkish]() | [English]()
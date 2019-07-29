# How to Connect MySQL Database in Django Project

## Tutorial Link - http://studygyaan.com/django/how-to-export-excel-file-with-django

In this tutorial, you will learn how to Export Excel Spreadsheet with Django. You will learn how to do read-write operations on excel sheets. Styling Excel spreadsheet with XLWT Library. And writing to Existing Excel Workbook using XLWT.

### Setup
1. Create a folder and put all the files inside it.
2. Create a virtual environtment - `virtualenv env`
3. Activate VirtualENV - `source env/bin/activate`
4. Run requirements.txt - `pip3 install -r requirements.txt`
5. Run the Application - `python3 manage.py runserver`
6. Go to - http://localhost:8000/

### Change Database Credentials with your Database - `blog/settings.py`

```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'your_database_name', # example - blog_data
        'USER': 'your_mysql_user',
        'PASSWORD': 'your_mysql_password',
        'HOST': 'localhost',
        'PORT': '80',
    }
}
```

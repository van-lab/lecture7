# lecture7
create project:
  django-admin startproject projectname
create app:
  python3 manage.py startapp appname
run app:
  python3 manage.py runserver
migration:
  python3 manage.py makemigrations
  python3 manage.py migrate
  python3 manage.py sqlmigrate flights 0003
shell:
  python3 manage.py shell
  python3 manage.py sqlmigrate flights 0001
admin:
  admin.py
    admin.site.register(Airport)
    admin.site.register(Flight)
  python3 manage.py createsuperuser

1.  create appname/urls.py
2.  project/urls.py
      add app urls folder.modulename format
3.  


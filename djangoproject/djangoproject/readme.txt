
mkdir djangoproject    (for creating new folder)
notepad file_name      (you can edit code file)
dir                    (this shows all file in perticular file)
conda env list         (this cmd will give you list of env youcreated for past project)
///////////////////////////////new django project///////////C:\Windows\System32\djangoproject////////////////////////////////////
conda install python==3.6.9
python -m pip install django
conda create -n django python==3.6.9      (creating env name as django)
call conda.bat activate django
django-admin startproject hello_world

cd hello_world
python manage.py runserver               #this command will give you local http: server
                                          (include path in urls.py file)
python manage.py startapp hello_app           
cd hello_app                              (write html inside hello_app/view)
                                          (edit urls.py)


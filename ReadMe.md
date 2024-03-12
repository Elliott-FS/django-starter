# First Django project! Excited to get started.
# to run file run python3 manage.py runserver in parent mydjangostarter file
# Having some issues, one thing I learned is we need to run Django virtual env from the top level file.
# from Django-starter run "source djangoenv/bin/activate" to acvtivate run deactivate to deactivate. 
# pylance missing modules currently trouble shooting. 
# Noticing when I change interperter to system interperter missing package problem goes away but I
# need to use my django venv for interperter. Researching. 

# Problem Solved! Heres what happened: we didn't have django installed in the right folder. we needed 
# django in the parent folder for the project because the virtual env will be using django modules. Once
# I installed django in django-starter i was able to activate the venv and set the interperter path variable 
# to the djangoenv file with no missing modules. 
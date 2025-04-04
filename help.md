cd DeepFake_Detection
# req python version Python 3.9.12
https://www.python.org/ftp/python/3.9.12/python-3.9.12-amd64.exe

# create virtual env
C:\Users\username\AppData\Local\Programs\Python\Python39\python.exe -m venv env
# active virtual env
env\Scripts\activate
# req installation
pip install -r requirements.txt
# to run the app
python server.py    

# to run the app everytime first switch  to env and then run it

env\Scripts\activate

python server.py
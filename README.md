<<<<<<< HEAD
=======

>>>>>>> 4b365be9377591abbd3c230c4119a21d7f406b27

### Python版本与依赖库：
  * python 3.6 + : https://www.python.org/
  * Django 2.0.7 + : https://www.djangoproject.com/
  * PyMySQL 0.8.0: https://github.com/PyMySQL/PyMySQL
  * pycryptodome 3.7.3：https://github.com/Legrandin/pycryptodome 

#### 提供接口

|接口| URL | 请求方式|
|:---|:---|:---|
|添加发布会接口 | http://127.0.0.1:8000/api/add_event/ | POST |
|查询发布会接口 | http://127.0.0.1:8000/api/get_event_list/ | GET |
|添加嘉宾接口 | http://127.0.0.1:8000/api/add_guest/ | POST |
|查询嘉宾接口 | http://127.0.0.1:8000/api/get_guest_list/ | GET |
|嘉宾签到接口 | http://127.0.0.1:8000/api/user_sign/ | GET |

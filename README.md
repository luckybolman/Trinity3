<p align="center">
  <img src="http://i.imgur.com/k8I15Gh.png" alt="Trinity 3"/>
</p>

[![stability-experimental](https://img.shields.io/badge/stability-experimental-orange.svg)](https://github.com/emersion/stability-badges#experimental)
[![PEP8](https://img.shields.io/badge/code%20style-pep8-orange.svg)](https://www.python.org/dev/peps/pep-0008/)

###### Using least ammount of modules possible
flask, flask-compress, pymysql, passlib

How to setup
-------------------
- Install Python 3+
https://www.python.org/

- Install MySQL Server
https://www.apachefriends.org/index.html

- Configure `config.ini`
- Import `mysqldb.sql` into your database. (default user included tr4-admin:password)

--------------------
Run the command below to install required modules. (pip or pip3)

```sh
$ pip3 install -r requirements.txt
```

Install NPM for frontend (temporary)
```sh
$ cd pub/__trinity__/
$ npm install
$ npm run dev
```
How to run
----------------
#### Local / development environment
```sh
python3 trinity_server.py
```
###### Windows users can simply launch `win_launch.bat`
--------------------

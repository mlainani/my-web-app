# How to run gunicorn

```
fennecfox@sahara:~$ cd flasky/
fennecfox@sahara:~/flasky$ source venv/bin/activate
(venv) fennecfox@sahara:~/flasky$ gunicorn hello:app
[2020-12-01 12:57:08 +0000] [915] [INFO] Starting gunicorn 20.0.4
[2020-12-01 12:57:08 +0000] [915] [INFO] Listening at: http://127.0.0.1:8000 (915)
[2020-12-01 12:57:08 +0000] [915] [INFO] Using worker: sync
[2020-12-01 12:57:08 +0000] [918] [INFO] Booting worker with pid: 918
^C[2020-12-01 12:57:44 +0000] [915] [INFO] Handling signal: int
[2020-12-01 12:57:44 +0000] [918] [INFO] Worker exiting (pid: 918)
[2020-12-01 12:57:45 +0000] [915] [INFO] Shutting down: Master
(venv) fennecfox@sahara:~/flasky$ deactivate
```

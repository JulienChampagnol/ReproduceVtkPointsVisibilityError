## Repro script

```bash
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install pytest pytest-xprocess
$ pip install requirements.txt
$ pip install -e .
$ pytest
```


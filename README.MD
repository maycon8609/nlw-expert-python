### Create virtualization
```bash
  python3 -m venv .venv
```

### Access virtualization
```bash
  . .venv/bin/activate
```

### Update requirements.txt
```bash
  .venv/bin/pip3 freeze > requirements.txt
```

### Start pre-commit
```bash
  pre-commit install
```

### Install dependencies
```bash
  pip install -r requirements.txt -t <path-to-the-lib-directory>
```

### Run project
```bash
  python3 run_raw.py
```
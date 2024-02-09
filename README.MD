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
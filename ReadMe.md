## ⚡FastAPI⚡


- `python -m venv venv`
- `venv\Scripts\active`

---

1. `pip install fastapi[all]`
2. create `main.py`
3. create `__init__.py`
4. main.py

```py
from fastapi import FastAPI

app = FastAPI()

@app.get('/')
async def welcome():
    return {'message': 'Hello World'}
```

5. `uvicorn main:app --reload` || `uvicorn main:app --host 0.0.0.0 --port 8080`

---

- `pydantic` kullanılabilir


<br>

---

- Ubuntu ortamı için python sanal ortam kurma

1. `sudo apt install python3-venv`
2. `python3 -m venv venv`
3. `source venv/bin/active`

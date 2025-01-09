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

5. `uvicorn main:app --reload`

<br>

- `pydantic` kullanılabilir

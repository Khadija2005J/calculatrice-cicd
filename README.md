# Calculatrice CI/CD

**A small Python calculator used to practice automated testing and continuous integration.**

## What it does

`calculatrice.py` provides four functions:

| Function | Operation |
|----------|-----------|
| `addition(a, b)` | a + b |
| `soustraction(a, b)` | a − b |
| `multiplication(a, b)` | a × b |
| `division(a, b)` | a ÷ b — raises `ValueError` when dividing by zero |

Each function is covered by a unit test in `test_calculatrice.py`, including the division-by-zero case.

## Run the tests

```bash
git clone https://github.com/Khadija2005J/calculatrice-cicd.git
cd calculatrice-cicd
python -m venv venv
# Windows: venv\Scripts\activate   |   macOS/Linux: source venv/bin/activate
pip install -r requirements.txt
pytest -v
```

## Tech stack

Python, pytest.

## Author

Khadija Alaoui Mrani – [GitHub](https://github.com/Khadija2005J)

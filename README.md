# github-eyad-test
github-actions-testing/
├── .github/
│   └── workflows/
│       └── test.yml
├── main.py
def add(a, b):
    return a + b

└── test_main.py
from main import add

def test_add():
    assert add(2, 3) == 5

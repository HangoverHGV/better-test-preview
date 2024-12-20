# Better Test Preview

Better Test Preview is a FastAPI application that allows you to run and preview test results in a web interface.

## Installation

To install the package, use:

```sh
pip install better-test-preview
```

## Usage

Import packages:

```python
from fastapi import FastAPI
from better_test_preview.better_test_preview import main
    
app = FastAPI()

app.include_router(main.router, prefix="/tests")
```

And you are done! Now you can run your tests and see the results in the web interface.
The tests will be automatically detected if you want to run them separately.


The source code is available on [GitHub](https://github.com/HangoverHGV/better-test-preview).


![img.png](img.png)



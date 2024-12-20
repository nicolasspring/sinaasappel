# sinaasappel
Useful utils

<p align="center">
<a href="https://github.com/nicolasspring/sinaasappel/actions?query=event%3Apush+branch%3Amain+workflow%3ACI" target="_blank">
    <img src="https://img.shields.io/github/actions/workflow/status/nicolasspring/sinaasappel/ci.yml?branch=main&logo=github&label=CI" alt="CI status">
</a>
<a href="https://github.com/nicolasspring/sinaasappel/actions/workflows/test.yml?query=branch%3Amain+" target="_blank">
    <img src="https://img.shields.io/github/actions/workflow/status/nicolasspring/sinaasappel/test.yml?branch=main&logo=github&label=Tests" alt="Tests">
</a>
<a href="https://coverage-badge.samuelcolvin.workers.dev/redirect/nicolasspring/sinaasappel" target="_blank">
    <img src="https://coverage-badge.samuelcolvin.workers.dev/nicolasspring/sinaasappel.svg" alt="Coverage">
</a>
<a href="https://pypi.org/project/sinaasappel" target="_blank">
    <img src="https://img.shields.io/pypi/v/sinaasappel?&label=pypi%20package" alt="Package version">
</a>
<a href="https://pypi.org/project/sinaasappel" target="_blank">
    <img src="https://img.shields.io/pypi/pyversions/sinaasappel" alt="Supported Python versions">
</a>
</p>

## Recursive sum

Use the following commands to calculate the unweighted sum of a nested list of ints:

```python
from sinaasappel import recursive_sum

list_sum = recursive_sum([1, 2, [3, [4]]])
print(list_sum)  # prints 10
```


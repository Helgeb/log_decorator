# log_decorator

Python logging decorator

Based on a gist from https://gist.github.com/bradmontgomery

## Install

```bash
pip install log_decorator
```

## Use

```python
@timed()
def fast_function(run):
    time.sleep(run * 0.0001)


@timed(False)
def untimed():
    time.sleep(0.001)


```

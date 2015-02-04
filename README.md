# Rullet
Just a script selecting an item from an array randomly

# Usage
```
$ pip install rullet
$ rullet foo bar baz
> bar
```
```python
from rullet import rullet
args = ['foo', 'bar', 'baz']
result = rullet.run(args)
print result

> bar
```

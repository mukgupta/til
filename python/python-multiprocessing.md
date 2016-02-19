# Multiprocessing in python

You can divide a simple task into multiple processes using the Pool object.

```python

from multiprocessing import Pool

def f(x):
    return x*x

if __name__ == '__main__':
    p = Pool(5)
    print(p.map(f, [1, 2, 3]))

```

The Pool object distributes the task into multiple processes thus allowing us to leverage multiple processors on a given machine.

[source](https://docs.python.org/2/library/multiprocessing.html)


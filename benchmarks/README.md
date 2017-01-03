# how to setup virtualenv

```
$ virtualenv myenv2.7 --system-site-packages --python=python2.7
$ pip install -r requirements.txt
$ pip install scales
$ pip install twisted
$ python benchmarks/future_full_throttle.py --help
```

# perf test
http://docs.datastax.com/en/drivers/python/2.6/performance.html

libev is not available
```
$ brew install libev
$ pip install -e .
```

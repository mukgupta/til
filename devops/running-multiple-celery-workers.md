# Running multiple workers in celery

You can run multiple workers on single host using

```bash
$ python manage.py celeryd start w1,w2 -Q:w1 queue1 -Q:w2 queue2

```

where
w1,w1 are two workers
queue1,queue2 are queues associated with w1 and w2 respectively 

[source] (https://celery.readthedocs.org/en/3.0/reference/celery.bin.celeryd_multi.html)


# pyfomatter
remove comment , docs 

```python
#NOTE HERE
#NOTE HERE
print('hello _world') #HELLO_WORLD
"""
__doc__	test
"""

def hello():
	"""a = 5"""
	print(234)
hello()
#END
```

to

```
print('hello _world')

def hello():
    print(234)
hello()
```

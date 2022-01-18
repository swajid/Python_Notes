# Python_Notes

```
Format:
# Headline
* links
Examples

Audience: new students to Python, a reference guide

```

# asterisks
* [Asterisks in Python: what they are and how to use them](https://treyhunner.com/2018/10/asterisks-in-python-what-they-are-and-how-to-use-them/)

# fizzbuzz
<details>
  
```
for fizzbuzz in range(50):
    if fizzbuzz % 3 == 0 and fizzbuzz % 5 == 0:
        print("FizzBuzz")
        continue
    elif fizzbuzz % 3 == 0:
        print("Fizz")
        continue
    elif fizzbuzz % 5 == 0:
        print("Buzz")
        continue
    print(fizzbuzz)
```
  
</details>

# Comprehensions
## list
```
>>> list_o_nums = [x for x in range(100)]
>>> sys.getsizeof(list_o_nums)
920
```
## generator
```
>>> gen_o_nums = (x for x in range(100))
<generator object <genexpr> at 0x7fb672d930d0>
>>> sys.getsizeof(gen_o_nums)
128
```
# list and tuple operations and special syntax

iterating through a list of tuples
```
for name,phone in listOfTuples:
  if name == a_name:
    return phone

listOfTuples = [
  ("name1", "555-555-5555"),
  ("name2", "666-666-6666"),
]
```

# underscores

# `__init__`
initializer; initializes class instance (self) so that it's ready for use

```
class Vector:
  def __init__(self,x,y):
    self.x = x
    self.y = y
    
>>> v
<__main__.Vector at 0x7fb66e8cca10>
>>> v = Vector(4,5)
>>> v.x
4
>>> v.y
5
```


# [zip](https://docs.python.org/3.3/library/functions.html#zip)
takes in multiple sequences and combines them into tuples
```
>>> keys = ["foobar", "barzz", "ba!"]
>>> dict(zip(keys, map(len,keys)))
{'foobar': 6, 'barzz': 5, 'ba!': 3}
```

# References
[Serious Python](https://nostarch.com/seriouspython)

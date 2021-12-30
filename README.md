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

# underscores

# [zip](https://docs.python.org/3.3/library/functions.html#zip)
takes in multiple sequences and combines them into tuples
```
>>> keys = ["foobar", "barzz", "ba!"]
>>> dict(zip(keys, map(len,keys)))
{'foobar': 6, 'barzz': 5, 'ba!': 3}
```

# References
[Serious Python](https://nostarch.com/seriouspython)

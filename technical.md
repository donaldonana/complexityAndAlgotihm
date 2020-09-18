# Technical  questions


Categories:

* Data structure
* sort
* NP-Probleme


## Data structure

* ABR

<img src="img/schema.png" />


Write the python code of each preocupation :

**1)** Structure permettant de definir un ABR

```python
class arbre:
    """docstring for arbre"""
    def __init__(self, arg):
        self.left = None
        self.right = None
        self.parent = None
        self.arg = arg

    # The next fonction will going to write

    def insertion(self):
        pass

    def infixPrint(self):
        pass

    def prefixPrint(self):
        pass
         .
         .
         .
         .
         .
         .
         .
    # And more again     
```

<br/>


**2)** insert methode

```python
def insert(self, val):
        if self.arg:
            if self.arg > val:
                if self.left is None:
                    self.left = arbre(val)
                else:
                    self.left.insert(val)
            elif self.arg < val:
                if self.right is None:
                    self.right = arbre(val)
                else:
                    self.right.insert(val)
        else:
            self.arg = val
```

<br/>


<br/>

**3)** Empty check methode

```python

```

<br/>

<br/>

**4)** Infix Print

```python

```

<br/>


<br/>

**5)** Prefix Print

```python

```

<br/>

<br/>

**6)** Postfix Print

```python

```

<br/>

<br/>

**7)** Search methode

```python

```

<br/>


<br/>

**8)** Maximum methode

```python

```
<br/>



<br/>

**9)** Minimum methode

```python

```
<br/>


<br/>

**10)** Successor methode

```python

```

<br/>

<br/>

**11)** Predecessor methode

```python

```

<br/>

<br/>

**12)** Delete methode

```python

```

<br/>

* ABR








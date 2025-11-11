This forks is a quick and dirty implementation of the 'two pixel' splitting criterion in the Tree's.

To create a tree with the twoPixel test instead of the standard axis-aligned, put the parameter splitter='twoPixel', in a DecisionTreeClassifier for example (works also for other trees).


```python
# Example for DecisionTreeClassifier:
DecisionTreeClassifier(splitter='twoPixel', ...)
```

This comes with absolutely NO guarantee : the fix is very shallow, and it will NOT work for : Sparse data matrixes and missing values.

Use this only as a quick fix.



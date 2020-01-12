+++
categories = "Python"
date = 2020-01-11T14:00:00Z
description = "If you wanna use Python as a Data Scientist, you have to know Python Data Structures - like lists, tuples and dictionaries!"
tags = ["Data structure", "Python"]
thumbnail = ""
title = "Data Structure Basics"

+++
Lists
“A list is a data structure that holds an ordered collection of items i.e. you can store a sequence of items in a list.” - A Byte Of Python

Lists are mutable.

# Create a list of countries, then print the results
```python
allies = ['USA','UK','France','New Zealand',
          'Australia','Canada','Poland']; allies
['USA', 'UK', 'France', 'New Zealand', 'Australia', 'Canada', 'Poland']
```

# Print the length of the list
```python
len(allies)

Output:
7
```

# Add an item to the list, then print the results
```python
allies.append('China'); allies

Output:
['USA',
 'UK',
 'France',
 'New Zealand',
 'Australia',
 'Canada',
 'Poland',
 'China']
 ```
 
# Sort list, then print the results
```python
allies.sort(); allies

Output:
['Australia',
 'Canada',
 'China',
 'France',
 'New Zealand',
 'Poland',
 'UK',
 'USA']
```

# Reverse sort list, then print the results
```python
allies.reverse(); allies

Output:
['USA',
 'UK',
 'Poland',
 'New Zealand',
 'France',
 'China',
 'Canada',
 'Australia']
```
# View the first item of the list
```python

allies[0]

Output:
'USA'
```
# View the last item of the list
```python
allies[-1]

Output:
'Australia'
```

# Delete the item in the list
```python
del allies[0]; allies

Output:
['UK', 'Poland', 'New Zealand', 'France', 'China', 'Canada', 'Australia']
```

# Add a numeric value to a list of strings
```python
allies.append(3442); allies

Output:
['UK', 'Poland', 'New Zealand', 'France', 'China', 'Canada', 'Australia', 3442]
```

+++
authors = []
date = 2020-01-11T14:00:00Z
excerpt = ""
hero = ""
timeToRead = 2
title = "Data Structure Basics"

+++
## Lists

“A list is a data structure that holds an ordered collection of items i.e. you can store a sequence of items in a list.” - A Byte Of Python

Lists are mutable.

    # Create a list of countries, then print the results
    allies = ['USA','UK','France','New Zealand',
              'Australia','Canada','Poland']; allies

    ['USA', 'UK', 'France', 'New Zealand', 'Australia', 'Canada', 'Poland']

    # Print the length of the list
    len(allies)

    7

    # Add an item to the list, then print the results
    allies.append('China'); allies

    ['USA',
     'UK',
     'France',
     'New Zealand',
     'Australia',
     'Canada',
     'Poland',
     'China']

    # Sort list, then print the results
    allies.sort(); allies

    ['Australia',
     'Canada',
     'China',
     'France',
     'New Zealand',
     'Poland',
     'UK',
     'USA']

    # Reverse sort list, then print the results
    allies.reverse(); allies

    ['USA',
     'UK',
     'Poland',
     'New Zealand',
     'France',
     'China',
     'Canada',
     'Australia']

    # View the first item of the list
    allies[0]

    'USA'

    # View the last item of the list
    allies[-1]

    'Australia'

    # Delete the item in the list
    del allies[0]; allies

    ['UK', 'Poland', 'New Zealand', 'France', 'China', 'Canada', 'Australia']

    # Add a numeric value to a list of strings
    allies.append(3442); allies

    ['UK', 'Poland', 'New Zealand', 'France', 'China', 'Canada', 'Australia', 3442]
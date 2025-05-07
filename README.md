# mapping_wines
Coursera Lesson 2: Mapping Data to Python

This project loads a csv file using Pandas and retrieves information about Spanish wines, grouping them by region.

The filtered data is then converted into a list of dictionaries and saved as a json file.

Missing values NaN are removed using numpy, since the json.dump() function cannot serialize them properly.

# Automated Business Intelligence (ABI)
ABI stands for Automated Business Intelligence.  This project is a fairly ambitious project to provide business intelligence entity classification and reporting using deep learning.

In the end, all understandable data is just a set of patterns that we have trained our brains to recognize.  Any machine should be able to classify and understand the same through machine learning and deep learning techniques.

The goal of this project is to create a platform whereby users can request reports from the system without the need for manual IT driven architecture or even manually created reports.

## Motivation
The business intelligence landscape is filled with tools and products that attempt to pull data from various data sources and display them in a meaningful manner.

Some products have very little structure, making it almost impossible to have a "single source of the truth."  They gain flexibility, but have a high expense of creating vast report libraries all with conflicting information.  It becomes difficult for business leaders to know which report is correct.  Lack of ownership, consistency, and scalability become problems for these flexible "quick analytics" platforms.

Other products have heavy underlying architecture that make them very powerful tools.  These tools can provide a lot of re-use and maintain data integrity better.  However, they end up creating an IT bottleneck where users need to wait for the business intelligence, data warehouse, or other teams to prepare the data so that they can use it.

Neither solution is ideal.  Either a business has flexibility and is more agile has trouble with a single source of the truth, or they have more reusable and accurate data, but aren't as flexible.

This projects goal is to leverage machine learning learn how existing reports are built and deep learning to classify and categorize data automatically.  By combining the two, we hope to create a system that can plug into existing database systems, and after a short learning / training period, give business users the ability to ask for reports.

Imagine spinning up an ABI project, pointing it at a database, and after 1 day of "learning," asking the system.

"Please show me a line chart of sales over the past 5 years."

Sounds impossible... and maybe it is.  But this project is an attempt to do just that!


## Code style
- All indentation must be using 4 spaces, not tabs.
- Hanging indents should align to their parent arguments
```python
def method (param1,
            param2,
            param3)
```
- The opening brace on a list of arguments should be on the same line as the declaration and the closing brace should be on a new line
```python
my_list[
    one,two,three
]
```
- binary operators should be on the same line as their operands
	- #### NO
	```python
	value = (a +
	         b +
	         c +
	         d)
	```
	- #### YES
	```python
	value = (a
	         + b
	         + c
	         + d)
	```
- Public variables and methods should begin with a capital letter and follow PascalCase
```python
Fruit
FruitBasket
```
- Private variables and methods should begin with an underscore (_) and follow camelCase
```python
_fruit
_fruitBasket
```
- Internal function variables should begin with a lower case letter and follow camelCase
```python
fruit
fruitBasket
```
- Surround top level function and class definitions with two blank lines
- Method definitions inside a class should be surrounded by a single blank line

- All imports should be on separate lines unless importing several classes from the same library
	- #### NO
	```python
	import sys, os, requests
	```
	-	#### YES
	```python
	import sys
	import os
	import requests
	from x import Y,Z
	```
- use single quotes for strings
- avoid trailing white space
- use trailing commas in lists

 

## Tech/framework used

<b>Built with</b>
- Python
- Pandas
- TensorFlow
- Numpy

## Features
This is the first AI business intelligence product and project of this sort that I know of.

## Installation
TBD

## How to use?
TBD

## Contribute
If you would like to contribute, please contact me at jason@smithstrategy.com

## Credits


## License
This project is licensed under the MIT license - see the [LICENSE.md](License.md) file for details.

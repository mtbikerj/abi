# Automated Business Intelligence (ABI)
ABI stands for Automated Business Intelligence.  This project as a fairly ambitious project to provide business intelligence classification and reporting using deep learning.

In the end, all understandable data is just a set of patterns that any machine should be able to classify and understand through machine learning and deep learning techniques.

The goal of this project is to create a platform whereby users can request reports from the system without the need for manual IT driven architecture or even manually created reports.

## Motivation
The business intelligence landscape is filled with tools and products that attempt to pull data from various sources and display them in a meaningful manner.

Some products have very structure, making it almost impossible to have a "single source of the truth."  They sacrifice flexibility at the expense of creating vast report libraries all with conflicting information.  Lack of ownership, consistency, and scalability becomes a problem.

Other products have heavy underlying architecture.  These tools can provide a lot of re-use and maintain data integrity better, but they end up creating an IT bottleneck where users need to wait for the business intelligence, data warehouse, or other teams to prepare the data so that they can use it.

Neither solution is ideal.  Either a business has flexibility and is more agile, or they have more reusable and accurate data, but aren't as flexible.

This projects goal is to leverage machine learning to learn how existing reports are built and deep learning to classify and categorize data automatically.

Imagine spinning up an ABI project, pointing it at a database, and after 1 day of "learning," asking the system.

"Please show me a line chart of sales over the past 5 years."

Sounds impossible... and maybe it is.  But this project is an attempt to do just that!


## Code style
- All indentation must be using 4 spaces, no tabs.
- Hanging indents should align to their parent arguments
    def method(param1
               param2
               param3)

- The opening brace on a list of arguments should be on the same line as the declaration
- The closing brace should be on a new line
    my_list[
        1,2,3,
        4,5,6
    ]
- binary operators should be on the same line as their operands
#NO
value = (a +
        b +
        c +
        d)

#YES
value = (a
         + b
         + c
         + d)

- Public variables and methods should begin with a capital letter and follow PascalCase
    Fruit
    FruitBasket
- Private variables and methods should begin with an underscore (_) and follow camelCase
    _fruit
    _fruitBasket
- Internal function variables should begin with a lower case letter and follow camelCase
    fruit
    fruitBasket

- Surround top level function and class definitions with two blank lines
- Method definitions inside a class should be surrounded by a single blank line

- All imports should be on separate lines unless importing several classes from the same library
# NO
import sys, os, requests

# YES
import sys
import os
import requests
from x import Y, Z

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
This is the first AI business intelligence product that I know of.

## Installation
TBD

## How to use?
TBD

## Contribute
If you would like to contribute, please contact me at jason@smithstrategy.com

## Credits


## License
This project is licensed under the MIT license - see the [LICENSE.md](License.md) file for details.
# MySql-Python-Import-Script
Python script for importing data from .csv, .xls, or .xlsx to MySql database.

## Setup

**Requirements**
 
* [python 2+](https://www.python.org)
* [virtualenv](https://virtualenv.pypa.io/en/latest/)
* [mysql-connector-python](https://dev.mysql.com/doc/connector-python/en/connector-python-introduction.html)
* [xlrd](https://xlrd.readthedocs.io/en/latest/)

**Setup**

    $ virtualenv <envname> -p python3
    $ source <envname>/bin/activate
    $ pip install -r requirements.txt

**Running script**

    $ python import.py -t spreadsheet -d data/users.xlsx -s source
    
###### arguments
    
_-t (type)_
    
spreadsheet, csv

_-d (dataset)_

Path to dataset

_-s (sheet name)_

Used if the dataset type in use is a spreadsheet
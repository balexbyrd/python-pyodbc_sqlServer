# python- pyodbc & SQL Server 
A test script to connect and send data from a python script to a SQL Server database.

## Installation

1. You must install pyodbc for the flavor of python you have. <https://github.com/mkleehammer/pyodbc>

> pip install pydobc

2. In SQL Server, set up a database called 'TestPython'.
3. Set up a table in the database called 'testtable' with columns 'id' (int) and 'name' varchar(4).
4. Set up a user with name 'Python' and password 'asdf' that has read/write access to the database.
	
## Usage

In a CLI, cd into the project folder where pydobctest.py file resides and run the code below. Check the testtable to see if the data was correctly sent to the database table.

> python pydobctest.py

## License

MIT

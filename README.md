# ANNA
ANNA seeks to transform natural language questions to SQL, allowing individuals to run unstructured queries against databases.

## Start
```sh
$ pip install -r requirements.txt
$ python nl2sql.py download
$ python nl2sql.py setup
$ python nl2sql.py run
```
### Run

You will be prompted to enter a statement which will be turned into SQL and executed.

Example Run:
```sh
$ python nl2sql.py run

  Type 'exit' to quit

  How can I help you?

  >: How many sections are located in Rhode Island in Spring 2017?

  +------------+
  | COUNT(*)   |
  +------------+
  |   9     |
  +------------+

   What else would you like to know?

   >:
```
### Still needs work on Corpus generator and Node generator

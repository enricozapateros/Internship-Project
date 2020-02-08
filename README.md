# The DrugLi Project

Python code to create database of protein-ligand
interactions with data derived from the Protein Data Bank called DrugLi.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites
Retrieve the structural data from PDBBind: http://www.pdbbind.org.cn/
Python (3.7)
Conda(4.7.12)
Numpy(1.16.4)
RDKit (Q3 2019)

End with an example of getting some data out of the system or using it for a little demo

## Running the tests
To create a dataset 

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment
To create the database it is neccesary to run the scripts in the following steps:
1. Run the SQL script to create the tables for the database.
2. Run the DruglikeFiltering.py script to create a druglike dataset from the structural data obtained from the PDBBind database.
3. Run the DatabasePopulator.py script to fill the tables in the database with data from the druglike dataset.
4. Run the PostgresTester.py script to retrieve information about the interactions from the database.

## Authors
* **Rick J Schoenmaker**




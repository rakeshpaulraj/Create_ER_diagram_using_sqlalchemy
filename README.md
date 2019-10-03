## Create ER diagram using sqlalchemy

### Scope of the Project:
This project is to illustrate the steps needed to generate an ER diagram for a given data model using python library sqlalchemy


### Packages requirements

* #### Install sqlalchemy

  SQLAlchemy is the Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL. SQLAlchemy provides a full suite of well known enterprise-level persistence patterns, designed for efficient and high-performing database access, adapted into a simple and Pythonic domain language.
  
  `pip install SQLAlchemy`


* #### Install sqlalchemy_schemadisplay
  This package turns SQLAlchemy DB Model into a graph.
  
  `pip install sqlalchemy_schemadisplay`


* #### Install Graphviz

  Graphviz is an open source graph visualization software. Graph visualization is a way of representing structural information as diagrams of abstract graphs and networks.

  `pip install pip install graphviz` or `conda install -c anaconda graphviz`
 
 
 * #### Install pydot
  * is an interface to Graphviz
  * can parse and dump into the DOT language used by GraphViz,
  * is written in pure Python,
  * and networkx can convert its graphs to pydot.   
  
  
  `pip install pydot`
 
  ### Steps
  * Import the packages
  * create metadata instance
  * Frame the DDL/metadata for each table
  * Create the pydot graph instance by passing format attributes
  * write into image file
![alt tag](http://spirtfire.com/res/img/knot.png)

knot
====

A graph computing engine on top of mongoDB

Background
----------
MongoDB provides main stream, reliable data storage, but it is not easy to run linked data analysis on top of it directly. Graph DBs (such as neo4j, titan) or ontology repository (such as protege) are good at analysis but not designed for serve large scale application. 

What is Knot
------------

Knot is an effort to combine both merits and create a async connector between two data platforms. 
A graph data platform who can read/write standard graph such as json-ld and GraphML http://graphml.graphdrawing.org into Mongo and translate change in Mongo into vertices and edges into the Graph DB -- Run complexity graph analysis on graph db directly and keep persistent on MangoDB.

Goal:
  * Following paths of graph in conventional data storage (MangoDB)
  * Less memory trace
  * Standard query interface (Gremlin REPL)
  * An extentable graph algorithm set

How does Knot work
 * TBD
Relevant component
 * TBD
  

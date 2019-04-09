# Overview
Mostly home-grown code, but uses the Apache Jena library for RDF-related work.

# GraphConnection
An abstraction for a node's connection to others. Includes the RDF concept of subject, predicate and object.

# GraphCreator
Takes the Jena RDF graph and converts it into a graph that is easier and faster to work with in Java.

# GraphNode
A wrapper for Jena's Node class.

# MainEntry
Where the user specifies the path for the ontology file, how many walks to perform, the depth of the walk for each node,
how many nodes to walk, etc. 

# RDFLoader
Loads in the specified ontology file and creates a Jena dataset to be worked with.

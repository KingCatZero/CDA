+-----------+
| Attribute |
+-----------+

represents: an expression in the model



+--------+
| Entity |
+--------+
   
represents: a table in the model



+-----------+
| Hierarchy |
+-----------+

represents: a sequence of dimensions where each attribute is the child of the attribute to its left



+---------+
| Measure |
+---------+
 
represents: a measure (a function applied to an expression) in the model

use: to allow the query engine to know how to represent the expression when aggregated



+--------------+
| Relationship |
+--------------+
   
represents: a link between entities



+-----------+
| DataModel |
+-----------+
 
represents: the collection of the above objects
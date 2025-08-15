+-----------+
| Aggregate |
+-----------+

represents: a column that is the aggregated version of another column along with the function against which it's aggregated
            (e.g. QuantitySum is SUM(Quantity))

use: to allow the query engine to link a column (to be aggregated) to it's aggregated versions



+--------+
| Column |
+--------+
 
represents: a column of a table (e.g. OrderId)



+------+
| Link |
+------+
 
represents: how two tables are joined (e.g. OrderLine <--> Order using OrderId)



+-------+
| Table |
+-------+
   
represents: a table (e.g. Orders)



+---------+
| Dataset |
+---------+
   
represents: the collection of the above objects
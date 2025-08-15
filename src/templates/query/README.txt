+-------------------------+
| Append / Exists / Merge |
+-------------------------+

represents: the joining of subqueries (e.g. T1 LEFT JOIN T2)



+----------+
| Subquery |
+----------+
 
represents: a SQL subquery along with the pointers to other subqueries to which this one is joined
            (e.g. CTE1)



+-------+
| Query |
+-------+
   
represents: the collection of all subqueries (nodes) that constitute the whole query (tree)



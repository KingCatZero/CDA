+-------------+
| Expresssion |
+-------------+

form: <term_1> <term_2> ... <term_n>

    where each <term> is one of
        - a literal (string or number)
        - a mathematical operator (+, -, /, *, etc)
        - a function (from a predefined list of options)
        - a column (from the list of available columns in the database)

use: in-place of standalone columns



+-----------+
| Predicate |
+-----------+
 
form: <expression> <operator> <expression>

    where <operator> is one of the predefined list of options (e.g. =, in, etc)



+--------+
| Window |
+--------+
   
represents: OVER (PARTITION BY <columns> ORDER BY <columns>)

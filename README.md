#OLAP Operations.
**Rollup**-summarizes data at a higher level by reducing dimensions.
**Drilldown**-shows more details at a lower lever by breaking down data into smaller levels of detail.
**Slice**-selects one value of a dimension by extracting a single subset of the cube and analyzing the rest.
**Dice**-selects multiple dimensions on a cube and applys filters to the subcubes for analysis.

- ROLAP - builds OLAP cubes by running SQL queries on relational tables to store and manage warehose data.
In the figure generated, it indicated a downward trend in the average salary for department 1 to 3.
  
- MOLAP stores data in a multidimensional cube structure by using array-based data structures and aggregated data.
Here, we reveal the salary pattern distribution across the departments in reference to the age,
hoeing a concentration in the older ages.
  
- HOLAP combines the strengths of ROLAP and MOLAP by storing detailed data in a relational database(ROLAP)
while storing aggregated data in multidimensional cubes(MOLAP).
While, HOLAP demonstrates the efficiency of combining both ROLAP to store detailed data in relational databases
and MOLAP by storing summarized aggregated data into multidimensional cubes,for instance, salary by departments.  

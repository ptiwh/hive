# hive

Set command for recursive folder operation on hive table 
set hive.mapred.supports.subdirectories=true;
set mapred.input.dir.recursive=true;

Explode opre

Lateral View :- A lateral view first applies the UDTF to each row of base table and then joins resulting output rows to the input rows to form a virtual table having the supplied table alias.
syntax
lateralView: LATERAL VIEW udtf(expression) tableAlias AS columnAlias (',' columnAlias)*
fromClause: FROM baseTable (lateralView)*


Beeline Execution of Hive for writing data into a text file using hive queries 

beeline -u "jdbc:hive2://master:10000/;principal=hive/master@DOMAIN.NET" 
        --incremental=true 
        --showHeader=true  
        --verbose =false  
        --outputformat=dsv  
        --delimiterForDSV="~"  
        -f /home/userfoldername/testquery.hql>file_correspond99.txt

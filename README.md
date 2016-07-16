# world country city region db sql for postgresql

This is a copy from postgresql

https://code.google.com/p/worlddb/

It contains 246 countries, 4156 regions and 101.907 cities.

First, 

git clone 

Second, 

su - postgres

Then you can

psql -d tableName -f path/worlddb/city.sql;
psql -d tableName -f path/worlddb/country.sql;
psql -d tableName -f path/worlddb/region.sql;

hope i can help you : )

# tap-mssql-to-target-cassandra

A [Singer.io](https://singer.io) target for [Apache Cassandra](http://cassandra.apache.org/),

## Usage
- In meltano project add this project 
- In side your meltano.yaml 
- Exclude schema ignore schemas & Exclude tables ignore tables
```
exclude_schemas:
- one
- two
exclude_tables:
- one_table1
- two_table2
```
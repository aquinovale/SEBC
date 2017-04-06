# George
[root@ip-10-159-126-189 ~]# kinit george
Password for george@HADOOP.LOCAL: 
[root@ip-10-159-126-189 ~]# beeline -u 'jdbc:hive2://10.159.126.189:10000/default;principal=hive/ip-10-159-126-189.ec2.internal@HADOOP.LOCAL'
scan complete in 3ms
Connecting to jdbc:hive2://10.159.126.189:10000/default;principal=hive/ip-10-159-126-189.ec2.internal@HADOOP.LOCAL
Connected to: Apache Hive (version 1.1.0-cdh5.10.1)
Driver: Hive JDBC (version 1.1.0-cdh5.10.1)
Transaction isolation: TRANSACTION_REPEATABLE_READ
Beeline version 1.1.0-cdh5.10.1 by Apache Hive
0: jdbc:hive2://10.159.126.189:10000/default> show tables;
INFO  : Compiling command(queryId=hive_20170406152828_bdbff1a8-47e2-4d9d-ba12-4dff1e9cdf51): show tables
INFO  : Semantic Analysis Completed
INFO  : Returning Hive schema: Schema(fieldSchemas:[FieldSchema(name:tab_name, type:string, comment:from deserializer)], properties:null)
INFO  : Completed compiling command(queryId=hive_20170406152828_bdbff1a8-47e2-4d9d-ba12-4dff1e9cdf51); Time taken: 0.056 seconds
INFO  : Executing command(queryId=hive_20170406152828_bdbff1a8-47e2-4d9d-ba12-4dff1e9cdf51): show tables
INFO  : Starting task [Stage-0:DDL] in serial mode
INFO  : Completed executing command(queryId=hive_20170406152828_bdbff1a8-47e2-4d9d-ba12-4dff1e9cdf51); Time taken: 0.123 seconds
INFO  : OK
+-----------+--+
| tab_name  |
+-----------+--+
| teste     |
+-----------+--+
1 row selected (0.277 seconds)
0: jdbc:hive2://10.159.126.189:10000/default> [root@ip-10-159-126-189 ~]# 
[root@ip-10-159-126-189 ~]# kdestroy 

# Ferdinand - I don't create table sample_07
[root@ip-10-159-126-189 ~]# kinit ferdinand
Password for ferdinand@HADOOP.LOCAL: 
[root@ip-10-159-126-189 ~]# beeline -u 'jdbc:hive2://10.159.126.189:10000/default;principal=hive/ip-10-159-126-189.ec2.internal@HADOOP.LOCAL'
scan complete in 2ms
Connecting to jdbc:hive2://10.159.126.189:10000/default;principal=hive/ip-10-159-126-189.ec2.internal@HADOOP.LOCAL
Connected to: Apache Hive (version 1.1.0-cdh5.10.1)
Driver: Hive JDBC (version 1.1.0-cdh5.10.1)
Transaction isolation: TRANSACTION_REPEATABLE_READ
Beeline version 1.1.0-cdh5.10.1 by Apache Hive
0: jdbc:hive2://10.159.126.189:10000/default> show tables;
INFO  : Compiling command(queryId=hive_20170406152929_e3d6f5cc-8962-403d-86ac-c0e8b4b08b2b): show tables
INFO  : Semantic Analysis Completed
INFO  : Returning Hive schema: Schema(fieldSchemas:[FieldSchema(name:tab_name, type:string, comment:from deserializer)], properties:null)
INFO  : Completed compiling command(queryId=hive_20170406152929_e3d6f5cc-8962-403d-86ac-c0e8b4b08b2b); Time taken: 0.055 seconds
INFO  : Executing command(queryId=hive_20170406152929_e3d6f5cc-8962-403d-86ac-c0e8b4b08b2b): show tables
INFO  : Starting task [Stage-0:DDL] in serial mode
INFO  : Completed executing command(queryId=hive_20170406152929_e3d6f5cc-8962-403d-86ac-c0e8b4b08b2b); Time taken: 0.113 seconds
INFO  : OK
+-----------+--+
| tab_name  |
+-----------+--+
+-----------+--+
No rows selected (0.258 seconds)
0: jdbc:hive2://10.159.126.189:10000/default> 

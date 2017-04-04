[hdfs@ip-10-159-126-189 ~]$ hdfs dfs -put /tmp/SEBC-master.zip /precious

[hdfs@ip-10-159-126-189 ~]$ hdfs dfsadmin -allowSnapshot /precious
Allowing snaphot on /precious succeeded

[hdfs@ip-10-159-126-189 ~]$ hdfs dfs -createSnapshot /precious sebc-hdfs-test
Created snapshot /precious/.snapshot/sebc-hdfs-test

[hdfs@ip-10-159-126-189 ~]$ hdfs dfs -rm  /precious/SEBC-master.zip
17/04/04 20:43:49 INFO fs.TrashPolicyDefault: Moved: 'hdfs://nameservice1/precious/SEBC-master.zip' to trash at: hdfs://nameservice1/user/hdfs/.Trash/Current/precious/SEBC-master.zip


[aquinovale@ip-10-159-126-189 tools]$ time ./YARNtest.sh 
Testing loop started on Tue Apr 4 21:15:39 UTC 2017
-Dmapreduce.job.maps=8 -Dmapreduce.map.memory.mb=512 -Dmapreduce.map.java.opts.max.heap=409



real	1m8.873s
user	0m6.524s
sys	0m0.321s
-Dmapreduce.job.maps=8 -Dmapreduce.job.reduces=1 -Dmapreduce.map.memory.mb=512 -Dmapreduce.map.java.opts.max.heap=409 -Dmapreduce.reduce.memory.mb=512 -Dmapreduce.reduce.java.opts.max.heap=409

real	3m16.293s
user	0m8.653s
sys	0m0.401s
Deleted /user/aquinovale/tg-10GB-8-1-1024
Deleted /user/aquinovale/ts-10GB-8-1-1024
rm: `/user/aquinovale/tg-10GB-8-1-1024': No such file or directory
rm: `/user/aquinovale/ts-10GB-8-1-1024': No such file or directory
./YARNtest.sh: line 48: syntax error near unexpected token `done'
./YARNtest.sh: line 48: `      done'


real	2m39.287s
user	0m8.019s
sys	0m0.416s
Deleted /user/aquinovale/tg-10GB-8-1-512
Deleted /user/aquinovale/ts-10GB-8-1-512
-Dmapreduce.job.maps=8 -Dmapreduce.map.memory.mb=1024 -Dmapreduce.map.java.opts.max.heap=819


real	0m55.829s
user	0m6.201s
sys	0m0.301s
-Dmapreduce.job.maps=8 -Dmapreduce.job.reduces=1 -Dmapreduce.map.memory.mb=1024 -Dmapreduce.map.java.opts.max.heap=819 -Dmapreduce.reduce.memory.mb=1024 -Dmapreduce.reduce.java.opts.max.heap=819

real	2m39.633s
user	0m8.090s
sys	0m0.414s
Deleted /user/aquinovale/tg-10GB-8-1-1024
Deleted /user/aquinovale/ts-10GB-8-1-1024
Testing loop ended on Tue Apr 4 21:23:13 UTC 2017

real	7m34.201s
user	1m34.840s
sys	0m4.725s


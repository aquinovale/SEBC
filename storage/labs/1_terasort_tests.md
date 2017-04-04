# Teragen

time hadoop jar /opt/cloudera/parcels/CDH-5.10.1-1.cdh5.10.1.p0.10/lib/hadoop-mapreduce/hadoop-mapreduce-examples-2.6.0-cdh5.10.1.jar teragen -Ddfs.blocksize=32M -Ddfs.replication=1 -Dmapreduce.job.maps=4 100000000 /user/aquinovale/input-teragen > out.txt 2>&1 


real	0m53.679s
user	0m6.241s
sys	0m0.289s


17/04/04 20:03:11 INFO client.RMProxy: Connecting to ResourceManager at ip-10-230-80-231.ec2.internal/10.230.80.231:8032
17/04/04 20:03:12 INFO terasort.TeraGen: Generating 100000000 using 4
17/04/04 20:03:12 INFO mapreduce.JobSubmitter: number of splits:4
17/04/04 20:03:12 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1491327357242_0009
17/04/04 20:03:13 INFO impl.YarnClientImpl: Submitted application application_1491327357242_0009
17/04/04 20:03:13 INFO mapreduce.Job: The url to track the job: http://ip-10-230-80-231.ec2.internal:8088/proxy/application_1491327357242_0009/
17/04/04 20:03:13 INFO mapreduce.Job: Running job: job_1491327357242_0009
17/04/04 20:03:19 INFO mapreduce.Job: Job job_1491327357242_0009 running in uber mode : false
17/04/04 20:03:19 INFO mapreduce.Job:  map 0% reduce 0%
17/04/04 20:03:37 INFO mapreduce.Job:  map 25% reduce 0%
17/04/04 20:03:38 INFO mapreduce.Job:  map 34% reduce 0%
17/04/04 20:03:43 INFO mapreduce.Job:  map 50% reduce 0%
17/04/04 20:03:44 INFO mapreduce.Job:  map 55% reduce 0%
17/04/04 20:03:49 INFO mapreduce.Job:  map 64% reduce 0%
17/04/04 20:03:50 INFO mapreduce.Job:  map 70% reduce 0%
17/04/04 20:03:55 INFO mapreduce.Job:  map 86% reduce 0%
17/04/04 20:03:56 INFO mapreduce.Job:  map 91% reduce 0%
17/04/04 20:03:59 INFO mapreduce.Job:  map 98% reduce 0%
17/04/04 20:04:01 INFO mapreduce.Job:  map 100% reduce 0%
17/04/04 20:04:02 INFO mapreduce.Job: Job job_1491327357242_0009 completed successfully
17/04/04 20:04:02 INFO mapreduce.Job: Counters: 31
	File System Counters
		FILE: Number of bytes read=0
		FILE: Number of bytes written=499420
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
		HDFS: Number of bytes read=344
		HDFS: Number of bytes written=10000000000
		HDFS: Number of read operations=16
		HDFS: Number of large read operations=0
		HDFS: Number of write operations=8
	Job Counters 
		Launched map tasks=4
		Other local map tasks=4
		Total time spent by all maps in occupied slots (ms)=159142
		Total time spent by all reduces in occupied slots (ms)=0
		Total time spent by all map tasks (ms)=159142
		Total vcore-seconds taken by all map tasks=159142
		Total megabyte-seconds taken by all map tasks=162961408
	Map-Reduce Framework
		Map input records=100000000
		Map output records=100000000
		Input split bytes=344
		Spilled Records=0
		Failed Shuffles=0
		Merged Map outputs=0
		GC time elapsed (ms)=1229
		CPU time spent (ms)=156620
		Physical memory (bytes) snapshot=1040359424
		Virtual memory (bytes) snapshot=6303686656
		Total committed heap usage (bytes)=1045430272
	org.apache.hadoop.examples.terasort.TeraGen$Counters
		CHECKSUM=214760662691937609
	File Input Format Counters 
		Bytes Read=0
	File Output Format Counters 
		Bytes Written=10000000000




# TeraSort

 time hadoop jar /opt/cloudera/parcels/CDH-5.10.1-1.cdh5.10.1.p0.10/lib/hadoop-mapreduce/hadoop-mapreduce-examples-2.6.0-cdh5.10.1.jar terasort /user/aquinovale/input-teragen /user/aquinovale/output-terasort > out.txt 2>&1 


real	7m16.779s
user	0m9.225s
sys	0m0.492s


17/04/04 20:08:54 INFO terasort.TeraSort: starting
17/04/04 20:08:55 INFO input.FileInputFormat: Total input paths to process : 4
Spent 190ms computing base-splits.
Spent 14ms computing TeraScheduler splits.
Computing input splits took 205ms
Sampling 10 splits of 300
Making 6 from 100000 sampled records
Computing parititions took 756ms
Spent 963ms computing partitions.
17/04/04 20:08:56 INFO client.RMProxy: Connecting to ResourceManager at ip-10-230-80-231.ec2.internal/10.230.80.231:8032
17/04/04 20:08:57 INFO mapreduce.JobSubmitter: number of splits:300
17/04/04 20:08:57 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1491327357242_0010
17/04/04 20:08:57 INFO impl.YarnClientImpl: Submitted application application_1491327357242_0010
17/04/04 20:08:57 INFO mapreduce.Job: The url to track the job: http://ip-10-230-80-231.ec2.internal:8088/proxy/application_1491327357242_0010/
17/04/04 20:08:57 INFO mapreduce.Job: Running job: job_1491327357242_0010
17/04/04 20:09:03 INFO mapreduce.Job: Job job_1491327357242_0010 running in uber mode : false
17/04/04 20:09:03 INFO mapreduce.Job:  map 0% reduce 0%
17/04/04 20:09:16 INFO mapreduce.Job:  map 2% reduce 0%
17/04/04 20:09:18 INFO mapreduce.Job:  map 3% reduce 0%
17/04/04 20:09:26 INFO mapreduce.Job:  map 5% reduce 0%
17/04/04 20:09:30 INFO mapreduce.Job:  map 6% reduce 0%
17/04/04 20:09:31 INFO mapreduce.Job:  map 7% reduce 0%
17/04/04 20:09:37 INFO mapreduce.Job:  map 8% reduce 0%
17/04/04 20:09:38 INFO mapreduce.Job:  map 9% reduce 0%
17/04/04 20:09:44 INFO mapreduce.Job:  map 10% reduce 0%
17/04/04 20:09:46 INFO mapreduce.Job:  map 11% reduce 0%
17/04/04 20:09:48 INFO mapreduce.Job:  map 12% reduce 0%
17/04/04 20:09:56 INFO mapreduce.Job:  map 14% reduce 0%
17/04/04 20:09:58 INFO mapreduce.Job:  map 15% reduce 0%
17/04/04 20:10:06 INFO mapreduce.Job:  map 16% reduce 0%
17/04/04 20:10:07 INFO mapreduce.Job:  map 17% reduce 0%
17/04/04 20:10:10 INFO mapreduce.Job:  map 18% reduce 0%
17/04/04 20:10:11 INFO mapreduce.Job:  map 19% reduce 0%
17/04/04 20:10:17 INFO mapreduce.Job:  map 20% reduce 0%
17/04/04 20:10:20 INFO mapreduce.Job:  map 21% reduce 0%
17/04/04 20:10:24 INFO mapreduce.Job:  map 22% reduce 0%
17/04/04 20:10:26 INFO mapreduce.Job:  map 23% reduce 0%
17/04/04 20:10:29 INFO mapreduce.Job:  map 24% reduce 0%
17/04/04 20:10:36 INFO mapreduce.Job:  map 25% reduce 0%
17/04/04 20:10:37 INFO mapreduce.Job:  map 27% reduce 0%
17/04/04 20:10:46 INFO mapreduce.Job:  map 29% reduce 0%
17/04/04 20:10:51 INFO mapreduce.Job:  map 30% reduce 0%
17/04/04 20:10:52 INFO mapreduce.Job:  map 31% reduce 0%
17/04/04 20:10:58 INFO mapreduce.Job:  map 32% reduce 0%
17/04/04 20:11:01 INFO mapreduce.Job:  map 33% reduce 0%
17/04/04 20:11:03 INFO mapreduce.Job:  map 34% reduce 0%
17/04/04 20:11:07 INFO mapreduce.Job:  map 35% reduce 0%
17/04/04 20:11:10 INFO mapreduce.Job:  map 36% reduce 0%
17/04/04 20:11:13 INFO mapreduce.Job:  map 37% reduce 0%
17/04/04 20:11:16 INFO mapreduce.Job:  map 38% reduce 0%
17/04/04 20:11:17 INFO mapreduce.Job:  map 39% reduce 0%
17/04/04 20:11:22 INFO mapreduce.Job:  map 40% reduce 0%
17/04/04 20:11:27 INFO mapreduce.Job:  map 41% reduce 0%
17/04/04 20:11:29 INFO mapreduce.Job:  map 42% reduce 0%
17/04/04 20:11:34 INFO mapreduce.Job:  map 43% reduce 0%
17/04/04 20:11:37 INFO mapreduce.Job:  map 44% reduce 0%
17/04/04 20:11:38 INFO mapreduce.Job:  map 45% reduce 0%
17/04/04 20:11:42 INFO mapreduce.Job:  map 46% reduce 0%
17/04/04 20:11:47 INFO mapreduce.Job:  map 47% reduce 0%
17/04/04 20:11:48 INFO mapreduce.Job:  map 48% reduce 0%
17/04/04 20:11:54 INFO mapreduce.Job:  map 49% reduce 0%
17/04/04 20:11:56 INFO mapreduce.Job:  map 50% reduce 0%
17/04/04 20:11:58 INFO mapreduce.Job:  map 51% reduce 0%
17/04/04 20:12:02 INFO mapreduce.Job:  map 52% reduce 0%
17/04/04 20:12:08 INFO mapreduce.Job:  map 53% reduce 0%
17/04/04 20:12:09 INFO mapreduce.Job:  map 54% reduce 0%
17/04/04 20:12:13 INFO mapreduce.Job:  map 55% reduce 0%
17/04/04 20:12:17 INFO mapreduce.Job:  map 56% reduce 0%
17/04/04 20:12:19 INFO mapreduce.Job:  map 57% reduce 0%
17/04/04 20:12:23 INFO mapreduce.Job:  map 58% reduce 0%
17/04/04 20:12:26 INFO mapreduce.Job:  map 59% reduce 0%
17/04/04 20:12:28 INFO mapreduce.Job:  map 60% reduce 0%
17/04/04 20:12:34 INFO mapreduce.Job:  map 61% reduce 0%
17/04/04 20:12:37 INFO mapreduce.Job:  map 62% reduce 0%
17/04/04 20:12:38 INFO mapreduce.Job:  map 63% reduce 0%
17/04/04 20:12:44 INFO mapreduce.Job:  map 64% reduce 0%
17/04/04 20:12:46 INFO mapreduce.Job:  map 65% reduce 0%
17/04/04 20:12:48 INFO mapreduce.Job:  map 66% reduce 0%
17/04/04 20:12:51 INFO mapreduce.Job:  map 67% reduce 0%
17/04/04 20:12:58 INFO mapreduce.Job:  map 68% reduce 0%
17/04/04 20:13:00 INFO mapreduce.Job:  map 69% reduce 0%
17/04/04 20:13:03 INFO mapreduce.Job:  map 70% reduce 0%
17/04/04 20:13:06 INFO mapreduce.Job:  map 71% reduce 0%
17/04/04 20:13:09 INFO mapreduce.Job:  map 72% reduce 0%
17/04/04 20:13:13 INFO mapreduce.Job:  map 73% reduce 0%
17/04/04 20:13:15 INFO mapreduce.Job:  map 74% reduce 0%
17/04/04 20:13:18 INFO mapreduce.Job:  map 75% reduce 0%
17/04/04 20:13:24 INFO mapreduce.Job:  map 76% reduce 0%
17/04/04 20:13:27 INFO mapreduce.Job:  map 77% reduce 0%
17/04/04 20:13:28 INFO mapreduce.Job:  map 78% reduce 0%
17/04/04 20:13:29 INFO mapreduce.Job:  map 79% reduce 0%
17/04/04 20:13:38 INFO mapreduce.Job:  map 80% reduce 0%
17/04/04 20:13:39 INFO mapreduce.Job:  map 81% reduce 0%
17/04/04 20:13:40 INFO mapreduce.Job:  map 82% reduce 0%
17/04/04 20:13:48 INFO mapreduce.Job:  map 83% reduce 0%
17/04/04 20:13:50 INFO mapreduce.Job:  map 84% reduce 0%
17/04/04 20:13:59 INFO mapreduce.Job:  map 85% reduce 0%
17/04/04 20:14:00 INFO mapreduce.Job:  map 85% reduce 6%
17/04/04 20:14:02 INFO mapreduce.Job:  map 85% reduce 9%
17/04/04 20:14:03 INFO mapreduce.Job:  map 85% reduce 12%
17/04/04 20:14:04 INFO mapreduce.Job:  map 85% reduce 15%
17/04/04 20:14:06 INFO mapreduce.Job:  map 85% reduce 17%
17/04/04 20:14:07 INFO mapreduce.Job:  map 86% reduce 17%
17/04/04 20:14:08 INFO mapreduce.Job:  map 86% reduce 18%
17/04/04 20:14:09 INFO mapreduce.Job:  map 87% reduce 19%
17/04/04 20:14:10 INFO mapreduce.Job:  map 87% reduce 21%
17/04/04 20:14:12 INFO mapreduce.Job:  map 87% reduce 22%
17/04/04 20:14:14 INFO mapreduce.Job:  map 87% reduce 23%
17/04/04 20:14:15 INFO mapreduce.Job:  map 87% reduce 24%
17/04/04 20:14:17 INFO mapreduce.Job:  map 88% reduce 24%
17/04/04 20:14:19 INFO mapreduce.Job:  map 89% reduce 24%
17/04/04 20:14:22 INFO mapreduce.Job:  map 89% reduce 25%
17/04/04 20:14:25 INFO mapreduce.Job:  map 90% reduce 25%
17/04/04 20:14:30 INFO mapreduce.Job:  map 91% reduce 25%
17/04/04 20:14:34 INFO mapreduce.Job:  map 92% reduce 25%
17/04/04 20:14:40 INFO mapreduce.Job:  map 92% reduce 26%
17/04/04 20:14:42 INFO mapreduce.Job:  map 93% reduce 26%
17/04/04 20:14:43 INFO mapreduce.Job:  map 94% reduce 26%
17/04/04 20:14:49 INFO mapreduce.Job:  map 95% reduce 26%
17/04/04 20:14:52 INFO mapreduce.Job:  map 96% reduce 26%
17/04/04 20:14:57 INFO mapreduce.Job:  map 96% reduce 27%
17/04/04 20:14:58 INFO mapreduce.Job:  map 97% reduce 27%
17/04/04 20:15:01 INFO mapreduce.Job:  map 98% reduce 27%
17/04/04 20:15:07 INFO mapreduce.Job:  map 99% reduce 27%
17/04/04 20:15:12 INFO mapreduce.Job:  map 99% reduce 28%
17/04/04 20:15:13 INFO mapreduce.Job:  map 100% reduce 28%
17/04/04 20:15:15 INFO mapreduce.Job:  map 100% reduce 33%
17/04/04 20:15:16 INFO mapreduce.Job:  map 100% reduce 39%
17/04/04 20:15:18 INFO mapreduce.Job:  map 100% reduce 45%
17/04/04 20:15:19 INFO mapreduce.Job:  map 100% reduce 51%
17/04/04 20:15:21 INFO mapreduce.Job:  map 100% reduce 57%
17/04/04 20:15:22 INFO mapreduce.Job:  map 100% reduce 59%
17/04/04 20:15:24 INFO mapreduce.Job:  map 100% reduce 64%
17/04/04 20:15:27 INFO mapreduce.Job:  map 100% reduce 66%
17/04/04 20:15:28 INFO mapreduce.Job:  map 100% reduce 68%
17/04/04 20:15:30 INFO mapreduce.Job:  map 100% reduce 71%
17/04/04 20:15:31 INFO mapreduce.Job:  map 100% reduce 72%
17/04/04 20:15:33 INFO mapreduce.Job:  map 100% reduce 76%
17/04/04 20:15:36 INFO mapreduce.Job:  map 100% reduce 77%
17/04/04 20:15:37 INFO mapreduce.Job:  map 100% reduce 78%
17/04/04 20:15:39 INFO mapreduce.Job:  map 100% reduce 80%
17/04/04 20:15:42 INFO mapreduce.Job:  map 100% reduce 84%
17/04/04 20:15:43 INFO mapreduce.Job:  map 100% reduce 85%
17/04/04 20:15:45 INFO mapreduce.Job:  map 100% reduce 86%
17/04/04 20:15:46 INFO mapreduce.Job:  map 100% reduce 87%
17/04/04 20:15:48 INFO mapreduce.Job:  map 100% reduce 89%
17/04/04 20:15:49 INFO mapreduce.Job:  map 100% reduce 90%
17/04/04 20:15:51 INFO mapreduce.Job:  map 100% reduce 91%
17/04/04 20:15:52 INFO mapreduce.Job:  map 100% reduce 92%
17/04/04 20:15:54 INFO mapreduce.Job:  map 100% reduce 93%
17/04/04 20:15:55 INFO mapreduce.Job:  map 100% reduce 94%
17/04/04 20:15:57 INFO mapreduce.Job:  map 100% reduce 95%
17/04/04 20:15:58 INFO mapreduce.Job:  map 100% reduce 96%
17/04/04 20:16:00 INFO mapreduce.Job:  map 100% reduce 97%
17/04/04 20:16:06 INFO mapreduce.Job:  map 100% reduce 99%
17/04/04 20:16:08 INFO mapreduce.Job:  map 100% reduce 100%
17/04/04 20:16:09 INFO mapreduce.Job: Job job_1491327357242_0010 completed successfully
17/04/04 20:16:09 INFO mapreduce.Job: Counters: 50
	File System Counters
		FILE: Number of bytes read=4449459252
		FILE: Number of bytes written=8830909307
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
		HDFS: Number of bytes read=10000045000
		HDFS: Number of bytes written=10000000000
		HDFS: Number of read operations=918
		HDFS: Number of large read operations=0
		HDFS: Number of write operations=12
	Job Counters 
		Launched map tasks=300
		Launched reduce tasks=6
		Data-local map tasks=178
		Rack-local map tasks=122
		Total time spent by all maps in occupied slots (ms)=2834529
		Total time spent by all reduces in occupied slots (ms)=686161
		Total time spent by all map tasks (ms)=2834529
		Total time spent by all reduce tasks (ms)=686161
		Total vcore-seconds taken by all map tasks=2834529
		Total vcore-seconds taken by all reduce tasks=686161
		Total megabyte-seconds taken by all map tasks=2902557696
		Total megabyte-seconds taken by all reduce tasks=702628864
	Map-Reduce Framework
		Map input records=100000000
		Map output records=100000000
		Map output bytes=10200000000
		Map output materialized bytes=4342785901
		Input split bytes=45000
		Combine input records=0
		Combine output records=0
		Reduce input groups=100000000
		Reduce shuffle bytes=4342785901
		Reduce input records=100000000
		Reduce output records=100000000
		Spilled Records=200000000
		Shuffled Maps =1800
		Failed Shuffles=0
		Merged Map outputs=1800
		GC time elapsed (ms)=45120
		CPU time spent (ms)=1525410
		Physical memory (bytes) snapshot=153600929792
		Virtual memory (bytes) snapshot=482578800640
		Total committed heap usage (bytes)=172027281408
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters 
		Bytes Read=10000000000
	File Output Format Counters 
		Bytes Written=10000000000
17/04/04 20:16:09 INFO terasort.TeraSort: done












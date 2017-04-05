[centos@ip-10-159-126-189 ~]$ kinit cloudera-scm/admin
Password for cloudera-scm/admin@HADOOP.LOCAL: 
[centos@ip-10-159-126-189 ~]$ klist -l
Principal name                 Cache name
--------------                 ----------
cloudera-scm/admin@HADOOP.LOCA FILE:/tmp/krb5cc_1000
[centos@ip-10-159-126-189 ~]$ klist -e
Ticket cache: FILE:/tmp/krb5cc_1000
Default principal: cloudera-scm/admin@HADOOP.LOCAL

Valid starting       Expires              Service principal
04/05/2017 20:28:12  04/06/2017 20:28:12  krbtgt/HADOOP.LOCAL@HADOOP.LOCAL
	renew until 04/12/2017 20:28:12, Etype (skey, tkt): aes256-cts-hmac-sha1-96, aes256-cts-hmac-sha1-96 
[centos@ip-10-159-126-189 ~]$ 



#Status 
vinicius@semantix:~/Downloads$ curl -X POST -u aquinovale:cloudera 'http://54.227.83.127:7180/api/v1/clusters/aquinovale/services/hive'

  "name" : "hive",
  "type" : "HIVE",
  "clusterRef" : {
    "clusterName" : "cluster"
  },
  "serviceUrl" : "http://ip-10-159-126-189.ec2.internal:7180/cmf/serviceRedirect/hive",
  "serviceState" : "STARTED",
  "healthSummary" : "GOOD",
  "healthChecks" : [ {
    "name" : "HIVE_HIVEMETASTORES_HEALTHY",
    "summary" : "GOOD"
  }, {
    "name" : "HIVE_HIVESERVER2S_HEALTHY",
    "summary" : "GOOD"
  } ],
  "configStale" : false
}

#Stop
vinicius@semantix:~/Downloads$ curl -X POST -u aquinovale:cloudera 'http://54.227.83.127:7180/api/v1/clusters/aquinovale/services/hive/commands/stop'
{
  "id" : 529,
  "name" : "Stop",
  "startTime" : "2017-04-05T15:06:06.292Z",
  "active" : true,
  "serviceRef" : {
    "clusterName" : "cluster",
    "serviceName" : "hive"
  }
}

#Start
vinicius@semantix:~/Downloads$ curl -X POST -u aquinovale:cloudera 'http://54.227.83.127:7180/api/v1/clusters/aquinovale/services/hive/commands/start'
{
  "id" : 533,
  "name" : "Start",
  "startTime" : "2017-04-05T15:07:31.174Z",
  "active" : true,
  "serviceRef" : {
    "clusterName" : "cluster",
    "serviceName" : "hive"
  }


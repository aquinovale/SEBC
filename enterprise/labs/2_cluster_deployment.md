{
  "timestamp" : "2017-04-05T14:55:13.682Z",
  "clusters" : [ {
    "name" : "aquinovale",
    "version" : "CDH5",
    "services" : [ {
      "name" : "hive",
      "type" : "HIVE",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "HIVEMETASTORE",
          "items" : [ {
            "name" : "hive_metastore_java_heapsize",
            "value" : "688914432"
          } ]
        }, {
          "roleType" : "HIVESERVER2",
          "items" : [ {
            "name" : "hiveserver2_java_heapsize",
            "value" : "688914432"
          }, {
            "name" : "hiveserver2_spark_driver_memory",
            "value" : "966367641"
          }, {
            "name" : "hiveserver2_spark_executor_cores",
            "value" : "4"
          }, {
            "name" : "hiveserver2_spark_executor_memory",
            "value" : "3433247539"
          }, {
            "name" : "hiveserver2_spark_yarn_driver_memory_overhead",
            "value" : "102"
          }, {
            "name" : "hiveserver2_spark_yarn_executor_memory_overhead",
            "value" : "577"
          } ]
        } ],
        "items" : [ {
          "name" : "hive_metastore_database_host",
          "value" : "ip-10-159-126-189.ec2.internal"
        }, {
          "name" : "hive_metastore_database_name",
          "value" : "hive"
        }, {
          "name" : "hive_metastore_database_password",
          "value" : "#semantix@"
        }, {
          "name" : "hive_metastore_database_user",
          "value" : "cmf"
        }, {
          "name" : "mapreduce_yarn_service",
          "value" : "yarn"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "hive-GATEWAY-42da64c0accb99c2690f70cdaed3b5dc",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "1c740e2b-78ab-406a-a54b-3ae5e67d0e19"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-53bb28e0ef35bdbe48414388f016f8d7",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "3c06ec6a-0b21-4313-b6be-111cfa9a2fb9"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-b5344f43f6c8ae30b9da6a65e59a3513",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "8004fa61-3117-4c8b-a4d2-cc48ffaedeb3"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-fdad87ceeb750fb4da66588ec8fce401",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-fdcae1be73bbb7c2128f3c5070039aec",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "8207a991-42c1-46f7-9c55-3727d3994634"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-HIVEMETASTORE-fdad87ceeb750fb4da66588ec8fce401",
        "type" : "HIVEMETASTORE",
        "hostRef" : {
          "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "8tijkrtftsvzc8s9z05sf1v3o"
          } ]
        }
      }, {
        "name" : "hive-HIVESERVER2-fdad87ceeb750fb4da66588ec8fce401",
        "type" : "HIVESERVER2",
        "hostRef" : {
          "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "dtw95kxvk4jkon1nqr7ggqq2t"
          } ]
        }
      } ],
      "displayName" : "Hive"
    }, {
      "name" : "zookeeper",
      "type" : "ZOOKEEPER",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "SERVER",
          "items" : [ {
            "name" : "zookeeper_server_java_heapsize",
            "value" : "688914432"
          } ]
        } ],
        "items" : [ ]
      },
      "roles" : [ {
        "name" : "zookeeper-SERVER-42da64c0accb99c2690f70cdaed3b5dc",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "1c740e2b-78ab-406a-a54b-3ae5e67d0e19"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "5z22301s6d3orqfh3ybz721sx"
          }, {
            "name" : "serverId",
            "value" : "3"
          } ]
        }
      }, {
        "name" : "zookeeper-SERVER-b5344f43f6c8ae30b9da6a65e59a3513",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "8004fa61-3117-4c8b-a4d2-cc48ffaedeb3"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "9km9huaet9i7jyaot1hj428h8"
          }, {
            "name" : "serverId",
            "value" : "1"
          } ]
        }
      }, {
        "name" : "zookeeper-SERVER-fdad87ceeb750fb4da66588ec8fce401",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "cl189i8tagycov1wg4yiylvkj"
          }, {
            "name" : "serverId",
            "value" : "2"
          } ]
        }
      } ],
      "displayName" : "ZooKeeper"
    }, {
      "name" : "hue",
      "type" : "HUE",
      "config" : {
        "roleTypeConfigs" : [ ],
        "items" : [ {
          "name" : "database_host",
          "value" : "ip-10-159-126-189.ec2.internal"
        }, {
          "name" : "database_password",
          "value" : "#semantix@"
        }, {
          "name" : "database_type",
          "value" : "mysql"
        }, {
          "name" : "database_user",
          "value" : "cmf"
        }, {
          "name" : "hive_service",
          "value" : "hive"
        }, {
          "name" : "hue_webhdfs",
          "value" : "hdfs-NAMENODE-fdad87ceeb750fb4da66588ec8fce401"
        }, {
          "name" : "oozie_service",
          "value" : "oozie"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "hue-HUE_SERVER-fdad87ceeb750fb4da66588ec8fce401",
        "type" : "HUE_SERVER",
        "hostRef" : {
          "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "ce42s1eblpztig1ebwgfw52cu"
          }, {
            "name" : "secret_key",
            "value" : "aTErzzRaSNJ90OhMhgGqN9Jm1MOfEF"
          } ]
        }
      } ],
      "displayName" : "Hue"
    }, {
      "name" : "oozie",
      "type" : "OOZIE",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "OOZIE_SERVER",
          "items" : [ {
            "name" : "oozie_database_host",
            "value" : "ip-10-159-126-189.ec2.internal"
          }, {
            "name" : "oozie_database_name",
            "value" : "ozs"
          }, {
            "name" : "oozie_database_password",
            "value" : "#semantix@"
          }, {
            "name" : "oozie_database_type",
            "value" : "mysql"
          }, {
            "name" : "oozie_database_user",
            "value" : "cmf"
          }, {
            "name" : "oozie_java_heapsize",
            "value" : "688914432"
          } ]
        } ],
        "items" : [ {
          "name" : "hive_service",
          "value" : "hive"
        }, {
          "name" : "mapreduce_yarn_service",
          "value" : "yarn"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "oozie-OOZIE_SERVER-fdad87ceeb750fb4da66588ec8fce401",
        "type" : "OOZIE_SERVER",
        "hostRef" : {
          "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "3a10jgo84xii62ttcs3ax9dh7"
          } ]
        }
      } ],
      "displayName" : "Oozie"
    }, {
      "name" : "yarn",
      "type" : "YARN",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "GATEWAY",
          "items" : [ {
            "name" : "mapred_reduce_tasks",
            "value" : "6"
          }, {
            "name" : "mapred_submit_replication",
            "value" : "1"
          } ]
        }, {
          "roleType" : "JOBHISTORY",
          "items" : [ {
            "name" : "mr2_jobhistory_java_heapsize",
            "value" : "688914432"
          } ]
        }, {
          "roleType" : "NODEMANAGER",
          "items" : [ {
            "name" : "container_executor_allowed_system_users",
            "value" : "nobody,impala,hive,llama,hbase,aquinovale"
          }, {
            "name" : "rm_cpu_shares",
            "value" : "1800"
          }, {
            "name" : "rm_io_weight",
            "value" : "900"
          }, {
            "name" : "yarn_nodemanager_heartbeat_interval_ms",
            "value" : "100"
          }, {
            "name" : "yarn_nodemanager_local_dirs",
            "value" : "/yarn/nm,/data1/yarn/nm"
          }, {
            "name" : "yarn_nodemanager_log_dirs",
            "value" : "/yarn/container-logs,/data1/yarn/container-logs"
          }, {
            "name" : "yarn_nodemanager_resource_cpu_vcores",
            "value" : "3"
          }, {
            "name" : "yarn_nodemanager_resource_memory_mb",
            "value" : "4939"
          } ]
        }, {
          "roleType" : "RESOURCEMANAGER",
          "items" : [ {
            "name" : "yarn_scheduler_maximum_allocation_mb",
            "value" : "4939"
          }, {
            "name" : "yarn_scheduler_maximum_allocation_vcores",
            "value" : "3"
          } ]
        } ],
        "items" : [ {
          "name" : "hdfs_service",
          "value" : "hdfs"
        }, {
          "name" : "rm_dirty",
          "value" : "false"
        }, {
          "name" : "rm_last_allocation_percentage",
          "value" : "90"
        }, {
          "name" : "yarn_service_cgroups",
          "value" : "false"
        }, {
          "name" : "yarn_service_lce_always",
          "value" : "false"
        }, {
          "name" : "zk_authorization_secret_key",
          "value" : "Xg3N9XI75WxrWgJ1D1QEtlUxR6LXLK"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "yarn-JOBHISTORY-fdad87ceeb750fb4da66588ec8fce401",
        "type" : "JOBHISTORY",
        "hostRef" : {
          "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "8nhr8xuqowl44fgsqsw221igv"
          } ]
        }
      }, {
        "name" : "yarn-NODEMANAGER-42da64c0accb99c2690f70cdaed3b5dc",
        "type" : "NODEMANAGER",
        "hostRef" : {
          "hostId" : "1c740e2b-78ab-406a-a54b-3ae5e67d0e19"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "4r1dh56gsnx5nuqetkkkzwkdn"
          } ]
        }
      }, {
        "name" : "yarn-NODEMANAGER-53bb28e0ef35bdbe48414388f016f8d7",
        "type" : "NODEMANAGER",
        "hostRef" : {
          "hostId" : "3c06ec6a-0b21-4313-b6be-111cfa9a2fb9"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "dvnr37wz7noohsn2sutn5j66f"
          } ]
        }
      }, {
        "name" : "yarn-NODEMANAGER-fdcae1be73bbb7c2128f3c5070039aec",
        "type" : "NODEMANAGER",
        "hostRef" : {
          "hostId" : "8207a991-42c1-46f7-9c55-3727d3994634"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "50n6lindzvvh8dntfrd638hqj"
          } ]
        }
      }, {
        "name" : "yarn-RESOURCEMANAGER-b5344f43f6c8ae30b9da6a65e59a3513",
        "type" : "RESOURCEMANAGER",
        "hostRef" : {
          "hostId" : "8004fa61-3117-4c8b-a4d2-cc48ffaedeb3"
        },
        "config" : {
          "items" : [ {
            "name" : "rm_id",
            "value" : "78"
          }, {
            "name" : "role_jceks_password",
            "value" : "4lbksjvihjewwdtf791odi8rs"
          } ]
        }
      } ],
      "displayName" : "YARN (MR2 Included)"
    }, {
      "name" : "hdfs",
      "type" : "HDFS",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "BALANCER",
          "items" : [ {
            "name" : "balancer_java_heapsize",
            "value" : "688914432"
          } ]
        }, {
          "roleType" : "DATANODE",
          "items" : [ {
            "name" : "datanode_java_heapsize",
            "value" : "1073741824"
          }, {
            "name" : "dfs_data_dir_list",
            "value" : "/dfs/dn,/data1/dfs/dn"
          }, {
            "name" : "dfs_datanode_du_reserved",
            "value" : "4293264998"
          }, {
            "name" : "dfs_datanode_failed_volumes_tolerated",
            "value" : "1"
          }, {
            "name" : "dfs_datanode_max_locked_memory",
            "value" : "4294967296"
          }, {
            "name" : "rm_cpu_shares",
            "value" : "200"
          }, {
            "name" : "rm_io_weight",
            "value" : "100"
          } ]
        }, {
          "roleType" : "GATEWAY",
          "items" : [ {
            "name" : "dfs_client_use_trash",
            "value" : "true"
          } ]
        }, {
          "roleType" : "JOURNALNODE",
          "items" : [ {
            "name" : "dfs_journalnode_edits_dir",
            "value" : "/data1/dfs/jn"
          } ]
        }, {
          "roleType" : "NAMENODE",
          "items" : [ {
            "name" : "dfs_name_dir_list",
            "value" : "/dfs/nn,/data1/dfs/nn"
          }, {
            "name" : "dfs_namenode_servicerpc_address",
            "value" : "8022"
          }, {
            "name" : "namenode_java_heapsize",
            "value" : "1073741824"
          }, {
            "name" : "role_config_suppression_namenode_java_heapsize_minimum_validator",
            "value" : "true"
          } ]
        }, {
          "roleType" : "SECONDARYNAMENODE",
          "items" : [ {
            "name" : "fs_checkpoint_dir_list",
            "value" : "/dfs/snn"
          }, {
            "name" : "secondary_namenode_java_heapsize",
            "value" : "1073741824"
          } ]
        } ],
        "items" : [ {
          "name" : "dfs_ha_fencing_cloudera_manager_secret_key",
          "value" : "t3NpAsQLbuQyGBEmISvd3p98xmXhc9"
        }, {
          "name" : "dfs_ha_fencing_methods",
          "value" : "shell(true)"
        }, {
          "name" : "fc_authorization_secret_key",
          "value" : "5jxSa1bjsOKAKirPeE63uzfg136h1O"
        }, {
          "name" : "http_auth_signature_secret",
          "value" : "SsupGtC9J2AOYnBKNHDhbWwfwLV1a8"
        }, {
          "name" : "rm_dirty",
          "value" : "false"
        }, {
          "name" : "rm_last_allocation_percentage",
          "value" : "10"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "hdfs-BALANCER-fdad87ceeb750fb4da66588ec8fce401",
        "type" : "BALANCER",
        "hostRef" : {
          "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hdfs-DATANODE-42da64c0accb99c2690f70cdaed3b5dc",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "1c740e2b-78ab-406a-a54b-3ae5e67d0e19"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "9spi6rpst4ywcms9gp4yiif6i"
          } ]
        }
      }, {
        "name" : "hdfs-DATANODE-53bb28e0ef35bdbe48414388f016f8d7",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "3c06ec6a-0b21-4313-b6be-111cfa9a2fb9"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "cbgh4a0s637v7595m7bs774v1"
          } ]
        }
      }, {
        "name" : "hdfs-DATANODE-fdcae1be73bbb7c2128f3c5070039aec",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "8207a991-42c1-46f7-9c55-3727d3994634"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "1aa0fifcd1ezih654otgsdiob"
          } ]
        }
      }, {
        "name" : "hdfs-FAILOVERCONTROLLER-b5344f43f6c8ae30b9da6a65e59a3513",
        "type" : "FAILOVERCONTROLLER",
        "hostRef" : {
          "hostId" : "8004fa61-3117-4c8b-a4d2-cc48ffaedeb3"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "en898v1wt433gzwkr82wv6y2y"
          } ]
        }
      }, {
        "name" : "hdfs-FAILOVERCONTROLLER-fdad87ceeb750fb4da66588ec8fce401",
        "type" : "FAILOVERCONTROLLER",
        "hostRef" : {
          "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "58z4bbu6w3u3vtcebp7pkfvyj"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-42da64c0accb99c2690f70cdaed3b5dc",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "1c740e2b-78ab-406a-a54b-3ae5e67d0e19"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "dw1hcr4cooj3ybrz9adfzk4c2"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-b5344f43f6c8ae30b9da6a65e59a3513",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "8004fa61-3117-4c8b-a4d2-cc48ffaedeb3"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "c84z34d33xk917wskqozt7evi"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-fdad87ceeb750fb4da66588ec8fce401",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "czineyz7iniobtsjzhqg4oq4p"
          } ]
        }
      }, {
        "name" : "hdfs-NAMENODE-b5344f43f6c8ae30b9da6a65e59a3513",
        "type" : "NAMENODE",
        "hostRef" : {
          "hostId" : "8004fa61-3117-4c8b-a4d2-cc48ffaedeb3"
        },
        "config" : {
          "items" : [ {
            "name" : "autofailover_enabled",
            "value" : "true"
          }, {
            "name" : "dfs_federation_namenode_nameservice",
            "value" : "nameservice1"
          }, {
            "name" : "dfs_namenode_quorum_journal_name",
            "value" : "nameservice1"
          }, {
            "name" : "namenode_id",
            "value" : "85"
          }, {
            "name" : "role_jceks_password",
            "value" : "2zf0sc69t770p98btscdlr19f"
          } ]
        }
      }, {
        "name" : "hdfs-NAMENODE-fdad87ceeb750fb4da66588ec8fce401",
        "type" : "NAMENODE",
        "hostRef" : {
          "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
        },
        "config" : {
          "items" : [ {
            "name" : "autofailover_enabled",
            "value" : "true"
          }, {
            "name" : "dfs_federation_namenode_nameservice",
            "value" : "nameservice1"
          }, {
            "name" : "dfs_namenode_quorum_journal_name",
            "value" : "nameservice1"
          }, {
            "name" : "namenode_id",
            "value" : "80"
          }, {
            "name" : "role_jceks_password",
            "value" : "clrt7x6lxspq6789ur8tw5qnc"
          } ]
        }
      } ],
      "displayName" : "HDFS"
    } ]
  } ],
  "hosts" : [ {
    "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62",
    "ipAddress" : "10.159.126.189",
    "hostname" : "ip-10-159-126-189.ec2.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ {
        "name" : "memory_overcommit_threshold",
        "value" : "0.9"
      } ]
    }
  }, {
    "hostId" : "1c740e2b-78ab-406a-a54b-3ae5e67d0e19",
    "ipAddress" : "10.167.211.202",
    "hostname" : "ip-10-167-211-202.ec2.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "8004fa61-3117-4c8b-a4d2-cc48ffaedeb3",
    "ipAddress" : "10.230.80.231",
    "hostname" : "ip-10-230-80-231.ec2.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "3c06ec6a-0b21-4313-b6be-111cfa9a2fb9",
    "ipAddress" : "10.61.164.57",
    "hostname" : "ip-10-61-164-57.ec2.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "8207a991-42c1-46f7-9c55-3727d3994634",
    "ipAddress" : "10.63.75.96",
    "hostname" : "ip-10-63-75-96.ec2.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  } ],
  "users" : [ {
    "name" : "__cloudera_internal_user__mgmt-EVENTSERVER-fdad87ceeb750fb4da66588ec8fce401",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "0388cf5170283f2093c51f174afe205b858d891ff8e82a1aef13e916792e9549",
    "pwSalt" : 1499822221068104834,
    "pwLogin" : true
  }, {
    "name" : "__cloudera_internal_user__mgmt-HOSTMONITOR-fdad87ceeb750fb4da66588ec8fce401",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "ad90ee6fbc882b1bd2a4aa8e0c5df2d99f55195970b9ba52932cfb85b536ffa7",
    "pwSalt" : -7638530869580530263,
    "pwLogin" : true
  }, {
    "name" : "__cloudera_internal_user__mgmt-REPORTSMANAGER-fdad87ceeb750fb4da66588ec8fce401",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "bbc4d09e0303ce0925fac46c11fa33c71cb32aceec9b68201301d66d448bb624",
    "pwSalt" : -5889433532813175120,
    "pwLogin" : true
  }, {
    "name" : "__cloudera_internal_user__mgmt-SERVICEMONITOR-fdad87ceeb750fb4da66588ec8fce401",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "5c9c1cc6b06add42becea12f90114792766ace2b6ecb7ca762bc0e308e78e4b4",
    "pwSalt" : -8291140970846244022,
    "pwLogin" : true
  }, {
    "name" : "admin",
    "roles" : [ "ROLE_LIMITED" ],
    "pwHash" : "5b381895131dd22f0de1a8aa0177ee67ff535c5bc3594f0a1df5d7d6458854c5",
    "pwSalt" : 6311750426058296782,
    "pwLogin" : true
  }, {
    "name" : "aquinovale",
    "roles" : [ "ROLE_ADMIN" ],
    "pwHash" : "568cf6410b6863213f760081623dc587e98b023ad14dc7896980caa6683ebeff",
    "pwSalt" : -9096538875599782866,
    "pwLogin" : true
  }, {
    "name" : "minotaur",
    "roles" : [ "ROLE_CONFIGURATOR" ],
    "pwHash" : "950fd87ffd891f519e0bcbebab7e5a3113caa7a3bf4885d2075d5fde7f569fd6",
    "pwSalt" : 2270841077128258122,
    "pwLogin" : true
  } ],
  "versionInfo" : {
    "version" : "5.10.1",
    "buildUser" : "jenkins",
    "buildTimestamp" : "20170319-2001",
    "gitHash" : "f226435f6fa5f545543c00245900ae43bea7a29c",
    "snapshot" : false
  },
  "managementService" : {
    "name" : "mgmt",
    "type" : "MGMT",
    "config" : {
      "roleTypeConfigs" : [ {
        "roleType" : "EVENTSERVER",
        "items" : [ {
          "name" : "event_server_heapsize",
          "value" : "688914432"
        } ]
      }, {
        "roleType" : "HOSTMONITOR",
        "items" : [ {
          "name" : "firehose_heapsize",
          "value" : "688914432"
        }, {
          "name" : "firehose_non_java_memory_bytes",
          "value" : "895483904"
        }, {
          "name" : "role_config_suppression_firehose_heap_size_validator",
          "value" : "true"
        }, {
          "name" : "role_config_suppression_firehose_non_java_memory_validator",
          "value" : "true"
        } ]
      }, {
        "roleType" : "REPORTSMANAGER",
        "items" : [ {
          "name" : "headlamp_database_host",
          "value" : "ip-10-159-126-189.ec2.internal"
        }, {
          "name" : "headlamp_database_name",
          "value" : "rm"
        }, {
          "name" : "headlamp_database_password",
          "value" : "#semantix@"
        }, {
          "name" : "headlamp_database_user",
          "value" : "cmf"
        }, {
          "name" : "headlamp_heapsize",
          "value" : "688914432"
        } ]
      }, {
        "roleType" : "SERVICEMONITOR",
        "items" : [ {
          "name" : "firehose_heapsize",
          "value" : "688914432"
        }, {
          "name" : "firehose_non_java_memory_bytes",
          "value" : "895483904"
        }, {
          "name" : "role_config_suppression_firehose_heap_size_validator",
          "value" : "true"
        }, {
          "name" : "role_config_suppression_firehose_non_java_memory_validator",
          "value" : "true"
        } ]
      } ],
      "items" : [ ]
    },
    "roles" : [ {
      "name" : "mgmt-ALERTPUBLISHER-fdad87ceeb750fb4da66588ec8fce401",
      "type" : "ALERTPUBLISHER",
      "hostRef" : {
        "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "bzudwpm01mqjy9m1d4urm1fbw"
        } ]
      }
    }, {
      "name" : "mgmt-EVENTSERVER-fdad87ceeb750fb4da66588ec8fce401",
      "type" : "EVENTSERVER",
      "hostRef" : {
        "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "4ufn298nts9o8oywjl8iikqk4"
        } ]
      }
    }, {
      "name" : "mgmt-HOSTMONITOR-fdad87ceeb750fb4da66588ec8fce401",
      "type" : "HOSTMONITOR",
      "hostRef" : {
        "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "egooku4u4zt2ccbg9klltzul7"
        } ]
      }
    }, {
      "name" : "mgmt-REPORTSMANAGER-fdad87ceeb750fb4da66588ec8fce401",
      "type" : "REPORTSMANAGER",
      "hostRef" : {
        "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "3tozeiced2ael5xjafrev7do9"
        } ]
      }
    }, {
      "name" : "mgmt-SERVICEMONITOR-fdad87ceeb750fb4da66588ec8fce401",
      "type" : "SERVICEMONITOR",
      "hostRef" : {
        "hostId" : "b99166c4-287d-4007-b0f7-4274552fad62"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "6q7l6qcg31fsplvu3jzp6pzip"
        } ]
      }
    } ],
    "displayName" : "Cloudera Management Service"
  },
  "managerSettings" : {
    "items" : [ {
      "name" : "CLUSTER_STATS_START",
      "value" : "10/27/2012 13:40"
    }, {
      "name" : "PUBLIC_CLOUD_STATUS",
      "value" : "ON_PUBLIC_CLOUD"
    }, {
      "name" : "REMOTE_PARCEL_REPO_URLS",
      "value" : "https://archive.cloudera.com/cdh5/parcels/{latest_supported}/,https://archive.cloudera.com/cdh4/parcels/latest/,https://archive.cloudera.com/impala/parcels/latest/,https://archive.cloudera.com/search/parcels/latest/,https://archive.cloudera.com/accumulo/parcels/1.4/,https://archive.cloudera.com/accumulo-c5/parcels/latest/,https://archive.cloudera.com/kafka/parcels/latest/,https://archive.cloudera.com/navigator-keytrustee5/parcels/latest/,https://archive.cloudera.com/spark/parcels/latest/,https://archive.cloudera.com/sqoop-connectors/parcels/latest/"
    } ]
  }


Using bundled JDK: /usr/share/logstash/jdk
OpenJDK 64-Bit Server VM warning: Option UseConcMarkSweepGC was deprecated in version 9.0 and will likely be removed in a future release.
Sending Logstash logs to /usr/share/logstash/logs which is now configured via log4j2.properties
[2022-04-05T18:19:57,174][INFO ][logstash.runner          ] Log4j configuration path used is: /usr/share/logstash/config/log4j2.properties
[2022-04-05T18:19:57,194][INFO ][logstash.runner          ] Starting Logstash {"logstash.version"=>"7.17.1", "jruby.version"=>"jruby 9.2.20.1 (2.5.8) 2021-11-30 2a2962fbd1 OpenJDK 64-Bit Server VM 11.0.13+8 on 11.0.13+8 +indy +jit [linux-x86_64]"}
[2022-04-05T18:19:57,196][INFO ][logstash.runner          ] JVM bootstrap flags: [-Xms1g, -Xmx1g, -XX:+UseConcMarkSweepGC, -XX:CMSInitiatingOccupancyFraction=75, -XX:+UseCMSInitiatingOccupancyOnly, -Djava.awt.headless=true, -Dfile.encoding=UTF-8, -Djruby.compile.invokedynamic=true, -Djruby.jit.threshold=0, -Djruby.regexp.interruptible=true, -XX:+HeapDumpOnOutOfMemoryError, -Djava.security.egd=file:/dev/urandom, -Dlog4j2.isThreadContextMapInheritable=true, -Dls.cgroup.cpuacct.path.override=/, -Dls.cgroup.cpu.path.override=/]
[2022-04-05T18:19:57,256][INFO ][logstash.settings        ] Creating directory {:setting=>"path.queue", :path=>"/usr/share/logstash/data/queue"}
[2022-04-05T18:19:57,286][INFO ][logstash.settings        ] Creating directory {:setting=>"path.dead_letter_queue", :path=>"/usr/share/logstash/data/dead_letter_queue"}
[2022-04-05T18:19:58,047][INFO ][logstash.agent           ] No persistent UUID file found. Generating new UUID {:uuid=>"d8587fef-67a4-45ba-b494-1680371cc82d", :path=>"/usr/share/logstash/data/uuid"}
[2022-04-05T18:20:00,039][WARN ][logstash.monitoringextension.pipelineregisterhook] xpack.monitoring.enabled has not been defined, but found elasticsearch configuration. Please explicitly set `xpack.monitoring.enabled: true` in logstash.yml
[2022-04-05T18:20:00,044][WARN ][deprecation.logstash.monitoringextension.pipelineregisterhook] Internal collectors option for Logstash monitoring is deprecated and may be removed in a future release.
Please configure Metricbeat to monitor Logstash. Documentation can be found at:
https://www.elastic.co/guide/en/logstash/current/monitoring-with-metricbeat.html
[2022-04-05T18:20:00,863][WARN ][deprecation.logstash.codecs.plain] Relying on default value of `pipeline.ecs_compatibility`, which may change in a future major release of Logstash. To avoid unexpected changes when upgrading Logstash, please explicitly declare your desired ECS Compatibility mode.
[2022-04-05T18:20:01,031][WARN ][deprecation.logstash.outputs.elasticsearch] Relying on default value of `pipeline.ecs_compatibility`, which may change in a future major release of Logstash. To avoid unexpected changes when upgrading Logstash, please explicitly declare your desired ECS Compatibility mode.
[2022-04-05T18:20:01,858][INFO ][logstash.licensechecker.licensereader] Elasticsearch pool URLs updated {:changes=>{:removed=>[], :added=>[http://172.31.12.23:9200/]}}
[2022-04-05T18:20:02,327][WARN ][logstash.licensechecker.licensereader] Restored connection to ES instance {:url=>"http://172.31.12.23:9200/"}
[2022-04-05T18:20:02,360][INFO ][logstash.licensechecker.licensereader] Elasticsearch version determined (7.17.1) {:es_version=>7}
[2022-04-05T18:20:02,368][WARN ][logstash.licensechecker.licensereader] Detected a 6.x and above cluster: the `type` event field won't be used to determine the document _type {:es_version=>7}
[2022-04-05T18:20:02,568][INFO ][logstash.monitoring.internalpipelinesource] Monitoring License OK
[2022-04-05T18:20:02,575][INFO ][logstash.monitoring.internalpipelinesource] Validated license for monitoring. Enabling monitoring pipeline.
[2022-04-05T18:20:03,035][INFO ][logstash.agent           ] Successfully started Logstash API endpoint {:port=>9600, :ssl_enabled=>false}
[2022-04-05T18:20:06,571][INFO ][org.reflections.Reflections] Reflections took 259 ms to scan 1 urls, producing 119 keys and 417 values
[2022-04-05T18:20:07,847][WARN ][deprecation.logstash.codecs.plain] Relying on default value of `pipeline.ecs_compatibility`, which may change in a future major release of Logstash. To avoid unexpected changes when upgrading Logstash, please explicitly declare your desired ECS Compatibility mode.
[2022-04-05T18:20:07,858][WARN ][deprecation.logstash.codecs.plain] Relying on default value of `pipeline.ecs_compatibility`, which may change in a future major release of Logstash. To avoid unexpected changes when upgrading Logstash, please explicitly declare your desired ECS Compatibility mode.
[2022-04-05T18:20:07,951][WARN ][deprecation.logstash.inputs.file] Relying on default value of `pipeline.ecs_compatibility`, which may change in a future major release of Logstash. To avoid unexpected changes when upgrading Logstash, please explicitly declare your desired ECS Compatibility mode.
[2022-04-05T18:20:07,978][WARN ][deprecation.logstash.codecs.plain] Relying on default value of `pipeline.ecs_compatibility`, which may change in a future major release of Logstash. To avoid unexpected changes when upgrading Logstash, please explicitly declare your desired ECS Compatibility mode.
[2022-04-05T18:20:08,018][WARN ][deprecation.logstash.codecs.plain] Relying on default value of `pipeline.ecs_compatibility`, which may change in a future major release of Logstash. To avoid unexpected changes when upgrading Logstash, please explicitly declare your desired ECS Compatibility mode.
[2022-04-05T18:20:08,049][WARN ][deprecation.logstash.outputs.elasticsearchmonitoring] Relying on default value of `pipeline.ecs_compatibility`, which may change in a future major release of Logstash. To avoid unexpected changes when upgrading Logstash, please explicitly declare your desired ECS Compatibility mode.
[2022-04-05T18:20:08,080][WARN ][deprecation.logstash.outputs.elasticsearch] Relying on default value of `pipeline.ecs_compatibility`, which may change in a future major release of Logstash. To avoid unexpected changes when upgrading Logstash, please explicitly declare your desired ECS Compatibility mode.
[2022-04-05T18:20:08,302][INFO ][logstash.outputs.elasticsearchmonitoring][.monitoring-logstash] New Elasticsearch output {:class=>"LogStash::Outputs::ElasticSearchMonitoring", :hosts=>["http://172.31.12.23:9200"]}
[2022-04-05T18:20:08,435][INFO ][logstash.outputs.elasticsearchmonitoring][.monitoring-logstash] Elasticsearch pool URLs updated {:changes=>{:removed=>[], :added=>[http://172.31.12.23:9200/]}}
[2022-04-05T18:20:08,535][WARN ][logstash.outputs.elasticsearchmonitoring][.monitoring-logstash] Restored connection to ES instance {:url=>"http://172.31.12.23:9200/"}
[2022-04-05T18:20:08,559][INFO ][logstash.outputs.elasticsearchmonitoring][.monitoring-logstash] Elasticsearch version determined (7.17.1) {:es_version=>7}
[2022-04-05T18:20:08,563][WARN ][logstash.outputs.elasticsearchmonitoring][.monitoring-logstash] Detected a 6.x and above cluster: the `type` event field won't be used to determine the document _type {:es_version=>7}
[2022-04-05T18:20:08,703][INFO ][logstash.outputs.elasticsearchmonitoring][.monitoring-logstash] Config is not compliant with data streams. `data_stream => auto` resolved to `false`
[2022-04-05T18:20:08,707][INFO ][logstash.outputs.elasticsearchmonitoring][.monitoring-logstash] Config is not compliant with data streams. `data_stream => auto` resolved to `false`
[2022-04-05T18:20:08,726][INFO ][logstash.outputs.elasticsearch][main] New Elasticsearch output {:class=>"LogStash::Outputs::ElasticSearch", :hosts=>["//172.31.12.23:9200"]}
[2022-04-05T18:20:08,735][WARN ][logstash.javapipeline    ][.monitoring-logstash] 'pipeline.ordered' is enabled and is likely less efficient, consider disabling if preserving event order is not necessary
[2022-04-05T18:20:08,825][INFO ][logstash.outputs.elasticsearch][main] Elasticsearch pool URLs updated {:changes=>{:removed=>[], :added=>[http://172.31.12.23:9200/]}}
[2022-04-05T18:20:08,849][WARN ][logstash.outputs.elasticsearch][main] Restored connection to ES instance {:url=>"http://172.31.12.23:9200/"}
[2022-04-05T18:20:08,864][INFO ][logstash.outputs.elasticsearch][main] Elasticsearch version determined (7.17.1) {:es_version=>7}
[2022-04-05T18:20:08,867][WARN ][logstash.outputs.elasticsearch][main] Detected a 6.x and above cluster: the `type` event field won't be used to determine the document _type {:es_version=>7}
[2022-04-05T18:20:08,902][INFO ][logstash.outputs.elasticsearch][main] Config is not compliant with data streams. `data_stream => auto` resolved to `false`
[2022-04-05T18:20:08,939][INFO ][logstash.outputs.elasticsearch][main] Using a default mapping template {:es_version=>7, :ecs_compatibility=>:disabled}
[2022-04-05T18:20:08,959][INFO ][logstash.javapipeline    ][.monitoring-logstash] Starting pipeline {:pipeline_id=>".monitoring-logstash", "pipeline.workers"=>1, "pipeline.batch.size"=>2, "pipeline.batch.delay"=>50, "pipeline.max_inflight"=>2, "pipeline.sources"=>["monitoring pipeline"], :thread=>"#<Thread:0x23f1963a run>"}
[2022-04-05T18:20:08,971][INFO ][logstash.javapipeline    ][main] Starting pipeline {:pipeline_id=>"main", "pipeline.workers"=>1, "pipeline.batch.size"=>125, "pipeline.batch.delay"=>50, "pipeline.max_inflight"=>125, "pipeline.sources"=>["/usr/share/logstash/pipeline/logstash.conf"], :thread=>"#<Thread:0x7abd8dd0@/usr/share/logstash/logstash-core/lib/logstash/pipeline_action/create.rb:54 run>"}
[2022-04-05T18:20:10,533][INFO ][logstash.javapipeline    ][.monitoring-logstash] Pipeline Java execution initialization time {"seconds"=>1.56}
[2022-04-05T18:20:10,710][INFO ][logstash.javapipeline    ][.monitoring-logstash] Pipeline started {"pipeline.id"=>".monitoring-logstash"}
[2022-04-05T18:20:10,839][INFO ][logstash.javapipeline    ][main] Pipeline Java execution initialization time {"seconds"=>1.87}
[2022-04-05T18:20:10,923][INFO ][logstash.inputs.file     ][main] No sincedb_path set, generating one based on the "path" setting {:sincedb_path=>"/usr/share/logstash/data/plugins/inputs/file/.sincedb_f2262573f9ae9c64c4928fb84135368c", :path=>["/api-logs/users-ws.log"]}
[2022-04-05T18:20:10,954][INFO ][logstash.javapipeline    ][main] Pipeline started {"pipeline.id"=>"main"}
[2022-04-05T18:20:11,023][INFO ][logstash.agent           ] Pipelines running {:count=>2, :running_pipelines=>[:".monitoring-logstash", :main], :non_running_pipelines=>[]}
[2022-04-05T18:20:11,051][INFO ][filewatch.observingtail  ][main][c38298305ed3072cba8f290b0e0cb1037a350aac303bfa45a280543a2ed34fbc] START, creating Discoverer, Watch with file and sincedb collections

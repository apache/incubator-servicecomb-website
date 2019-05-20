---
title: "Release Notes"
lang: en
ref: release
permalink: /release/java-chassis-release-notes/
excerpt: "Release Notes"
last_modified_at: 2019-04-12T00:50:43-55:00
---


        Release Notes - Apache ServiceComb - Version java-chassis-1.2.1
            
<h2>        Bug
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1088'>SCB-1088</a>] -         SDK IsolationServerEvent is missing endpoint information
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1251'>SCB-1251</a>] -         reduce configuration inject callback
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1253'>SCB-1253</a>] -         Adjust the priority of FailureHandler of the dispatchers
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1260'>SCB-1260</a>] -         inspector online test with servlet.urlPattern cause 404
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1266'>SCB-1266</a>] -         ScbMarker work with log4j2 will cause log4j2 leak instance of Marker
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1280'>SCB-1280</a>] -         Fix problem with nested generic list param like List&lt;List&lt;String&gt;&gt;
</li>
</ul>
                
<h2>        Improvement
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1229'>SCB-1229</a>] -         update the version of dependency
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1250'>SCB-1250</a>] -         make ArchaiusUtils simpler
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1259'>SCB-1259</a>] -         response type support Optional
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1265'>SCB-1265</a>] -         Add doc about maxHeaderSize configuration
</li>
</ul>
            
<h2>        Task
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1246'>SCB-1246</a>] -         EventBus subscriber support order
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1262'>SCB-1262</a>] -         change 1.2.0-SNAPSHOT to 1.3.0-SNAPSHOT in pom.xml
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1263'>SCB-1263</a>] -         forward request in edge should not inherit cse-context
</li>
</ul>
                                                                                                                                        
                                                                                                                                        
        Release Notes - Apache ServiceComb - Version java-chassis-1.2.0
    
<h2>        Sub-task
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-353'>SCB-353</a>] -         Support Servicecomb metrics with statics during a long time
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-837'>SCB-837</a>] -         add http2 special configuration
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-945'>SCB-945</a>] -         enhance swagger to idl to support method parameter/result/List&lt;List&gt;/List&lt;Map&gt;/Map&lt;List&gt;/Map&lt;Map&gt;
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-946'>SCB-946</a>] -         serialize/deseriaze List&lt;List&lt;X&gt;&gt;/List&lt;Map&lt;X, Y&gt;&gt;/Map&lt;X, List&lt;Y&gt;&gt;/Map&lt;X, Map&lt;Y, Z&gt;&gt;
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1071'>SCB-1071</a>] -         serialize/deserialize array and primitives
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1144'>SCB-1144</a>] -         change samples use log4j2
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1153'>SCB-1153</a>] -         provide traceId-invocationId by marker mechanism
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1162'>SCB-1162</a>] -         document for PriorityProperty/InjectProperties/InjectProperty
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1175'>SCB-1175</a>] -         document for basic configuration rule
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1188'>SCB-1188</a>] -         provide a way to view/convert and download schemas
</li>
</ul>
        
<h2>        Bug
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-781'>SCB-781</a>] -         support @ConfigurationProperties with Apollo.
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-968'>SCB-968</a>] -         [SCB-968] http2 do not support pump download
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1054'>SCB-1054</a>] -         when download file, we should ignore consumer acceptType
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1065'>SCB-1065</a>] -         when request not contain traceId,should use provider&#39;s invocation&#39;s traceId
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1066'>SCB-1066</a>] -         when start error, destroy method may throw an exception lead to origin exception losed
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1073'>SCB-1073</a>] -         StaticMicroserviceVersions should be ignored while checking instance cache
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1088'>SCB-1088</a>] -         SDK IsolationServerEvent is missing endpoint information
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1089'>SCB-1089</a>] -         Fix PrometheusPublisher naming error
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1095'>SCB-1095</a>] -         Timer task need catch all throwable to protected from unexpected error
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1096'>SCB-1096</a>] -         [SCB-1096]change the method calculate process cpu rate  to same with top
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1102'>SCB-1102</a>] -         fix empty swagger and information leak problem
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1108'>SCB-1108</a>] -         when timeout, the access log status is 200
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1109'>SCB-1109</a>] -         local-service-registry sample of java-chassis can not run directly 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1114'>SCB-1114</a>] -         upgrade zipkin
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1115'>SCB-1115</a>] -         fix not standard protostuff javadoc @Created
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1126'>SCB-1126</a>] -         springmvc project generated by ServiceComb scaffold can not run
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1129'>SCB-1129</a>] -         @JsonProperty on enum value is ignored
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1141'>SCB-1141</a>] -         latest versionRule can not update to new version
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1143'>SCB-1143</a>] -         Servicecomb support watch service center with auth headers
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1156'>SCB-1156</a>] -         avoid collect wrong invocation stage data when rest invoke failed
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1191'>SCB-1191</a>] -         NPE When return type is ResponseEntity&lt;Void&gt;
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1224'>SCB-1224</a>] -         [SCB-1224] az affinity is conflict with empty instance protection
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1226'>SCB-1226</a>] -         there are problems when request rejected by thread pool queue full
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1230'>SCB-1230</a>] -         avoid throw exception in httpClientResponse.exceptionHandler
</li>
</ul>
        
<h2>        New Feature
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1048'>SCB-1048</a>] -         Provide a way to configure bootstrap information in Cloud Native enviroment
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1061'>SCB-1061</a>] -         Provide a way to using handlers(e.g. LoabalanceHanler) outside handler chain
</li>
</ul>
        
<h2>        Improvement
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-674'>SCB-674</a>] -         protobuf codec based on idl from swagger
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1037'>SCB-1037</a>] -         in vertx 3.6.0, PumpImpl do not support &quot;&quot;, it will throw exception
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1044'>SCB-1044</a>] -         add current process CPU rate  and net packets in the metrics
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1047'>SCB-1047</a>] -         microservice.yaml  service_description.version support format xxx.xx.xxx.xxx
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1051'>SCB-1051</a>] -         when interface set produces=text/plain;charset=utf-8. and consumers set accept = text/plain,will cause error
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1056'>SCB-1056</a>] -         Put provider QPS flow control in front
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1063'>SCB-1063</a>] -         Improve the time cost when first time loading schema
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1068'>SCB-1068</a>] -         As a developer want to know instance detail info when instance isolation 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1072'>SCB-1072</a>] -         change dependency management version to project.version
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1074'>SCB-1074</a>] -         minor fixes for mistakes and logs
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1075'>SCB-1075</a>] -         upgrade spring-framework to 4.3.20.RELEASE
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1076'>SCB-1076</a>] -         upgrade guava to 25.1
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1077'>SCB-1077</a>] -         upgrade hystrix to 1.5.12
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1079'>SCB-1079</a>] -         allow consumer-id to be empty when query instance
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1101'>SCB-1101</a>] -         ServiceComb-Java-Chassis support IPv6
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1106'>SCB-1106</a>] -         isolation must make sure one of instances is available
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1135'>SCB-1135</a>] -         Add client max receive header size config item
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1139'>SCB-1139</a>] -         Upgrade Vert.x to 3.6
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1146'>SCB-1146</a>] -         update PR template
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1157'>SCB-1157</a>] -         spring-boot2-starter-discovery and spring-boot-starter-discovery depend on zuul is not correct
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1170'>SCB-1170</a>] -         improve log of upload directory during boot.
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1177'>SCB-1177</a>] -         update vertx to 3.6+ version to result .vertx directory was default created 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1178'>SCB-1178</a>] -         In the unit test, the issue of assertEquals and Float.MAX_VALUE.
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1179'>SCB-1179</a>] -         Optimize the mainclass auto-discovery logic to cover more scenes.
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1185'>SCB-1185</a>] -         Log DNS related exception to help locate problem
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1186'>SCB-1186</a>] -         add a common pom module to simplify user configurations
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1193'>SCB-1193</a>] -         upgread spring boot versions and add easy to use dependency management
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1202'>SCB-1202</a>] -         pump down with vertx3.6.3 no need to check buff length in AsynFileImpl#doWrite
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1205'>SCB-1205</a>] -         improve edge forward http2 request
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1206'>SCB-1206</a>] -         sort schemas in inspector ui
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1208'>SCB-1208</a>] -         improve slow invocation logger: log remote address
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1210'>SCB-1210</a>] -         improve the average latency precision of the metrics log
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1211'>SCB-1211</a>] -         avoid  create multiple caches for different expression of one versionRule 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1220'>SCB-1220</a>] -         Support regex path param on consumer side
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1222'>SCB-1222</a>] -         change groupId of &quot;hibernate-validator&quot; from &quot;org.hibernate&quot; to &quot;org.hibernate.validator&quot;
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1239'>SCB-1239</a>] -         close thread after finish unit test case at once.
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1240'>SCB-1240</a>] -         allowed one prometheus cluster support multiple apps
</li>
</ul>
            
<h2>        Task
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-291'>SCB-291</a>] -         delete old useless configuration mechanism
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-594'>SCB-594</a>] -         Create a document description for https://github.com/apache/incubator-servicecomb-java-chassis/pull/704
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-638'>SCB-638</a>] -         create mechanism for read config item by priority 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1046'>SCB-1046</a>] -         file upload support file array for the same name
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1062'>SCB-1062</a>] -         Update the project development version to 1.2.0-SNAPSHOT
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1083'>SCB-1083</a>] -         support test before provide service
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1134'>SCB-1134</a>] -         change default verticle instance count
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1136'>SCB-1136</a>] -         change default settings of sync executor
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1147'>SCB-1147</a>] -         log invocation stage trace information if too slow
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1148'>SCB-1148</a>] -         read transport configuration from model
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1163'>SCB-1163</a>] -         Support spring-cloud-gateway 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1165'>SCB-1165</a>] -         filter bridge methods when generate swagger
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1184'>SCB-1184</a>] -         upgrade swagger from 1.5.12 to 1.5.22 to support convert swagger to html
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1192'>SCB-1192</a>] -         add &quot;metrics&quot; prefix to slow invocation configuration 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1218'>SCB-1218</a>] -         Prepare 1.2.0 Release
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1221'>SCB-1221</a>] -         add missed modules to distribution and adjust orders
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1231'>SCB-1231</a>] -         add queue meter of http client connection pool 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1232'>SCB-1232</a>] -         make GroupExecutor configuration compatible to old version
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1237'>SCB-1237</a>] -         improve default thread pool strategy
</li>
</ul>
                                                                                                                                        

        Release Notes - Apache ServiceComb - Version java-chassis-1.1.0
    
<h2>        Sub-task
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-493'>SCB-493</a>] -         parameters and DefaultLogPublisher optimize
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-675'>SCB-675</a>] -         generate protobuf idl from swagger
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-681'>SCB-681</a>] -         jackson protobuf support v3 specification: map/list/array
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-687'>SCB-687</a>] -         highway server not accept too many connection
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-691'>SCB-691</a>] -         add vertx server/ rest client/highway client/ highway server connection meter
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-790'>SCB-790</a>] -         support create new target microservice instance in one node
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-793'>SCB-793</a>] -         run it-consumer during travis CI 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-842'>SCB-842</a>] -         jackson protobuf serializer have performance problem
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-843'>SCB-843</a>] -         add http client pool request time to consumer invocation meter
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-881'>SCB-881</a>] -         add more invocation stage measurement
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-894'>SCB-894</a>] -         measure httpServer and httpClient
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-917'>SCB-917</a>] -         parse proto file to model
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-918'>SCB-918</a>] -         serialize/deserialize based on proto model
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-922'>SCB-922</a>] -         collect Getter/Setter from pojo
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-947'>SCB-947</a>] -         delete old jackson protobuf logic
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-948'>SCB-948</a>] -         convert proto model to string
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1001'>SCB-1001</a>] -         [vertx] downloading, client disconnect first, should close WriteStream right now.
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1021'>SCB-1021</a>] -         add vertx client/server meters to metrics
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1022'>SCB-1022</a>] -         measure tcpServer and tcpClient
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1034'>SCB-1034</a>] -         metrics performance optimize
</li>
</ul>
        
<h2>        Bug
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-74'>SCB-74</a>] -         POJO static method is export as an operation
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-381'>SCB-381</a>] -         Fix foudation-vertx UT failure on linux
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-769'>SCB-769</a>] -         When delay fault injection is enabled, the business thread will be blocked 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-774'>SCB-774</a>] -         Unexpected warn log is printed while the service is exiting if there are reactive operations
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-780'>SCB-780</a>] -         sessionstickrule add the judgement of whether lastServer can also be accessed.
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-787'>SCB-787</a>] -         Server States not clean unavailable server
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-794'>SCB-794</a>] -         Edge invocation do not properly send servlet filter response code
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-799'>SCB-799</a>] -         fix problem about &quot;mvn install&quot; in ubuntu
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-800'>SCB-800</a>] -         Param order generated by BeanParamAnnotationProcessor is not stable
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-802'>SCB-802</a>] -         in rollback scenario, old versions meta is used and invocation is fail
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-810'>SCB-810</a>] -         fix zipkin dependency
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-828'>SCB-828</a>] -         In some tomcat implementation inputstream available is null
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-845'>SCB-845</a>] -         some times download file can not get correct content
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-849'>SCB-849</a>] -         refactor producer connection limit using vertx metrics spi mechanism
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-861'>SCB-861</a>] -         lost response type of @ApiResponse 490/590
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-886'>SCB-886</a>] -         Path param is not encoded and decoded correctly
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-888'>SCB-888</a>] -         switch SCBEngine status to up in the wrong time
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-895'>SCB-895</a>] -         When json parse fail will not get 400 but 590
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-898'>SCB-898</a>] -         Governance function is not effective when configuration Start with servicecomb
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-904'>SCB-904</a>] -         SpringMVC @RequestHeader do not support value,only support name
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-905'>SCB-905</a>] -         Request connection is hang up when request path contains illegal string
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-910'>SCB-910</a>] -         Java Chassis support spring boot 2.0
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-956'>SCB-956</a>] -         not support body to be a enum
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-959'>SCB-959</a>] -         When parsing inner classes，CtType will throw NotFoundException
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-960'>SCB-960</a>] -         when consumer local failed(eg: LB failed), CompletableFuture callback can not get InvocationContext
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-964'>SCB-964</a>] -         Fix MediaType setting problem
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-965'>SCB-965</a>] -         resolve DoS attack problem about enum/char/Character/byte/Byte/short/Short/int/Integer/long/Long/float/Float/double/Double
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-972'>SCB-972</a>] -         Using SHA1 signature key as UUID of micro service
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1007'>SCB-1007</a>] -         not support CustomGeneric&lt;Map&lt;KEY, VALUE&gt;&gt;
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1012'>SCB-1012</a>] -         add NoRouteToHostException in retry&#39;s exception
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1014'>SCB-1014</a>] -         Fix priority problem of ExceptionToResponseConverter
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1043'>SCB-1043</a>] -         MicroserviceVersions.safeSetInstances lost exception message
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1045'>SCB-1045</a>] -         fix sample spring bean declaring
</li>
</ul>
        
<h2>        New Feature
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-215'>SCB-215</a>] -         support annotation ApiParam
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-775'>SCB-775</a>] -         support invoke service using raw type like JsonObject
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-777'>SCB-777</a>] -         Support @BeanParam annotation in JAX-RS developing style
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-778'>SCB-778</a>] -         In tomcat, support register swagger base path with container prefix
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-786'>SCB-786</a>] -         when instances cache is not sync to SC caused by bug, auto fix it.
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-788'>SCB-788</a>] -         public key black/white add feature: choose server by microservice field  and properties
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-847'>SCB-847</a>] -         Provide a way to decode user&#39;s custom error data
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-880'>SCB-880</a>] -         Give an option to query parameter convert empty to null
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-903'>SCB-903</a>] -         Add a feature to serialize/deserialize using Object to avoid information lose
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-926'>SCB-926</a>] -         Invoke 3rd party service
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-936'>SCB-936</a>] -         Encoded slash &#39;/&#39; is decoded in EdgeService, causing 404 error response
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-967'>SCB-967</a>] -         support configed ip send request
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1009'>SCB-1009</a>] -         Supporting configure encrypted password for proxy settings
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1040'>SCB-1040</a>] -         Support discover instances from ServiceCenter Aggregator
</li>
</ul>
        
<h2>        Improvement
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-206'>SCB-206</a>] -         Support @Api to specify produces and consumes
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-711'>SCB-711</a>] -         HTTP2 and other client should be lasy initialized 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-747'>SCB-747</a>] -         add jaxrs upload file demo
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-795'>SCB-795</a>] -         update jackson from 2.9.5 to 2.9.6
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-827'>SCB-827</a>] -         Add response decode error log
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-832'>SCB-832</a>] -         modify the errorThresholdPercentage from 20 to 0
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-833'>SCB-833</a>] -         Provide a retry mechanism to meet upgrade no interrupt
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-870'>SCB-870</a>] -         Refractor loadbalancer rule to not use IRule to give more control
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-873'>SCB-873</a>] -         Make the validation result display the parameter name instead of arg0, arg1
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-887'>SCB-887</a>] -         aysnc servlet timeout is too short and may block container pool when tasks are timeout
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-889'>SCB-889</a>] -         add SCBEngine reference to BootEvent
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-897'>SCB-897</a>] -         Support config rest server max initial line length
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-911'>SCB-911</a>] -         Timeout scenario print too many logs
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-931'>SCB-931</a>] -         upgrade vert.x to fix some know issues
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-933'>SCB-933</a>] -         Revert changes to RestObjectMapper that fail on primitive types not present
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-943'>SCB-943</a>] -         make ProduceJsonProcessor,DefaultHttpClientFilter,ServerRestArgsFilter changable
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-954'>SCB-954</a>] -         improve consumer stage time record when failed
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-961'>SCB-961</a>] -         Isolation provide a way to isolate for at least a moment
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-975'>SCB-975</a>] -         Improve retry rule
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-979'>SCB-979</a>] -         Add reminder log on the selection of SwaggerGeneratorContext
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-982'>SCB-982</a>] -         Show the warning message in maven compile plugin
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-985'>SCB-985</a>] -         Add springboot2-starter-discovery
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-986'>SCB-986</a>] -         ServerInstances can be cached in spring-boot2-starter-discovery
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-987'>SCB-987</a>] -         delete spring 3 related declaring
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-989'>SCB-989</a>] -         scan RestController to to make springmvc controller publish as ServiceComb Rest easier
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-996'>SCB-996</a>] -         When retries fail, return the last error
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1020'>SCB-1020</a>] -         No need unregister when bootup failure before register service
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1031'>SCB-1031</a>] -         The Response&#39;s properties was overrided wrong between @APIOperation and @Resoponse on the controller method
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1038'>SCB-1038</a>] -         Fix some bugs and logs improvement reported by users when testing
</li>
</ul>
            
<h2>        Task
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-612'>SCB-612</a>] -         delete useless MicroserviceMetaManager
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-736'>SCB-736</a>] -         generate default value to swagger for primitive type, even there is no defaultValue annotation
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-854'>SCB-854</a>] -         BootListener support load by not only spring bean, but also SPI
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-859'>SCB-859</a>] -         generate traceId when create invocation for consumer/producer/edge
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-882'>SCB-882</a>] -         split mixed integration test case
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-893'>SCB-893</a>] -         measure vertx by vertx metrics mechanism
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-906'>SCB-906</a>] -         add sample for invocation apm by java agent
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-919'>SCB-919</a>] -         generate lambda Getter/Setter from reflect method or field to improve performance
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-920'>SCB-920</a>] -         Remove duplicate dependencies
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-921'>SCB-921</a>] -         check if swagger compatible to protobuf and choose transport automatically
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-928'>SCB-928</a>] -         support swagger &quot;collection-format&quot; feature
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-944'>SCB-944</a>] -         make control IT deploy simpler and print less log
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-957'>SCB-957</a>] -         delete too old protobuf map compatible flag
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-973'>SCB-973</a>] -         TLP graduation tasks
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-992'>SCB-992</a>] -         Synchronous open source code from Vert.x 3.5.3 version
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1023'>SCB-1023</a>] -         switch max connection limitation to metrics mechanism
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-1035'>SCB-1035</a>] -         Update third party licenses for java-chassis
</li>
</ul>
                                                                                                                                        

        Release Notes - Apache ServiceComb - Version java-chassis-1.0.0
            
<h2>        Bug
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-651'>SCB-651</a>] -         QPS rate limit bug
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-662'>SCB-662</a>] -         Using cse/servicecomb duplicate key will get list of values
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-666'>SCB-666</a>] -         Test failure on system that have rotate option set in /etc/resolv.conf
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-696'>SCB-696</a>] -         [AccessLog] If nginx send requests via short-lived connections, %v will print &quot;0.0.0.0&quot;
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-699'>SCB-699</a>] -         add schemaIds field in register.yaml when mock the Local sevice-center
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-703'>SCB-703</a>] -         When consumer invoke void type method in RPC style, an exception is thrown
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-705'>SCB-705</a>] -         When consumer invoke an unregistered provider, it will never find this provider even the provider is registered later
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-753'>SCB-753</a>] -         NPE when query not exists service
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-754'>SCB-754</a>] -         Check null invocation in AbstractRestInvocation to avoid unexpected NPE
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-759'>SCB-759</a>] -         Fix ServiceComb version error
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-772'>SCB-772</a>] -         Java Chassis::Handlers::Loadbalance test failed
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-773'>SCB-773</a>] -         Java Chassis::Core test failed
</li>
</ul>
        
<h2>        New Feature
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-616'>SCB-616</a>] -         Make access log mechanism extensible
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-640'>SCB-640</a>] -         Add black/white list support based on public key handler
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-679'>SCB-679</a>] -         Support Cross-Origin Resource Sharing (CORS)
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-708'>SCB-708</a>] -         Support assembling query param into Object parameter(in Spring MVC developing style)
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-752'>SCB-752</a>] -         User can switch off outputting merged log4j property file
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-760'>SCB-760</a>] -         provide a way to invoke service with full path
</li>
</ul>
        
<h2>        Improvement
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-194'>SCB-194</a>] -         Improve component-scan setting
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-661'>SCB-661</a>] -         Logs improvement to give better information
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-671'>SCB-671</a>] -         Duplicate cse.xxx to servicecomb.xxx to work better in future
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-684'>SCB-684</a>] -         Following swagger conventions
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-685'>SCB-685</a>] -         Service comb chassis must support default values
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-697'>SCB-697</a>] -         Service comb chassis must support JAX-RS @DefaultValue
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-700'>SCB-700</a>] -         Check server status when choose an available server
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-701'>SCB-701</a>] -         RequestBody(required = false) and when requestBody is null then exception observed
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-702'>SCB-702</a>] -         Deleted unwanted json-lib maven dependency for foundation-config
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-706'>SCB-706</a>] -         refactor loadbalance filters logic to support invocation based filter
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-712'>SCB-712</a>] -         Do not register service path to service center when not necessary
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-713'>SCB-713</a>] -         @DefaulValue should be set only when input param is null
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-715'>SCB-715</a>] -         Working in thread that do not have context class loader
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-727'>SCB-727</a>] -         Java Chassis-Local generated schema and service center schema are different while registering the service then print the difference content
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-750'>SCB-750</a>] -         Dependency management is incomplete in Saga and Java-Chassis
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-755'>SCB-755</a>] -         [SCB-755] 755 Duplicate copy cse config to Servicecomb config
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-763'>SCB-763</a>] -         Simplify Dynamic Config (Apollo) Integration Test in Java Chassis
</li>
</ul>
        
<h2>        Wish
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-746'>SCB-746</a>] -         Update Chassis from m1 to m2 in start.servicecomb.io
</li>
</ul>
    
<h2>        Task
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-506'>SCB-506</a>] -         Report the service governance event 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-693'>SCB-693</a>] -         registry microservice failed if get host address failed
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-725'>SCB-725</a>] -         support get main class package when run with &quot;java -jar xxx.jar&quot;
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-726'>SCB-726</a>] -         edge support convert from form-data or x-www-form-urlencoded to json automatically
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-728'>SCB-728</a>] -         add decrypt/signature/... to edge demo
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-729'>SCB-729</a>] -         check if instance cache equals to SC
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-733'>SCB-733</a>] -         open handlerContext for business logic, and add a new name: localContext
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-738'>SCB-738</a>] -         delete microservice from MicroserviceManager after it not exist in SC
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-762'>SCB-762</a>] -         resolve eclipse compile warnings
</li>
</ul>
                                                                                                                                        
                                                                                                                                        

        Release Notes - Apache ServiceComb - Version java-chassis-1.0.0-m2
    
<h2>        Sub-task
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-137'>SCB-137</a>] -         Add new dimension of transport way for all Consumer/Producer
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-196'>SCB-196</a>] -         Add metrics for each consumer/provider handler
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-203'>SCB-203</a>] -         servlet rest support file upload
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-252'>SCB-252</a>] -         Metrics support overwatch Integration
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-370'>SCB-370</a>] -         Metrics timer (like latency) output precision must to nano level not milli level
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-383'>SCB-383</a>] -         metrics subscribe invocation life event and do statistics
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-384'>SCB-384</a>] -         provide invocation performance log publisher
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-385'>SCB-385</a>] -         metrics publisher switch to new mechanism
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-422'>SCB-422</a>] -         add executor metrics, not just queue size
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-440'>SCB-440</a>] -         Provide Maven Archetype of business-service-pojo
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-441'>SCB-441</a>] -         Provide Maven Archetype of business-service-jaxrs
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-442'>SCB-442</a>] -         Provide Maven Archetype of business-service-springmvc
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-445'>SCB-445</a>] -         delete old metrics mechanism
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-446'>SCB-446</a>] -         metrics-prometheus switch to new mechanism
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-450'>SCB-450</a>] -         documents for metrics initializer/publisher, and how to extend
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-462'>SCB-462</a>] -         cloud eye publisher switch to new mechanism
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-470'>SCB-470</a>] -         Provide Maven Archetype of business-service-spring-boot-starter
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-484'>SCB-484</a>] -         servlet rest support download
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-485'>SCB-485</a>] -         jaxrs mode support file download
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-486'>SCB-486</a>] -         edge support route file download invocation
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-487'>SCB-487</a>] -         consumer support download file
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-494'>SCB-494</a>] -         support delete temp file after download
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-501'>SCB-501</a>] -         document for download
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-527'>SCB-527</a>] -         Reorganization All Archetype For Enable Auto Publish
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-529'>SCB-529</a>] -         producer download file from byte[]
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-531'>SCB-531</a>] -         x-java-interface change from require to optional
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-532'>SCB-532</a>] -         support recursive dependence
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-533'>SCB-533</a>] -         javassistUtils create class from CtClass, not only JavaType
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-534'>SCB-534</a>] -         generic class generate optimize
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-538'>SCB-538</a>] -         create SwaggerToClassGenerator to convert swagger to class
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-540'>SCB-540</a>] -         Delete archetypes from java-chassis-dependencies
</li>
</ul>
        
<h2>        Bug
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-72'>SCB-72</a>] -         Can isolation information of provider and consumer been discovered through capability of release and subscription?
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-449'>SCB-449</a>] -         Typo in LICENSE
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-455'>SCB-455</a>] -         Base on 1.0.0-m2-SNAPSHOT version, execution of the metrics UT failed 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-474'>SCB-474</a>] -         使用zuul做网关进行路由，当同一个微服务接口同时开放rest和highway方式时，出现无法调用情况。
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-481'>SCB-481</a>] -         Fix qps handler assertion errors when schemaid or microservice name contails . (dot)
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-490'>SCB-490</a>] -         Service Center verrsion is not forward compatible and needs to be noted in releasenote.
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-495'>SCB-495</a>] -         Compile java-chassis 1.0.0-m2-SNAPSHOT failed
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-502'>SCB-502</a>] -         logs日志没有输出
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-503'>SCB-503</a>] -         When using WeighedResponseTimeRule, there are some initialize and stateless access problems
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-507'>SCB-507</a>] -         poll task in MetricsBootstrap did not really measure meters
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-512'>SCB-512</a>] -         download support chinese file name
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-516'>SCB-516</a>] -         AccessLog of EdgeService does not print traceId
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-520'>SCB-520</a>] -         resolve service with env re-registered will fail
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-521'>SCB-521</a>] -         change the priority of ServiceComb config and SpringBoot config
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-562'>SCB-562</a>] -         Java Chassis will throw NPE when producer impl do not contain any method
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-567'>SCB-567</a>] -         treat warning as errors, modify the compilerArgments
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-579'>SCB-579</a>] -         NullPointerException is thrown when consumer upload null
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-580'>SCB-580</a>] -         When upload file size exceeds limitation of provider, consumer will return a confusing response
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-587'>SCB-587</a>] -         Fix archetypes readme
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-588'>SCB-588</a>] -         Set archetypes sourceEncoding to UTF-8
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-591'>SCB-591</a>] -         configcenter need to do encode
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-593'>SCB-593</a>] -         Change log level to remind user to specify loadbalance handler
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-597'>SCB-597</a>] -         update spring boot version from 1.4.5 to 1.5.12 in starter archetype
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-617'>SCB-617</a>] -         graceful shutdown with standalone tomcat
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-652'>SCB-652</a>] -         Fix schema registry environment configuration
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-653'>SCB-653</a>] -         When provider returns Transfer-Encoding header and Edge will cause problem
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-654'>SCB-654</a>] -         DiscoveryTree has concurrency problems.
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-656'>SCB-656</a>] -         When provider returns non 200 code Edge Service will all convert to 502
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-658'>SCB-658</a>] -         leak of MicroserviceVersions register to EventBus
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-659'>SCB-659</a>] -         Fix build failed in Springmvc Integration Test
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-667'>SCB-667</a>] -         gracefully shutdown is not work in some case
</li>
</ul>
        
<h2>        New Feature
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-6'>SCB-6</a>] -         ServiceComb Java Chassis Metrics
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-136'>SCB-136</a>] -         Improvement and New Features of Java Chassis Metrics in version 1.0.0-m2
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-201'>SCB-201</a>] -         As a SDK user, I want to send file/stream data so that I can use ServiceComb to handle the music or image data
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-257'>SCB-257</a>] -         As a developer, I want to download file from microservice
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-292'>SCB-292</a>] -         As a developer, I want to use annotation to validate input parameter
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-406'>SCB-406</a>] -         Chassis must support standard parameter validation handler
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-439'>SCB-439</a>] -         Provide Maven Archetypes in Java Chassis
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-482'>SCB-482</a>] -         Http2 support for java chassis
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-582'>SCB-582</a>] -         Provide a way to protection for instance removal
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-607'>SCB-607</a>] -         Support printing invocation context in access log
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-611'>SCB-611</a>] -         Provide a default Edge service dispatcher to make developer edge easy
</li>
</ul>
        
<h2>        Improvement
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-350'>SCB-350</a>] -         Vertx ssl file config error execption approvement
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-355'>SCB-355</a>] -         As a operator, when sdk config a fault ak/sk on HuaweiCloud, then will auth token fail, but it continues to register, will cause may fault in server
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-373'>SCB-373</a>] -         As a developer, i want to do something around serialize/deserialize, so that we should make a  aspect to eanable others can do this work
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-431'>SCB-431</a>] -         Add Rat check on the travis CI
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-444'>SCB-444</a>] -         try to optimize autodiscovery function
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-447'>SCB-447</a>] -         optimize SPIServiceUtils to avoid get different instance for the same type
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-467'>SCB-467</a>] -         Contributing &amp; Reporting Issues in java-chassis README.md is not direct to any contents
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-477'>SCB-477</a>] -         sdk guava‘s version need to update from 16.0.1 to 19.0
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-488'>SCB-488</a>] -         Retry/Metrics some default behavior cause unnecessary retry and logs
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-498'>SCB-498</a>] -         Configuration Center IP Addresses need to meet general specifications
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-514'>SCB-514</a>] -         update pom and code, so that we can treat warnings as errors
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-517'>SCB-517</a>] -         service center starter for spring boot/cloud improvement
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-518'>SCB-518</a>] -         ServiceCenter ip address need to config default port
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-523'>SCB-523</a>] -         maven-remote-resource-plugin execute very slow
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-526'>SCB-526</a>] -         When creating dynamic configuration, we need to fetch once for the configuration when startup
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-543'>SCB-543</a>] -         optimize registry procedure
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-546'>SCB-546</a>] -         As a developer, want to reregistry schemas in the dev environment
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-548'>SCB-548</a>] -         Support Gracefully Shutdown
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-570'>SCB-570</a>] -         reformat  everything
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-575'>SCB-575</a>] -         Publish the Java doc of ServiceComb projects
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-576'>SCB-576</a>] -         javassist License file need to be updated
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-585'>SCB-585</a>] -         Add ServiceComb-java-chassis reference guide to project
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-625'>SCB-625</a>] -         ProduceProcessor use SPI to support extends
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-627'>SCB-627</a>] -         Java Chassis- Client Request Timeout support for operation/schema/service level
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-636'>SCB-636</a>] -         As a OM staff, i want to use the lb endpoint as the servicecenter/configcenter address config
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-646'>SCB-646</a>] -         if local swagger exists, not generate swagger according to class
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-649'>SCB-649</a>] -         when port can&#39;t been listened,log warn and show more detail message
</li>
</ul>
        
<h2>        Wish
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-504'>SCB-504</a>] -         Upgrade to Spring boot 1.5.12.RELEASE
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-515'>SCB-515</a>] -          change all configuration from &#39;cse.xxx&#39; to &#39;servicecomb.xxx&#39;
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-672'>SCB-672</a>] -         Edge Service support calls from different ApplicationIds
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-673'>SCB-673</a>] -         Edge Service support calls from different ApplicationIds
</li>
</ul>
    
<h2>        Task
</h2>
<ul>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-324'>SCB-324</a>] -         Chassis must support network failure simulation, so that I can developers can enhance the robustness of the app
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-352'>SCB-352</a>] -         Support operation level flow control on provider side
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-354'>SCB-354</a>] -         metrics上报的统计数据可能需要支持加上业务自己的维度，方便统计分析，比如APP版本，机型等，业务可以把参数作为invocation参数传递到框架，需要框架支持
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-420'>SCB-420</a>] -         Change default HTTP header length restriction to 32K
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-424'>SCB-424</a>] -         Get configuration interface to add header: x-environment
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-443'>SCB-443</a>] -         Fix randomly UT failure of TestProviderQpsFlowControlHandler
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-453'>SCB-453</a>] -         Read configuration from application.yml/application.properties
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-456'>SCB-456</a>] -         Provider a way to input configuration from a Map, instead of  micreservice.yaml
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-457'>SCB-457</a>] -         Verify if gradle can manage the ServiceComb java Chassis jars in a remote or local maven repository
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-471'>SCB-471</a>] -         vertx upgrade causes use config center push mode error 
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-542'>SCB-542</a>] -         Update netty&#39;s version to 4.1.24
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-589'>SCB-589</a>] -         allow consumer upgrade before producer
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-590'>SCB-590</a>] -         Update the validator version to latest(6.0.2)
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-595'>SCB-595</a>] -         Compatible with old SC versions
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-599'>SCB-599</a>] -         Service registry failed when service before Service Center start
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-601'>SCB-601</a>] -         ServiceComb integrated to spring boot or tomcat will print too many logs
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-637'>SCB-637</a>] -         enhance HttpServletRequestEx impl
</li>
<li>[<a href='https://issues.apache.org/jira/browse/SCB-647'>SCB-647</a>] -         Update LICENSE/NOTICE for release
</li>
</ul>
                                                                                                                                    
                                                                                                                                    
        Release Notes - Apache ServiceComb - Version Java-Chassis-1.0.0-m1
    

### Major improvements:

 - Java Chassis can now use Apollo as configuration center. Users can now
change configurations like load balancing policy and those changes will
come into effect on the fly.
See [here](http://servicecomb.incubator.apache.org/users/dynamic-config/) for more
details.

 - Metrics was re-factored. We now uses events for collecting invocation data
instead of Hystrix. This reduces the performance penalty of computing
metrics.
Metrics can now be fetched via '/metrics' using HTTP.
See [here](http://servicecomb.incubator.apache.org/users/metrics-in-1.0.0-m1/) for
more details.

### Other Noticeable Changes:

- The Java Chassis libraries are now under group "org.apache.servicecomb".
- We provide out of the box metrics support now. Prometheus is supported.
- Configuration center was re-factored and moved out from foundation.
Support for Apollo was added.
- Users can now use Object type for calling services.
- Users can now use Generics for calling services.
- Better integration with Spring MVC.
- Upgraded to zipkin2 internally, Java Chassis can now work with zipkin
server v1 and v2.
- We are in the process of supporting reactive programming. Pojo consumer
and provider now supports CompletableFuture.

### For more detailed information please checkout [here](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12321626&version=12342351)

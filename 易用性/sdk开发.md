## sdk开发

sdk是提升产品易用性的一种直接方式,通过包引用的方式,就可以直接支持用户使用.

### nacos-client sdk分析

依赖包:

slf4j-api optional    
log4j-core optional    
log4j-api optional    
log4j-slf4j-impl optional    
logback-classic optional    
nacos-common
nacos-api
commons-codec
jackson-core
jackson-databind
httpasyncclient
reflections
jcip-annotations
io.prometheus.simpleclient
snakeyaml

测试:
junit
mockito-core
mockito-inline



包结构

api    
client
common
shaded



































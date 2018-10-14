# first-app
starocto begin on 10.02


-------------- 微博小工程的模块说明

commonapi	:	前端api公共接口，负责页面逻辑

dao	:	数据库访问通道，对数据库表单的增删改查，内部包含两个服务：读服务 & 写服务

cache	：	缓存，针对commonapi的数据获取操作提供缓存机制，减少直接对dao的访问压力

mq	：	消息队列，针对commonapi的数据存储操作提供异步写入的机制

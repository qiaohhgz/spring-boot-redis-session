# spring-boot-redis-session
分布式项目session内容共享到redis中

主要实现了spring提供的ExpiringSession, SessionRepository, HttpSessionStrategy 接口
- WxHttpSessionStrategy
- WxRedisSession
- WxRedisSessionRepository

配置到spring boot项目中
- HttpSessionConfig
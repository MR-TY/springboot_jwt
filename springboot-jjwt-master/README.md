# springboot-jwt
SpringBoot集成JWT实现token验证
 
##### 总结：在 web 应用中，使用 jwt 代替 session 存在不小的风险，绝大多数情况下，传统的 cookie-session 机制工作得更好。jwt 适合做简单的 restful api 认证，颁发一个固定有效期的 jwt，降低 jwt 暴露的风险，不要对 jwt 做服务端的状态管理，这样才能体现出 jwt 无状态的优势。
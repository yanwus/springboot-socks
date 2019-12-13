### 无法找到repository组件解决办法
```java
@ComponentScan({"repo", "pojo", "service"}) // 1. 多模块项目需要扫描的包
@EnableJpaRepositories("repo") // 2. Dao 层所在的包
@EntityScan("pojo") // 3. Entity 所在的包.
```

## 通过注解来实现方法拦截耗时打印

1.  通过本项目可以实践Spring Boot Starter 最佳实践。
2.  我们描述Starter的原理，以及如何开发一个Starter的步骤。

## Spring Starter 原理
1. Spring Boot在启动时扫码项目所依赖Jar包，寻找包含spring.factories文件的Jar包
2. 根据spring.factories 配置加载AutoConfigure类
3. 根据@Conditional 注解条件，进行自动配置并将Bean 注入Spring Context

## 详细原理与实现
可以参见我的公众号文章
# 目标：整合常用的开源项目作为.NET互联网公司的解决方案
# 任务
## 1、收集常见的.NET开源项目
## 2、根据开源项目规划功能
* 参考：https://www.oschina.net/project/lang/194/csharp
* 强烈推荐：偏互联网方向 https://blog.csdn.net/qq_27825451/article/details/70666044
* 传统应用方向 https://www.cnblogs.com/TXSH/p/4442106.html
* 监控之类的 https://www.jianshu.com/p/14fc79fb1d13
## 3、统计分类，筛选出我们需要的。
# 2019-01-22
## 暂定目标：
* 1.生命周期管理。（比如说管理Service等生命周期）
* ~~2.连接池管理。（dapper连接池管理，连接生命周期等，异步时连接池管理的问题。）~~
* 3.配置文件默认json格式。（后续可能支持yaml格式。）
* 4.依赖注入（单列，每次都生成新的等)
* 5.ioc框架使用autofac.(扩展支持Ninject)
* 6.配置读取方式使用 **特性** 。

### 参考
#### yaml 
    http://www.cnblogs.com/shanyou/p/4733267.html
    https://blog.csdn.net/sD7O95O/article/details/78096321

#### core
    https://blog.csdn.net/sD7O95O/article/details/78700937
#### Ninject
    https://blog.csdn.net/simpkan/article/details/8169740
#### 特性
    https://docs.microsoft.com/zh-cn/dotnet/csharp/programming-guide/concepts/attributes/index
#### 创建自定义特性
    https://docs.microsoft.com/zh-cn/dotnet/csharp/programming-guide/concepts/attributes/creating-custom-attributes

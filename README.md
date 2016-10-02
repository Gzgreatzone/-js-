# -js-
前一阵子，猛补了一下算法
关于angular的问题：servic factory provider 的区别。
总结
所有的供应商都只被实例化一次，也就说他们都是单例的
除了constant，所有的供应商都可以被装饰器(decorator)装饰
value就是一个简单的可注入的值
service是一个可注入的构造器
factory是一个可注入的方法
decorator可以修改或封装其他的供应商，当然除了constant
provider是一个可配置的factory

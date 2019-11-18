## ES 2015/2016 编程实战

> 当前项目源码来自ES 2015/2016 编程实战这本书，自己增加了一些注释和个人理解

- `babel`命令必须安装babel-cli才能使用，当前项目是局部安装，不是全局安装。所以在`package.json`中的`scripts`执行测试脚本`babel src -d dist`。注意`browserify`同理，但要注意**@babel/core**升级后，相关的包都是`@babel/`为前缀
# NONA
基于Q-lisp语法的逻辑门编辑器

## 交互部分
大致就是C程里面xxxx管理系统里面那个交互界面,也提供直接输入Q-lisp语句的功能,感觉这个东西不会很难,如果以后有兴趣的话,用Qt之类的东西把它弄得好看一些,整个IDE(但就我的前端水平来说,做梦...)
## 解释部分
可以把之前写的Q-lisp解释器挂几个函数直接拿来用(大概需要好好修缮一下,里面代码还是有点傻的),日后或许可以把逻辑门部分做成Q-lisp的一个库(import nano)
## 运行部分
要用C来重构Re-NANO的代码,但是实在不想搞个ReRe,于是直接就叫NANO了,写这种比较底层的东西,果然还是C比较好用.

### 对逻辑门电路的抽象
- 端口:可以被修改的,只有两个值的变量
- 元件:连接着若干个出口,若干个入口,入口出口都是端口,根据入口的值来修改出口的值





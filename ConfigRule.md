## 基本概念 ##

> 规则是为了完成复杂的业务逻辑而引入的概念。 规则的主体是定义一个有执行条件的服务。

> 规则的执行需要依附于服务。服务只有被完全执行（[服务的完全执行](http://code.google.com/p/eeplat/wiki/ConfigService#%E6%9C%8D%E5%8A%A1%E7%9A%84%E6%89%A7%E8%A1%8C)）时才执行服务所定义的规则。

> 规则有执行优先级，当多个规则执行时，优先级越高（即阿拉伯数字越大）执行的顺序越靠前。

> 规则可以定义在服务前执行，也可以定义在服务后执行。




## 对应JAVA 数据类型 ##
> com.exedosoft.plat.bo.DORule

## 配置界面 ##

> 参加服务的“规则定义”及“生成规则”
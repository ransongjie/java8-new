# 总述
func_interface: 函数式接口
lambda: lambda表达式
func_reference: 方法引用
stream: 流式编程
interface_default_func: 接口默认方法
datetime: 日期时间
base64: base64编码解码
optional: null处理


# 函数式编程
方法作为入参，函数式接口 作为方法入参，lambda表达式作函数式接口中抽象方法的方法体
func_interface: 函数式接口，interface上标注@FunctionalInterface
lambda: lambda表达式，作为 函数式接口 中 抽象方法 的方法体
func_reference: 方法引用

函数式接口，lambda表达式，lambda表达式所在类
- lambda表达式是 函数式接口 的实现类
- lambda表达式是 lambda表达式所在类 的内部类
- lambda表达式等号右边是 函数式接口中的 抽象方法 的实现
- 传入lambda表达式的变量 必须是final或effectively final

函数式接口，lambda表达式，方法引用
- 方法引用，引用方法
- 引用已有方法 避免自己写lambda表达式，使得代码更加紧凑
- 方法引用，双冒号::

# 流式编程

# 接口优化
interface_default_func: 接口默认方法

# 日期时间优化
datetime: 日期时间

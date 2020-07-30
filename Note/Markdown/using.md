### **uisng , typedef ,define**区别

#### using新类型的声明：

在我们定义一个常指针常量的变量的时候会输入：const int \* const p 很明显这里会输入很长的一段代码；

在C中，可以使用：typedef const int\* const MyCCP 

​			这里要注意与define进行区分，define的使用方法是：

​			#define PI 3.14 也就是 #define MACROT something

​			typedef const int\* const MyCCP 也就是：typedef Some type NewTypeName

一言蔽之就是：两者定义的位置相反

但是在C++中，引入using就变得显而易见。

例如上面的：	typedef const int\* const MyCCP。

就可以写成：	using MyCCP = const int \* const 

 但是在using中不能使用：using in = std::cin ，是因为using的表达式只能是类型，不能是一个对象！




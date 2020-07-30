## **C++ Class（类）**

**class -》objects**

**对象是类的实例化**

#### **类的特点：**

类是一种数据类型

- **封装 Encapsulation**
- **继承 Inheritance**
- **多态 Polymorphis**

#### **类的构成：**

- **数据域（data field）By 变量（ variable）**
- **行为（behavior ） By 函数(Function)**
- **特殊的两种函数**
  - **构造函数 constructors ：创建对象时，被自动调用**
    - **当类中不含有构造函数时，编译器会自己的创建一个`默认构函数（default constructors）`**
  - **析构函数 destructors ：对象被销毁时，被自动调用**

#### **类的用法**

```cpp
#include <iostream>
using std::cin;
using std::cout;
using std::endl;
class Circle {
public:
	double radius;
	Circle() {
		radius = 1.0;
	}
	Circle(double r) {
		radius = r;
	}
	double getArea() {
		return (3.14 * radius * radius);
	}
};

int main() {
	Circle c1;
	Circle c2{ 2.0 };
	cout << c1.getArea() << endl;
	cout << c2.getArea() << endl;
	return 0;
}
```

#### **类的成员关系**

- public关系，类中的成员可以被访问

- private关系，成员仅仅允许类内部进行访问

  
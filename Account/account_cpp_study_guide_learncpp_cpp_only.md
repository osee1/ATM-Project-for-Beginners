# Account 模块补充学习地图（再排除 C 语言通用知识点）

## 1. 这份文档的前提

这份版本是在前一版基础上继续过滤后的结果，默认你已经具备：

- 菜鸟教程里你截图中的那部分基础内容
- 大约 1 年 C 语言开发经验

所以这份文档会继续滤掉这些 **更偏 C / C++ 共通** 的知识点：

- 多文件项目的基本拆分思路
- `#include`、预处理器、头文件保护这种基础工程知识
- 基本变量、判断、循环、函数、数组
- 一般性的输入校验思路

保留下来的内容，基本都是你读这个 `Account` 模块时真正容易卡住的 **C++ 特有知识点**。

## 2. 现在最值得你补的教程

- LearnCpp 首页：<https://www.learncpp.com/>
- LearnCpp 教程目录：<https://www.learncpp.com/cpp-tutorial/>

## 3. 过滤后，你真正还需要补的 LearnCpp 章节

1. Chapter 2.9 [`Naming collisions and an introduction to namespaces`]<https://www.learncpp.com/cpp-tutorial/naming-collisions-and-an-introduction-to-namespaces/>
2. Chapter 10.4 [`Narrowing conversions, list initialization, and constexpr initializers`]<https://www.learncpp.com/cpp-tutorial/narrowing-conversions-list-initialization-and-constexpr-initializers/>
3. Chapter 10.8 [`Type deduction for objects using the auto keyword`]<https://www.learncpp.com/cpp-tutorial/type-deduction-for-objects-using-the-auto-keyword/>
4. Chapter 12.15 [`std::optional`]<https://www.learncpp.com/cpp-tutorial/stdoptional/>
5. Chapter 14.1 [`Introduction to object-oriented programming`]<https://www.learncpp.com/cpp-tutorial/introduction-to-object-oriented-programming/>
6. Chapter 14.2 [`Introduction to classes`]<https://www.learncpp.com/cpp-tutorial/introduction-to-classes/>
7. Chapter 14.3 [`Member functions`]<https://www.learncpp.com/cpp-tutorial/member-functions/>
8. Chapter 14.4 [`Const class objects and const member functions`]<https://www.learncpp.com/cpp-tutorial/const-class-objects-and-const-member-functions/>
9. Chapter 14.5 [`Public and private members and access specifiers`]<https://www.learncpp.com/cpp-tutorial/public-and-private-members-and-access-specifiers/>
10. Chapter 14.6 [`Access functions`]<https://www.learncpp.com/cpp-tutorial/access-functions/>
11. Chapter 14.8 [`The benefits of data hiding <encapsulation>`]<https://www.learncpp.com/cpp-tutorial/the-benefits-of-data-hiding-encapsulation/>
12. Chapter 14.9 [`Introduction to constructors`]<https://www.learncpp.com/cpp-tutorial/introduction-to-constructors/>
13. Chapter 14.10 [`Constructor member initializer lists`]<https://www.learncpp.com/cpp-tutorial/constructor-member-initializer-lists/>
14. Chapter 15.4 [`Introduction to destructors`]<https://www.learncpp.com/cpp-tutorial/introduction-to-destructors/>
15. Chapter 16.8 [`Range-based for loops <for-each>`]<https://www.learncpp.com/cpp-tutorial/range-based-for-loops-for-each/>
16. Chapter 24.1 [`Introduction to inheritance`]<https://www.learncpp.com/cpp-tutorial/introduction-to-inheritance/>
17. Chapter 24.2 [`Basic inheritance in C++`]<https://www.learncpp.com/cpp-tutorial/basic-inheritance-in-c/>
18. Chapter 24.5 [`Inheritance and access specifiers`]<https://www.learncpp.com/cpp-tutorial/inheritance-and-access-specifiers/>
19. Chapter 25.2 [`Virtual functions and polymorphism`]<https://www.learncpp.com/cpp-tutorial/virtual-functions/>
20. Chapter 25.3 [`The override and final specifiers, and covariant return types`]<https://www.learncpp.com/cpp-tutorial/the-override-and-final-specifiers-and-covariant-return-types/>
21. Chapter 25.7 [`Pure virtual functions, abstract base classes, and interface classes`]<https://www.learncpp.com/cpp-tutorial/pure-virtual-functions-abstract-base-classes-and-interface-classes/>
22. Chapter 28.3 [`Output with ostream and ios`]<https://www.learncpp.com/cpp-tutorial/output-with-ostream-and-ios/>
23. Chapter 28.4 [`Stream classes for strings`]<https://www.learncpp.com/cpp-tutorial/stream-classes-for-strings/>

## 4. 如果你时间有限，先学这 8 个

1. Chapter 12.15 [`std::optional`]<https://www.learncpp.com/cpp-tutorial/stdoptional/>
2. Chapter 14.2 [`Introduction to classes`]<https://www.learncpp.com/cpp-tutorial/introduction-to-classes/>
3. Chapter 14.4 [`Const class objects and const member functions`]<https://www.learncpp.com/cpp-tutorial/const-class-objects-and-const-member-functions/>
4. Chapter 14.9 [`Introduction to constructors`]<https://www.learncpp.com/cpp-tutorial/introduction-to-constructors/>
5. Chapter 14.10 [`Constructor member initializer lists`]<https://www.learncpp.com/cpp-tutorial/constructor-member-initializer-lists/>
6. Chapter 24.1 [`Introduction to inheritance`]<https://www.learncpp.com/cpp-tutorial/introduction-to-inheritance/>
7. Chapter 25.2 [`Virtual functions and polymorphism`]<https://www.learncpp.com/cpp-tutorial/virtual-functions/>
8. Chapter 25.7 [`Pure virtual functions, abstract base classes, and interface classes`]<https://www.learncpp.com/cpp-tutorial/pure-virtual-functions-abstract-base-classes-and-interface-classes/>

## 5. 这些是 C 语言经验不能直接覆盖的点

1. 命名空间  
代码例子：`std::string`、`std::cout`  
为什么要补：C 没有 `std::` 这套命名空间体系  
对应章节：2.9 `Naming collisions and an introduction to namespaces`

2. 花括号初始化和 `constexpr`  
代码例子：`m_balance{0.0}`、`m_transactions{}`、`constexpr float fast_cash_options[4]`  
为什么要补：这不是传统 C 风格初始化，`constexpr` 也不是普通 `const`  
对应章节：10.4 `Narrowing conversions, list initialization, and constexpr initializers`

3. `auto` 类型推导  
代码例子：`const auto &transaction`  
为什么要补：C 没有这种现代 C++ 的对象类型推导用法  
对应章节：10.8 `Type deduction for objects using the auto keyword`

4. `std::optional`  
代码例子：`std::optional<int> m_PIN;`  
为什么要补：这是 C++ 标准库里“可能有值，也可能没值”的对象封装  
对应章节：12.15 `std::optional`

5. 类与对象  
代码例子：`class Account`  
为什么要补：这是整个 `Account` 模块最核心的 C++ 知识  
对应章节：14.1 `Introduction to object-oriented programming`、14.2 `Introduction to classes`

6. 成员函数与 `const` 成员函数  
代码例子：`Account::CreatePIN()`、`bool Authenticate() const`  
为什么要补：C 函数没有“属于对象”的概念，也没有成员函数 `const` 语义  
对应章节：14.3 `Member functions`、14.4 `Const class objects and const member functions`

7. `public` / `private` / 封装  
代码例子：`public:`、`private:`、getter / setter  
为什么要补：这是 C 结构体思维到 C++ 封装思维最关键的跨越  
对应章节：14.5 `Public and private members and access specifiers`、14.6 `Access functions`、14.8 `The benefits of data hiding (encapsulation)`

8. 构造函数、成员初始化列表、析构函数  
代码例子：`Account(...)`、`: m_first_name{first_name}, ...`、`~Account() = default;`  
为什么要补：对象创建和销毁机制是 C 语言里没有的核心能力  
对应章节：14.9 `Introduction to constructors`、14.10 `Constructor member initializer lists`、15.4 `Introduction to destructors`

9. 范围 `for`  
代码例子：`for (const auto &transaction : m_transactions)`  
为什么要补：这不是 C 风格 `for`，而是 C++ 容器遍历语法  
对应章节：16.8 `Range-based for loops (for-each)`

10. 继承  
代码例子：`class Account : public IAccount`  
为什么要补：C 没有类继承体系  
对应章节：24.1 `Introduction to inheritance`、24.2 `Basic inheritance in C++`、24.5 `Inheritance and access specifiers`

11. 虚函数、多态、`override`  
代码例子：`virtual void CreatePIN()`、`override`  
为什么要补：这是接口调用能落到子类实现上的关键  
对应章节：25.2 `Virtual functions and polymorphism`、25.3 `The override and final specifiers, and covariant return types`

12. 纯虚函数、抽象类、接口  
代码例子：`virtual void CreatePIN() = 0;`、`class IAccount`  
为什么要补：这是你读懂 `IAccount.h` 的关键  
对应章节：25.7 `Pure virtual functions, abstract base classes, and interface classes`

13. `iostream` 的格式控制  
代码例子：`std::fixed`、`std::setprecision(2)`、`std::flush`  
为什么要补：这已经不是 C 的 `printf` / `scanf` 思路了  
对应章节：28.3 `Output with ostream and ios`

14. `stringstream`  
代码例子：`std::stringstream stream;`  
为什么要补：这是 C++ 风格的字符串流，不是 C 风格字符串处理  
对应章节：28.4 `Stream classes for strings`

## 6. 对你现在这个项目，建议按这个顺序读代码

1. 先读 `IAccount.h`  
先补：25.7、25.2、24.1

2. 再读 `Account.h`  
先补：14.2、14.4、14.5、14.9、14.10、12.15

3. 最后读 `Account.cpp`  
先补：28.4、28.3、16.8、10.8、10.4

## 7. 可以先不急着补的点

即使你是 C 开发者，下面这些在当前 `Account` 模块里也不是最先要深挖的：

- `std::chrono`
- `std::this_thread::sleep_for`
- 更完整的流状态恢复细节

先把类、继承、虚函数、`optional`、构造函数、成员初始化列表吃透，收益最大。

## 8. 参考来源

- LearnCpp 首页：<https://www.learncpp.com/>
- LearnCpp 教程目录：<https://www.learncpp.com/cpp-tutorial/>
- `std::optional`：<https://www.learncpp.com/cpp-tutorial/stdoptional/>
- `Introduction to classes`：<https://www.learncpp.com/cpp-tutorial/introduction-to-classes/>
- `Constructor member initializer lists`：<https://www.learncpp.com/cpp-tutorial/constructor-member-initializer-lists/>
- `Virtual functions`：<https://www.learncpp.com/cpp-tutorial/virtual-functions/>
- `Pure virtual functions, abstract base classes, and interface classes`：<https://www.learncpp.com/cpp-tutorial/pure-virtual-functions-abstract-base-classes-and-interface-classes/>

# Account 模块补充学习地图（排除你已学过的菜鸟教程部分）

## 1. 这份文档的前提

我把你截图里这些菜鸟教程章节视为 **已经学过**，所以这里不再重复：

- `C++ 简介`
- `C++ 环境设置`
- `C++ AI 编程助手`
- `C++ 基本语法`
- `C++ 注释`
- `C++ 数据类型`
- `C++ 变量类型`
- `C++ 变量作用域`
- `C++ 常量`
- `C++ 修饰符类型`
- `C++ 存储类`
- `C++ 运算符`
- `C++ 循环`
- `C++ 判断`
- `C++ 函数`
- `C++ 数字`
- `C++ 数组`
- `C++ 字符串`
- `C++ 指针`
- `C++ 引用`
- `C++ 日期 & 时间`
- `C++ 基本的输入输出`
- `C++ 结构体(struct)`
- `C++ vector 容器`
- `C++ 数据结构`

所以这份清单只保留一件事：  
**为了读懂 `Account` 目录这 3 个文件，你还需要在 LearnCpp 里补哪些知识。**

## 2. 我推荐你现在重点补的教程

- LearnCpp 首页：<https://www.learncpp.com/>
- LearnCpp 教程目录：<https://www.learncpp.com/cpp-tutorial/>

## 3. 这个 Account 模块里，你还没补齐的重点知识

按重要程度，我建议你补下面这几组内容：

1. 多文件项目、头文件、预处理器、命名空间
2. 类、对象、访问控制、构造函数、析构函数
3. 继承、虚函数、接口、抽象类、多态
4. `std::optional`、`auto`、`constexpr`、成员初始化列表
5. 更进阶一点的输入校验、输出格式化、字符串流

## 4. 建议你的学习顺序

这是我按你当前项目需要，过滤后的 LearnCpp 学习顺序：

1. Chapter 2.8 [`Programs with multiple code files`]<https://www.learncpp.com/cpp-tutorial/programs-with-multiple-code-files/>
2. Chapter 2.9 [`Naming collisions and an introduction to namespaces`]<https://www.learncpp.com/cpp-tutorial/naming-collisions-and-an-introduction-to-namespaces/>
3. Chapter 2.10 [`Introduction to the preprocessor`]<https://www.learncpp.com/cpp-tutorial/introduction-to-the-preprocessor/>
4. Chapter 2.11 [`Header files`]<https://www.learncpp.com/cpp-tutorial/header-files/>
5. Chapter 2.12 [`Header guards`]<https://www.learncpp.com/cpp-tutorial/header-guards/>
6. Chapter 10.4 [`Narrowing conversions, list initialization, and constexpr initializers`]<https://www.learncpp.com/cpp-tutorial/narrowing-conversions-list-initialization-and-constexpr-initializers/>
7. Chapter 10.8 [`Type deduction for objects using the auto keyword`]<https://www.learncpp.com/cpp-tutorial/type-deduction-for-objects-using-the-auto-keyword/>
8. Chapter 12.15 [`std::optional`]<https://www.learncpp.com/cpp-tutorial/stdoptional/>
9. Chapter 14.1 [`Introduction to object-oriented programming`]<https://www.learncpp.com/cpp-tutorial/introduction-to-object-oriented-programming/>
10. Chapter 14.2 [`Introduction to classes`]<https://www.learncpp.com/cpp-tutorial/introduction-to-classes/>
11. Chapter 14.3 [`Member functions`]<https://www.learncpp.com/cpp-tutorial/member-functions/>
12. Chapter 14.4 [`Const class objects and const member functions`]<https://www.learncpp.com/cpp-tutorial/const-class-objects-and-const-member-functions/>
13. Chapter 14.5 [`Public and private members and access specifiers`]<https://www.learncpp.com/cpp-tutorial/public-and-private-members-and-access-specifiers/>
14. Chapter 14.6 [`Access functions`]<https://www.learncpp.com/cpp-tutorial/access-functions/>
15. Chapter 14.8 [`The benefits of data hiding <encapsulation>`]<https://www.learncpp.com/cpp-tutorial/the-benefits-of-data-hiding-encapsulation/>
16. Chapter 14.9 [`Introduction to constructors`]<https://www.learncpp.com/cpp-tutorial/introduction-to-constructors/>
17. Chapter 14.10 [`Constructor member initializer lists`]<https://www.learncpp.com/cpp-tutorial/constructor-member-initializer-lists/>
18. Chapter 15.4 [`Introduction to destructors`]<https://www.learncpp.com/cpp-tutorial/introduction-to-destructors/>
19. Chapter 16.8 [`Range-based for loops <for-each>`]<https://www.learncpp.com/cpp-tutorial/range-based-for-loops-for-each/>
20. Chapter 24.1 [`Introduction to inheritance`]<https://www.learncpp.com/cpp-tutorial/introduction-to-inheritance/>
21. Chapter 24.2 [`Basic inheritance in C++`]<https://www.learncpp.com/cpp-tutorial/basic-inheritance-in-c/>
22. Chapter 24.5 [`Inheritance and access specifiers`]<https://www.learncpp.com/cpp-tutorial/inheritance-and-access-specifiers/>
23. Chapter 25.2 [`Virtual functions and polymorphism`]<https://www.learncpp.com/cpp-tutorial/virtual-functions/>
24. Chapter 25.3 [`The override and final specifiers, and covariant return types`]<https://www.learncpp.com/cpp-tutorial/the-override-and-final-specifiers-and-covariant-return-types/>
25. Chapter 25.7 [`Pure virtual functions, abstract base classes, and interface classes`]<https://www.learncpp.com/cpp-tutorial/pure-virtual-functions-abstract-base-classes-and-interface-classes/>
26. Chapter 28.3 [`Output with ostream and ios`]<https://www.learncpp.com/cpp-tutorial/output-with-ostream-and-ios/>
27. Chapter 28.4 [`Stream classes for strings`]<https://www.learncpp.com/cpp-tutorial/stream-classes-for-strings/>
28. Chapter 28.5 [`Stream states and input validation`]<https://www.learncpp.com/cpp-tutorial/stream-states-and-input-validation/>

## 5. 代码里的语法点，对应你现在真正还要补的 LearnCpp 章节

为了避免 Markdown 预览里表格过宽，这里改成列表版。

1. 多文件项目  
例子：`Account.cpp`、`Account.h`、`IAccount.h` 分开  
为什么还要补：菜鸟前面讲了函数和头文件的基础，但项目级拆分通常讲得不细  
对应章节：2.8 `Programs with multiple code files`

2. 命名空间  
例子：`std::string`、`std::cout`  
为什么还要补：你要真正理解 `std::` 到底是什么  
对应章节：2.9 `Naming collisions and an introduction to namespaces`

3. 预处理器  
例子：`#include`、`#pragma once`  
为什么还要补：要知道头文件为什么能被引入，为什么要防重复包含  
对应章节：2.10 `Introduction to the preprocessor`、2.11 `Header files`、2.12 `Header guards`

4. 花括号初始化  
例子：`m_balance{0.0}`、`m_transactions{}`  
为什么还要补：这是现代 C++ 常见写法，菜鸟基础部分通常不展开讲透  
对应章节：10.4 `Narrowing conversions, list initialization, and constexpr initializers`

5. `constexpr`  
例子：`constexpr float fast_cash_options[4]`  
为什么还要补：这不是普通 `const`，你需要知道它是“编译期常量”  
对应章节：10.4 `Narrowing conversions, list initialization, and constexpr initializers`

6. `auto`  
例子：`const auto &transaction`  
为什么还要补：你现在代码里已经遇到类型推导了  
对应章节：10.8 `Type deduction for objects using the auto keyword`

7. `std::optional`  
例子：`std::optional<int> m_PIN;`  
为什么还要补：这是当前模块最典型的现代 C++ 新语法之一  
对应章节：12.15 `std::optional`

8. 类与对象  
例子：`class Account`  
为什么还要补：这是你现在最需要补的主线知识  
对应章节：14.1 `Introduction to object-oriented programming`、14.2 `Introduction to classes`

9. 成员函数  
例子：`Account::CreatePIN()`  
为什么还要补：你需要区分“普通函数”和“类的成员函数”  
对应章节：14.3 `Member functions`

10. `const` 成员函数  
例子：`bool Authenticate() const`  
为什么还要补：这个 `const` 和普通常量不是一回事  
对应章节：14.4 `Const class objects and const member functions`

11. 访问控制  
例子：`public:`、`private:`  
为什么还要补：这是类设计的核心知识点  
对应章节：14.5 `Public and private members and access specifiers`

12. getter / setter  
例子：`get_first_name()`、`set_first_name()`  
为什么还要补：这是面向对象封装的常见写法  
对应章节：14.6 `Access functions`

13. 封装  
例子：私有成员 `m_first_name`、`m_balance`  
为什么还要补：你要理解为什么成员变量通常不直接暴露  
对应章节：14.8 `The benefits of data hiding (encapsulation)`

14. 构造函数  
例子：`Account(std::string first_name, ...)`  
为什么还要补：对象创建时为什么自动执行这个函数  
对应章节：14.9 `Introduction to constructors`

15. 成员初始化列表  
例子：`: m_first_name{first_name}, ...`  
为什么还要补：这是新手读类代码最容易卡住的点之一  
对应章节：14.10 `Constructor member initializer lists`

16. 析构函数  
例子：`~Account() = default;`  
为什么还要补：即使这里只写了默认析构，你也要知道析构是什么  
对应章节：15.4 `Introduction to destructors`

17. 范围 `for`  
例子：`for (const auto &transaction : m_transactions)`  
为什么还要补：这不是最基础的 `for`，是现代容器遍历写法  
对应章节：16.8 `Range-based for loops (for-each)`

18. 继承  
例子：`class Account : public IAccount`  
为什么还要补：这是你从“会写函数”进阶到“读懂项目架构”的关键一步  
对应章节：24.1 `Introduction to inheritance`、24.2 `Basic inheritance in C++`、24.5 `Inheritance and access specifiers`

19. 虚函数与多态  
例子：`virtual void CreatePIN()`  
为什么还要补：这是接口设计的核心  
对应章节：25.2 `Virtual functions and polymorphism`

20. `override`  
例子：`virtual void CreatePIN() override;`  
为什么还要补：让编译器帮你检查是否真的重写成功  
对应章节：25.3 `The override and final specifiers, and covariant return types`

21. 纯虚函数 / 接口 / 抽象类  
例子：`virtual void CreatePIN() = 0;`、`class IAccount`  
为什么还要补：`IAccount.h` 就是你现在要读懂的接口例子  
对应章节：25.7 `Pure virtual functions, abstract base classes, and interface classes`

22. 输出格式控制  
例子：`std::fixed`、`std::setprecision(2)`、`std::flush`  
为什么还要补：基本输入输出你学过了，但这些“格式和缓冲”还没补齐  
对应章节：28.3 `Output with ostream and ios`

23. 字符串流  
例子：`std::stringstream`  
为什么还要补：这个是 `FloatToString()` 能工作的关键  
对应章节：28.4 `Stream classes for strings`

24. 输入校验  
例子：`while (...)` 反复要求重输  
为什么还要补：你现在代码里只做了简单校验，真正稳健输入要继续补  
对应章节：28.5 `Stream states and input validation`

## 6. 你最该优先掌握的 10 个 LearnCpp 章节

如果你不想一次看太多，就先看这 10 个：

1. 12.15 `std::optional`
2. 14.2 `Introduction to classes`
3. 14.3 `Member functions`
4. 14.5 `Public and private members and access specifiers`
5. 14.9 `Introduction to constructors`
6. 14.10 `Constructor member initializer lists`
7. 24.1 `Introduction to inheritance`
8. 25.2 `Virtual functions and polymorphism`
9. 25.7 `Pure virtual functions, abstract base classes, and interface classes`
10. 28.4 `Stream classes for strings`

## 7. 对你现在这个项目，哪些点最容易卡住

你大概率会卡在下面这些地方：

1. `class Account : public IAccount`
   这里同时出现了类、继承、接口三个概念。
2. `virtual ... = 0`
   这是纯虚函数，不是普通函数声明。
3. `override`
   它不是“可有可无的装饰”，而是帮你检查重写关系。
4. `bool Authenticate() const`
   这个 `const` 修饰的是成员函数，不是返回值。
5. `: m_first_name{first_name}, ...`
   这是成员初始化列表，不是函数体里的赋值语句。
6. `std::optional<int>`
   它表示 PIN 可能还不存在，不是“普通 int”。
7. `for (const auto &transaction : m_transactions)`
   这是范围 `for`，并且里面同时用了 `const`、引用、`auto`。
8. `std::stringstream` + `std::fixed` + `std::setprecision(2)`
   这是“把数字格式化成字符串”的组合写法。

## 8. LearnCpp 里没有完整主线讲透，但你先知道意思就够的点

`WaitIndicator()` 里有两处东西：

- `std::chrono::seconds(1)`
- `std::this_thread::sleep_for(...)`

LearnCpp 对 `chrono` 有相关内容，但它并没有像“类 / 继承 / 虚函数 / optional”那样，专门给新手做一整套线程主线教程。  
对你现在这个 ATM 项目来说，先知道它的作用就够了：

- `std::chrono::seconds(1)`：表示 1 秒
- `std::this_thread::sleep_for(...)`：让程序暂停一会儿

如果只是为了看懂这个项目，你现在不用深挖线程。

## 9. 你现在可以这样学

推荐你按这个顺序推进：

1. 先看 `IAccount.h`
   重点补：25.7、25.2、24.1
2. 再看 `Account.h`
   重点补：14.2、14.3、14.5、14.9、14.10、12.15
3. 再看 `Account.cpp`
   重点补：28.4、28.3、16.8、10.8

## 10. 参考来源

- LearnCpp 首页：<https://www.learncpp.com/>
- LearnCpp 教程目录：<https://www.learncpp.com/cpp-tutorial/>
- 12.15 `std::optional`：<https://www.learncpp.com/cpp-tutorial/stdoptional/>
- 14.10 `Constructor member initializer lists`：<https://www.learncpp.com/cpp-tutorial/constructor-member-initializer-lists/>
- 25.7 `Pure virtual functions, abstract base classes, and interface classes`：<https://www.learncpp.com/cpp-tutorial/pure-virtual-functions-abstract-base-classes-and-interface-classes/>
- 28.5 `Stream states and input validation`：<https://www.learncpp.com/cpp-tutorial/stream-states-and-input-validation/>

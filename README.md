# Effective C++(第三版) 

细读 Effective C++ 参考[Harttle](https://harttle.land/effective-cpp.html)
做到胸中自有丘壑

### 目录

#### 第一章: 自己习惯C++

1. [将C++视作一系列的语言](effective/01.md)
2. [避免使用define](effective/02.md)
3. [尽量使用常量](effective/03.md)
4. [确保使用前已经初始化](effective/04.md)

#### 第二章: 构造、析构、赋值

5. [了解C++默默编写并调用哪些函数](effective/05.md)
6. [若不想使用编译器自动生成的函数，就该明确拒绝](effective/06.md)
7. [将多态基类的析构函数声明为虚函数](effective/07.md)
8. [别让异常逃离析构函数](effective/08.md)
9. [绝不在构造和析构过程中调用virtual函数](effective/09.md)
10. [令operator=返回一个reference to *this](effective/10.md)
11. [在operator中处理自我赋值](effective/11.md)
12. [复制对象时勿忘其每一个成分](effective/12.md)

#### 第三章：资源管理

13. [以对象管理资源](effective/13.md)
14. [在资源管理类中小心copying行为](effective/14.md)
15. [在资源管理类中提高对原始资源的访问](effective/15.md)
16. [成对使用new和delete时要采用相同的形式](effective/16.md)
17. [以独立语句将new对象置入智能指针](effective/17.md)

#### 第四章：设计与声明

18. [让接口容易被正确使用，不易被误用](effective/18.md)
19. [设计clas犹如设计type](effective/19.md)
20. [传引用代替传值](effective/20.md)
21. [必须返回对象时，别妄想返回引用](effective/21.md)
22. [将成员变量声明为private](effective/22.md)
23. [非成员、非友元替换成员函数](effective/23.md)
24. [用非成员函数来支持所有元的类型转换](effective/24.md)
25. [考虑写出一个不抛出异常的swap函数](effective/25.md)

#### 第五章：实现

26. [尽可能延后变量定义式的出现时间](effective/26.md)
27. [尽量少做转型动作](effective/27.md)
28. [避免返回handles指向对象内部成分](effective/28.md)
29. [为异常安全而努力是值得的](effective/29.md)
30. [透彻了解inlining的里里外外](effective/30.md)
31. [将文件间的编译依存关系降至最低](effective/31.md)

##### 第六章：继承与面向对象设计
32. [public继承](effective/32.md)
33. [避免遮掩继承而来的名称](effective/33.md)
34. [区分接口继承和实现继承](effective/34.md)
35. [考虑virtual函数以外的其他选择](effective/35.md)
36. [不要重新定义继承而来的non-virtual函数](effective/36.md)
37. [绝不重新定义继承而来的缺省参数](effective/37.md)

#### 第七章：模板于泛型编程
41. [了解隐式接口和编译器多态](effective/41.md)

#### 第九章 杂项讨论
53. [不要忽略编译器的警告](effective/53.md)
55. [让自己熟悉Boost](effective/55.md)
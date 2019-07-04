# 刷题知识点总结
## 1
质数：指在一个大于1的自然数中，除了1和此整数自身外，没法被其他自然数整除的数（2,3,5,7,11,13,17......）  
分解质因数：把一个合数用质因数相乘的形式表示出来（30 = 2x3x5）  
## 2
p1指向字符型，一次移动一个字符型，1个字节；p1+5后移5个字节，16进制表示为5；  
p2指向长整型，一次移动一个长整型，4个字节，p2+5后移20字节，16进制表示为14  
{ char每次移动1个字节；short移动2个字节 ；int , long ,float移动4个字节 ；double移动8个字节}  
## 3 虚函数和函数重载
虚函数也是类的成员函数  
虚函数和函数重载都实现了C+=的多态性，但表现形式不一样，函数重载调用根据参数个数、参数类型等进行区分，而虚函数则是根据动态联编来确定调用什么  

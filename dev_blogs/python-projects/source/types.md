类型
===============

数字

- integer 整数

   可以无限长 取决于计算机内存

   可以进行的操作 如  加 减 乘 除 等

   从其他类型创建

    int(0.6) # 浮点型创建int
    int('0.6') # 从字符串创建

- 二进制 0b<nnn>
- 八进制 0o<nnn>
- 十六进制 0x<nnn>

浮点型 不可以做整数基转换
float('4.5',16)  是错误的表达式

python 的浮点型基于IEEE 范围跟底层计算机架构有关

## 布尔型

字面   True False

### true-like
 - 整数中 是非零值是真
 - 浮点数 0.0 是假 其他均为真

与或非  or and not

## 布尔型是以整数的子类实现的！ ##
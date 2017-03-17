# DayNote

1.java的八个基本数据类型
  4个整型（int(4),short(2),long(8),byte(1）) 其中一个byte=8个二进制（取值范围为-128~127） long类型后面需要加后缀L
  2个浮点类型(float(4),double(8))    float （6~7位有效数字,后缀为F）   double双精度数值，15位有效数字   3.402默认为double
  （浮点数不适合出现在禁止出现在舍入的计算中，比如system.out.print(2.0-1.1);会出现0.89999999而不是0.9,建议使用BigDecimal类
  char类型
  boolean类型

2.八进制的前缀为0，如010为8    十六位进制的前缀为0x,如 0xACFE

3.大数据可以使用 BigInteger和BigDecimal,前者处理任意精度的整数运算，后者处理任意精度的浮点运算(但是不能运用运算符，有固定的加减乘除方法)

4.

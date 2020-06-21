斐波那契数列（Fibonacci sequence），又称黄金分割数列、因数学家列昂纳多·斐波那契（Leonardoda Fibonacci）以兔子繁殖为例子而引入，故又称为“兔子数列”，指的是这样一个数列：1、1、2、3、5、8、13、21、34、……即从第3个数开始，每个数都等于它前两个数的和。
函数名为 Fibonacci.of()
of是一个静态方法，入参是int，返回值是int
参数从1开始，各参考值如下
Fibonacci.of(1) == 1
Fibonacci.of(2) == 1
Fibonacci.of(3) == 2
Fibonacci.of(4) == 3
Fibonacci.of(5) == 5
...
在main函数用循环打印1~200的Fibonacci数列
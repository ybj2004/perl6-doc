## Set, Bag

充分了解 Perl 6 语言，用 Perl 6 语言设计开发语言转换工具，将不同的
语言相互转换。

Ruby 的数据遍历的时候，能同时接受多个参数吗？

    for (a,b,c,d) in multiarr
        print("a=#{a}, b=#{b}, c=#{c}, d=#{d}\n")
    end

1. Ruby 的变量没有前缀，在没有了解清楚关键字的情况下，不能随意命名变量。
内插也繁琐一些，而且也不清楚变量的类型，显然通过命名来解决这个问题也行。

2. Perl 6 将各种内置的变量名称进行了划分，$?FILE $*TAB, 给了变量命名
一个独立的空间 $id-name

2. Ruby 的类变量就像母亲，是类变量的模板，类实例携带的变量就像儿子。自己
继承了母亲的东西，还能自己修改，不过不能自己扩展自己。

Perl 6 是一个能自我进化的可怕东西。能从一个实例扩展出一个完整的系统。

可以用 Perl 6 来模拟一个 CPU, C 语言有的东西，它都有，有结构吗？

这个 CPU 的驱动语言是一种语法的字符串。一个 CPU 会进化成一个庞大的系统。

要做的事情很多，我的任务只有一个，语言的转换。

Task1任务描述
====
1. 环境搭建：anaconda环境配置、解释器<br>
2. python初体验：print and input<br>
3. python基础讲解：python变量特性+命名释方法、python中“：”作用、学会使用dir( )及和help( )、import使用、pep8介绍<br>
4. python数值基本知识：python中数值类型（int，float，bool，e记法等）、算数运算符、逻辑运算符、成员运算符、身份运算符、运算符

# 学习总结
## 1. 环境搭建
* Anaconda+pycharm. 直接下载pycharm和anaconda，可以在里面进行python相关的环境配置。<br>
* python解释器。什么是python解释器呢？我们在编辑器中输入的代码，计算机并不能直接识别其内容与意义，需要用相关的“语言翻译机”翻译成计算机懂得的语言然后再让它执行。这里的语言翻译机就是python解释器了。所以我们要运行python程序，必须先安装python解释器。
## 2. python初级代码体验
    ``` 
    x = input('x=');
    y = int(x) * int(x);
    print('the answer is',y)
    ```
   心得：有C的基础，python编程几乎不是什么难点，只要学会常用的几个点，基本足够满足机器学习的初级阶段，但是要进阶还是得继续深入学习。
## 3. python基础讲解
* python变量特性<br>
    在python编程中，变量名无需进行事先声明，在进行赋值操作是就相当于进行了声明。其赋值方式与C相同。其次，python允许对多个变量进行赋值。比如：
    ```
    a, b, c = 14, 15, 'king';
    print('the answer is',a, b, c)
    ```
    以上程序的输出结果，14赋值给a，15赋值给b，字符串king赋值给c。
* python数据类型<br>
    在python中，常用的数据类型包括整数、浮点数、字符串、List、Tuple、Dictionary和Set。具体用法在此不另作解释。
* 冒号的作用<br>
    在python中，冒号主要用于定义分片、步长。常用于list、tuple、Dic等。
* dir()<br>
    使用dir()函数可以查看python对像内的所有属性及方法，在python中任何东西都是对像，包括一个数据类型，一个模块。它返回包含要查询对象的所有属性名称的列表。
* help()<br>
    在python中如果对任何名称、变量等不熟悉用法，可使用help()函数进行查询。
* import<br>
    当我们编写了很长的代码时，为了便于维护代码，我们把很多函数分组，分别放到不同的文件里，这样，每个文件包含的代码就相对较少，很多编程语言都采用这种组织代码的方式。在Python中，一个.py文件就称之为一个模块。而使用这些模块，我们就要用到import。
    以python内置的模块sys为例，我们要使用这个模块，就需要先声明：
    ```
    import sys
    ```
    这样，sys模块就相当于导入到当前项目内，可以直接使用了。可以访问sys模块的所有功能。此外，对于from...import语句，他表示从模块中导入一个指定的部分到当前命名空间中。
* pep8<br>
    python中，pep8是表示python的编码规范。比如什么时候该用空格，什么时候该换行等等。python使用者都遵守这个规范，这样程序员之间能够互相看得懂对方的代码。不同程序员编写的 Python 代码可以保持最大程度的相似风格。这样就易于阅读，易于在程序员之间交流。
## 4. python基础数值知识总结
这里整型和浮点数省略，用法基本与C相同。
* bool<br>
    布尔值（bool）和布尔代数的表示完全一致，一个布尔值只有True、False两种值，要么是True，要么是False。在Python中，可以直接用True、False表示布尔值，也可以通过布尔运算计算出来（3>2,Ture）。其次，布尔值可以用and、or和not运算。
* e记法<br>    
    对于很大或很小的浮点数，就必须用科学计数法表示，把10用e替代，1.23x10^9就是1.23e9，或者12.3e8，0.000012可以写成1.2e-5，等等。
* 算术运算符<br>  
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

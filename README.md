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
## 3. python基础知识总结
* python变量特性<br>
    在python编程中，变量名无需进行事先声明，在进行赋值操作是就相当于进行了声明。其赋值方式与C相同。其次，python允许对多个变量进行赋值。比如：
    ```
    a, b, c = 14, 15, 'king';
    print('the answer is',a, b, c)
    ```
    以上程序的输出结果，14赋值给a，15赋值给b，字符串king赋值给c。

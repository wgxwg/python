# python
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {
    "collapsed": true
   },
   "source": [
    "    人生苦短，我用python\n",
    "\n",
    "# python课程"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "collapsed": true
   },
   "source": [
    "### 课表\n",
    "    一、 python基础    -     变量与数据类型，及常见数据类型的用法\n",
    "    二、 python基础    -     条件、循环、函数、类\n",
    "    三、 python爬虫    -     python爬虫并用Mysql数据库存储\n",
    "    四、 pandas通览    -     用pandas做数据处理与分析\n",
    "    五、 实战          -     泰坦尼克幸存者预测"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 学完本课程之后，你会：\n",
    "    1、 掌握基本的python语法，并编写简单的python程序\n",
    "    2、 可以阅读别人写的python代码\n",
    "    3、 编写简单的爬虫\n",
    "    4、 进行基本的数据分析"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 机器学习需要：\n",
    "    1、 数学理论知识  (统计、线性代数、微积分 。。。)\n",
    "    2、 编程能力（python)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### python的特性\n",
    "    1、python语法简单，容易理解，容易学习\n",
    "    2、跨平台，可在windows/linux/mac os等系统上运行\n",
    "    3、可以做网站、爬虫、大数据处理、机器学习\n",
    "    4、拥有强大、丰富的第三方库  numpy、pandas ..."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 最简单的开始"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "hello, \"world\n"
     ]
    }
   ],
   "source": [
    "print('hello, \"world')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "metadata": {
    "scrolled": true
   },
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "hello, 'world\n"
     ]
    }
   ],
   "source": [
    "print(\"hello, 'world\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 347,
   "metadata": {},
   "outputs": [],
   "source": [
    "import this"
   ]
  },
  {
   "cell_type": "raw",
   "metadata": {},
   "source": [
    "python之禅  \n",
    "                作者：Tim Peters\n",
    "\n",
    "优美胜于丑陋                                                  Python 以编写优美的代码为目标\n",
    "明了胜于晦涩                                                  优美的代码应当是明了的，命名规范，风格相似 \n",
    "简洁胜于复杂                                                  优美的代码应当是简洁的，不要有复杂的内部实现 \n",
    "复杂胜于凌乱                                                  如果复杂不可避免，那代码间也不能有难懂的关系，要保持接口简洁 \n",
    "扁平胜于嵌套                                                  优美的代码应当是扁平的，不能有太多的嵌套\n",
    "间隔胜于紧凑                                                  优美的代码有适当的间隔，不要奢望一行代码解决问题 \n",
    "可读性很重要                                                  优美的代码是可读的 \n",
    "即便假借特例的实用性之名，也不可违背这些规则                        这些规则至高无上 \n",
    "不要包容所有错误，除非你确定需要这样做                             精准地捕获异常，不写 except:pass 风格的代码 \n",
    "当存在多种可能，不要尝试去猜测 \n",
    "而是尽量找一种，最好是唯一一种明显的解决方案                        如果不确定，就用穷举法\n",
    "虽然这并不容易，因为你不是Python之父                             这里的 Dutch 是指 Guido \n",
    "做也许好过不做，但不假思索就动手还不如不做                          动手之前要细思量\n",
    "如果你无法向人描述你的方案，那肯定不是一个好方案；反之亦然             方案测评标准\n",
    "命名空间是一种绝妙的理念，我们应当多加利用                          倡导与号召"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 从计算器开始"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "105"
      ]
     },
     "execution_count": 9,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "5 + 100"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 12,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "10.0"
      ]
     },
     "execution_count": 12,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "100 / 10"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 13,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "1000"
      ]
     },
     "execution_count": 13,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "100 * 10"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 14,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "1"
      ]
     },
     "execution_count": 14,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "100 - 99"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 15,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "1"
      ]
     },
     "execution_count": 15,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "10 % 3"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 16,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "1000"
      ]
     },
     "execution_count": 16,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "10 ** 3"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 18,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "2.154434690031884"
      ]
     },
     "execution_count": 18,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "10 ** (1/3)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 19,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "import math"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 20,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "3.141592653589793"
      ]
     },
     "execution_count": 20,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "math.pi"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 21,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "1.0"
      ]
     },
     "execution_count": 21,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "math.sin(math.pi/2)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 22,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "9"
      ]
     },
     "execution_count": 22,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "math.floor(9.23432)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 23,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "10"
      ]
     },
     "execution_count": 23,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "math.ceil(9.234)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 应用题：\n",
    "    1、小姐姐去买水果，苹果5元一斤，葡萄15元一斤，现在小姐姐买了2斤苹果，1.5斤葡萄，问，小姐姐买这两种水果分别花了多少钱？总共花了多少钱？"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 26,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "10\n",
      "22.5\n",
      "32.5\n"
     ]
    }
   ],
   "source": [
    "# 苹果的花费\n",
    "print(5*2)\n",
    "\n",
    "# 葡萄的花费\n",
    "print(15*1.5)\n",
    "\n",
    "# 总花费\n",
    "print((5*2) + (15*1.5))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 三个问题：\n",
    "    1、如果脱离了题干和注释，我们无法理解 5 * 2 是什么意思\n",
    "    2、当计算总价的时候，重复计算了苹果和葡萄的花费\n",
    "    3、输出是一个数字，表达不清晰"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 32,
   "metadata": {
    "scrolled": true
   },
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "10 32.5\n"
     ]
    }
   ],
   "source": [
    "apple_price = 5\n",
    "apple_weight = 2\n",
    "apple_cost = apple_price * apple_weight\n",
    "\n",
    "grape_price = 15\n",
    "grape_weight = 1.5\n",
    "grape_cost = grape_price * grape_weight\n",
    "\n",
    "total_cost = apple_cost + grape_cost\n",
    "\n",
    "print(apple_cost, total_cost)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 增强的格式化字符串函数 format"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 33,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'苹果的花费为：10；葡萄的花费为：22.5；总花费为：32.5'"
      ]
     },
     "execution_count": 33,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "\"苹果的花费为：{}；葡萄的花费为：{}；总花费为：{}\".format(apple_cost, grape_cost, total_cost)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 变量： 代表某个值得名称"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 34,
   "metadata": {},
   "outputs": [
    {
     "ename": "NameError",
     "evalue": "name 'number' is not defined",
     "output_type": "error",
     "traceback": [
      "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[0;31mNameError\u001b[0m                                 Traceback (most recent call last)",
      "\u001b[0;32m<ipython-input-34-e96a55dd7add>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[0;32m----> 1\u001b[0;31m \u001b[0mnumber\u001b[0m \u001b[0;34m+\u001b[0m \u001b[0;36m2\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m",
      "\u001b[0;31mNameError\u001b[0m: name 'number' is not defined"
     ]
    }
   ],
   "source": [
    "number + 2"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 语法糖"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 35,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "a = 10 \n",
    "b = 20\n",
    "\n",
    "a, b = b, a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 36,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "a is 20, b is 10\n"
     ]
    }
   ],
   "source": [
    "print(\"a is {}, b is {}\".format(a, b))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 命名规范"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "    1、标识符的第一个字符必须是字母表中的字母(大写或小写)或者一个下划线\n",
    "    2、标识符名称的其他部分可以由字母(大写或小写)、下划线(‘_’)或数字(0-9)组成。\n",
    "    3、标识符名称是对大小写敏感的。"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 40,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "n = 10\n",
    "N = 10"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 45,
   "metadata": {},
   "outputs": [
    {
     "ename": "SyntaxError",
     "evalue": "invalid syntax (<ipython-input-45-d2231249f0f8>, line 2)",
     "output_type": "error",
     "traceback": [
      "\u001b[0;36m  File \u001b[0;32m\"<ipython-input-45-d2231249f0f8>\"\u001b[0;36m, line \u001b[0;32m2\u001b[0m\n\u001b[0;31m    3thidnf = 10\u001b[0m\n\u001b[0m          ^\u001b[0m\n\u001b[0;31mSyntaxError\u001b[0m\u001b[0;31m:\u001b[0m invalid syntax\n"
     ]
    }
   ],
   "source": [
    "# 错误： 首字符为数字\n",
    "3thidnf = 10 "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 49,
   "metadata": {},
   "outputs": [
    {
     "ename": "SyntaxError",
     "evalue": "invalid syntax (<ipython-input-49-61ab1aa1327b>, line 2)",
     "output_type": "error",
     "traceback": [
      "\u001b[0;36m  File \u001b[0;32m\"<ipython-input-49-61ab1aa1327b>\"\u001b[0;36m, line \u001b[0;32m2\u001b[0m\n\u001b[0;31m    my name = 100\u001b[0m\n\u001b[0m          ^\u001b[0m\n\u001b[0;31mSyntaxError\u001b[0m\u001b[0;31m:\u001b[0m invalid syntax\n"
     ]
    }
   ],
   "source": [
    "# 字母中间有空格，为非法字符\n",
    "my name = 100"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 48,
   "metadata": {},
   "outputs": [
    {
     "ename": "SyntaxError",
     "evalue": "can't assign to operator (<ipython-input-48-69fd2ff4a721>, line 2)",
     "output_type": "error",
     "traceback": [
      "\u001b[0;36m  File \u001b[0;32m\"<ipython-input-48-69fd2ff4a721>\"\u001b[0;36m, line \u001b[0;32m2\u001b[0m\n\u001b[0;31m    my-name = 10\u001b[0m\n\u001b[0m                ^\u001b[0m\n\u001b[0;31mSyntaxError\u001b[0m\u001b[0;31m:\u001b[0m can't assign to operator\n"
     ]
    }
   ],
   "source": [
    "# -是变量命名中的非法字符\n",
    "my-name = 10"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 54,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "33.333"
      ]
     },
     "execution_count": 54,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "round(100/3, 3)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 代码规范建议"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- 1、不要使用单字符\n",
    "- 2、变量名能清晰表达变量的意思\n",
    "- 3、合理使用字母中间下划线"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 变量类型"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "    1、字符串 str\n",
    "    2、数字 int float complex ..\n",
    "    3、列表 list\n",
    "    4、元组 tuple\n",
    "    5、字典 dict"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 数值类型"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 56,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "number = 10\n",
    "number = number + 10\n",
    "number += 10"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 57,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "number -= 10\n",
    "number *= 10\n",
    "number /= 10"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 58,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "import math"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 59,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "59049.0"
      ]
     },
     "execution_count": 59,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 乘方、开放\n",
    "math.pow(3, 10)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 61,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "59049"
      ]
     },
     "execution_count": 61,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 推荐是用\n",
    "3 ** 10"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 62,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "2"
      ]
     },
     "execution_count": 62,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "math.floor(2.23242)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 63,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "3"
      ]
     },
     "execution_count": 63,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "math.ceil(2.234234)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 65,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "3.141592653589793"
      ]
     },
     "execution_count": 65,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 度的转换\n",
    "math.radians(180)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 66,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "1.0"
      ]
     },
     "execution_count": 66,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "math.sin(math.pi/2)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 67,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "1"
      ]
     },
     "execution_count": 67,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "min(10, 12, 234, 100, 1)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 68,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "234"
      ]
     },
     "execution_count": 68,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "max(10, 12, 234, 100, 1)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 70,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "357"
      ]
     },
     "execution_count": 70,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "sum([10, 12, 234, 100, 1])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 72,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(3, 1)"
      ]
     },
     "execution_count": 72,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "divmod(10, 3)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### bool型"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 73,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(True, False)"
      ]
     },
     "execution_count": 73,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "True, False"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 74,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 74,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "True == 1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 75,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 75,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "False == 0"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 91,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "11"
      ]
     },
     "execution_count": 91,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 不建议这样写，没有意义， 有一个特例，后面会讲到\n",
    "True + 10"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 78,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 78,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "100 > 10"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### bool类型，运算： 与运算、或运算、非运算"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 81,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "False"
      ]
     },
     "execution_count": 81,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 与运算，同为真则为真\n",
    "True and False"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 86,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 86,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 或运算, 只要一个为真则为真\n",
    "True or False"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 89,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 89,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 非运算，取反\n",
    "not False"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "| 操作符 | 解释 |\n",
    "| ---  | --- |\n",
    "| <  | 小于 |\n",
    "| <=  | 小于等于 |\n",
    "| >  | 大于 |\n",
    "| >=  | 大于等于 |\n",
    "| ==  | 等于 |\n",
    "| !=  | 不等于 |\n",
    "| is  | 是相同对象 |"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 字符串"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 98,
   "metadata": {},
   "outputs": [],
   "source": [
    "# 字符串可以用双引号，也可以用单引号。通过单、双引号的恰当使用，可以避免不必要的字符转义（escape）,也就是说，可以避免使用 \\ (转义字符)\n",
    "\n",
    "line = \"hello world\"\n",
    "line = \"hello world\\\"\"\n",
    "line = 'hello \\'world'"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 101,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'ni hao, xiaojiejie'"
      ]
     },
     "execution_count": 101,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 字符串的加法操作\n",
    "line_1 = \"ni hao, \"\n",
    "line_2 = 'xiaojiejie'\n",
    "line_1 + line_2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 104,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'nihao nihao nihao nihao nihao nihao nihao nihao nihao nihao '"
      ]
     },
     "execution_count": 104,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 字符串的乘法操作\n",
    "line = 'nihao '\n",
    "line * 10"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 107,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'nihao '"
      ]
     },
     "execution_count": 107,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 字符串是不可变类型的变量\n",
    "line"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 109,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'buhao '"
      ]
     },
     "execution_count": 109,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line = 'buhao '\n",
    "line"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 105,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "6"
      ]
     },
     "execution_count": 105,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 返回字符串的长度\n",
    "len(line)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 119,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(4417536944, 4417536944)"
      ]
     },
     "execution_count": 119,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line = 'nihao '\n",
    "line_copy = line\n",
    "# id函数，返回一个身份识别符，可以理解为一个变量的内存地址\n",
    "id(line), id(line_copy)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 120,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(4417537336, 4417536944)"
      ]
     },
     "execution_count": 120,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line = 'buhao '\n",
    "id(line), id(line_copy)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 116,
   "metadata": {
    "scrolled": true
   },
   "outputs": [
    {
     "data": {
      "text/plain": [
       "33"
      ]
     },
     "execution_count": 116,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "23 + 10"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### markdown中表格的写法"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "| 序号 | 名称 | 年龄 |\n",
    "| --- | :---: | --- |\n",
    "| 1 | wong | 18 |\n",
    "| 2 | sun xing zhe | 500 |"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 切片"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "line = 'huan ying da jia lai wan men shang ke'"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 取前十个字符"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 123,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'huan ying '"
      ]
     },
     "execution_count": 123,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line[0:10]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 186,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'Akjd'"
      ]
     },
     "execution_count": 186,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line[0:20:3]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 取后十个字符"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 128,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'n shang ke'"
      ]
     },
     "execution_count": 128,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line[-10:]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 翻转字符"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 129,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'ek gnahs nem naw ial aij ad gniy nauh'"
      ]
     },
     "execution_count": 129,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line[::-1]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 单字符"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 单字符是不可以进行赋值的"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 134,
   "metadata": {},
   "outputs": [
    {
     "ename": "TypeError",
     "evalue": "'str' object does not support item assignment",
     "output_type": "error",
     "traceback": [
      "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[0;31mTypeError\u001b[0m                                 Traceback (most recent call last)",
      "\u001b[0;32m<ipython-input-134-6dbfc2cde6c6>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[0;32m----> 1\u001b[0;31m \u001b[0mline\u001b[0m\u001b[0;34m[\u001b[0m\u001b[0;34m-\u001b[0m\u001b[0;36m1\u001b[0m\u001b[0;34m]\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0;34m'E'\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m",
      "\u001b[0;31mTypeError\u001b[0m: 'str' object does not support item assignment"
     ]
    }
   ],
   "source": [
    "line[-1] = 'E'"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 136,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'Huan ying da jia lai wan men shang ke'"
      ]
     },
     "execution_count": 136,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.capitalize()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 199,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'Asdfasdfewfsdf'"
      ]
     },
     "execution_count": 199,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line = \"ASDFASDFEWFSDF\"\n",
    "line.capitalize()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 145,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'   ASDFASDFEWFSDF   '"
      ]
     },
     "execution_count": 145,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 居中\n",
    "line.center(20)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 147,
   "metadata": {
    "scrolled": true
   },
   "outputs": [
    {
     "data": {
      "text/plain": [
       "0"
      ]
     },
     "execution_count": 147,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 计数\n",
    "line.count('Z')"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 字符串首尾判断"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 151,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "False"
      ]
     },
     "execution_count": 151,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.endswith('FEWFSDD')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 152,
   "metadata": {
    "scrolled": true
   },
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 152,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.startswith('ASDFA')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 201,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'ASDFASDFEWFSDF'"
      ]
     },
     "execution_count": 201,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 204,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "4"
      ]
     },
     "execution_count": 204,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.find('A', 2)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 167,
   "metadata": {},
   "outputs": [
    {
     "ename": "ValueError",
     "evalue": "substring not found",
     "output_type": "error",
     "traceback": [
      "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[0;31mValueError\u001b[0m                                Traceback (most recent call last)",
      "\u001b[0;32m<ipython-input-167-a63f130686f3>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[0;31m# 当字符不存在时，报错\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 2\u001b[0;31m \u001b[0mline\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mindex\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m'Z'\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m",
      "\u001b[0;31mValueError\u001b[0m: substring not found"
     ]
    }
   ],
   "source": [
    "# 当字符不存在时，报错\n",
    "line.index('Z')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 175,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "line = 'Aslkdfjsldkf'"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 170,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'ACDASDLDSD'"
      ]
     },
     "execution_count": 170,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.upper()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 172,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'acdasdldsd'"
      ]
     },
     "execution_count": 172,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.lower()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 176,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 176,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.istitle()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 177,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "False"
      ]
     },
     "execution_count": 177,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.isupper()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 178,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "False"
      ]
     },
     "execution_count": 178,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.islower()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 180,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "line = '   lskdas k  \\n\\t   '"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 181,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'lskd \\n as k'"
      ]
     },
     "execution_count": 181,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.strip()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 182,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'   lskd \\n as k'"
      ]
     },
     "execution_count": 182,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.rstrip()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 183,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'lskd \\n as k  \\n\\t   '"
      ]
     },
     "execution_count": 183,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.lstrip()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 184,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "line = 'Aslkdfjsldkf'"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 185,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'aSLKDFJSLDKF'"
      ]
     },
     "execution_count": 185,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line.swapcase()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 【重点】上面我们用到的所有字符串函数，都是为我们生成了一个新的字符串，原有的字符串是不变的"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 188,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "4417602368"
      ]
     },
     "execution_count": 188,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "line = \"ni hao\"\n",
    "id(line)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 189,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(4417602368, 4417601976)"
      ]
     },
     "execution_count": 189,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "new_line = line.upper()\n",
    "id(line), id(new_line)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 列表"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 190,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "# 空列表\n",
    "varibals = []\n",
    "varibals = list()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### 可以容纳任意类型的对象，任意数量的对象 【重点】列表是可变类型的"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 191,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "varibals = [1, 2, 3, 'ni hao', 'hello, python', [], [100, 100]]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 194,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[1, 2, 'ni hao']"
      ]
     },
     "execution_count": 194,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "varibals = []\n",
    "varibals.append(1)\n",
    "varibals.append(2)\n",
    "varibals.append('ni hao')\n",
    "varibals"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 197,
   "metadata": {
    "scrolled": true
   },
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[10, 2, 'ni hao']"
      ]
     },
     "execution_count": 197,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "varibals[0] = 10\n",
    "varibals"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### python是一种动态类型的语言，一个变量是什么类型，要看程序在运行过程中变量所代表的值是什么"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 207,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "str"
      ]
     },
     "execution_count": 207,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "var = 10\n",
    "type(var)\n",
    "var = 'str'\n",
    "type(var)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 切片"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 211,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[2, 'ni hao']"
      ]
     },
     "execution_count": 211,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "varibals[-2:]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 212,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[10, 2, 'ni hao', 1, 23]"
      ]
     },
     "execution_count": 212,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "varibals + [1,23]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 213,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[10, 2, 'ni hao', 10, 2, 'ni hao', 10, 2, 'ni hao', 10, 2, 'ni hao']"
      ]
     },
     "execution_count": 213,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "varibals * 4"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 序列 列表是一种容器型的序列；字符串是一种扁平型的序列"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 214,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "3"
      ]
     },
     "execution_count": 214,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "len(varibals)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 217,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[10, 2, 'ni hao', 1, 1, 1]"
      ]
     },
     "execution_count": 217,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# 没有返回值，而是修改了我们列表对象本身\n",
    "varibals.append(1)\n",
    "varibals"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 218,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "# 清空\n",
    "varibals.clear()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 246,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "varibals = [1,12,23,4234, [1,2]]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 247,
   "metadata": {},
   "outputs": [],
   "source": [
    "new_varibals = varibals.copy()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 248,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[1, 12, 23, 4234, [99999, 2]]"
      ]
     },
     "execution_count": 248,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "new_varibals[-1][0] = 99999\n",
    "new_varibals"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 252,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[1, 12, 23, 4234, [99999, 2]]"
      ]
     },
     "execution_count": 252,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "varibals"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 253,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(4414081800, 4414081800)"
      ]
     },
     "execution_count": 253,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "id(new_varibals[-1]), id(varibals[-1])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 255,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[1, 2, 3, 4]"
      ]
     },
     "execution_count": 255,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a = [1,2]\n",
    "b = [3,4]\n",
    "a + b"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 257,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[1, 2, 3, 4, 3, 4]"
      ]
     },
     "execution_count": 257,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a.extend(b)\n",
    "a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 258,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[1, 2, 3, 4, 3, 4]"
      ]
     },
     "execution_count": 258,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 259,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "a.insert(0, 100)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 263,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[100, 1, 2, 3, 4, 3]"
      ]
     },
     "execution_count": 263,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 264,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "100"
      ]
     },
     "execution_count": 264,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a.pop(0)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 265,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[1, 2, 3, 4, 3]"
      ]
     },
     "execution_count": 265,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 271,
   "metadata": {},
   "outputs": [
    {
     "ename": "ValueError",
     "evalue": "list.remove(x): x not in list",
     "output_type": "error",
     "traceback": [
      "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[0;31mValueError\u001b[0m                                Traceback (most recent call last)",
      "\u001b[0;32m<ipython-input-271-c7b29c338c05>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[0;32m----> 1\u001b[0;31m \u001b[0ma\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mremove\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m'z'\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m",
      "\u001b[0;31mValueError\u001b[0m: list.remove(x): x not in list"
     ]
    }
   ],
   "source": [
    "a.remove('z')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 267,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[1, 3, 4, 3]"
      ]
     },
     "execution_count": 267,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 270,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "a.remove?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 269,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[1, 4, 3]"
      ]
     },
     "execution_count": 269,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 275,
   "metadata": {},
   "outputs": [],
   "source": [
    "a.sort(reverse=True)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 277,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[4, 3, 1]"
      ]
     },
     "execution_count": 277,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 279,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "False"
      ]
     },
     "execution_count": 279,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "5 in a"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### tuple"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 282,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "tuple"
      ]
     },
     "execution_count": 282,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "var = tuple()\n",
    "var = ()\n",
    "type(var)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 286,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "var = (1,2, 1, 3,4,5, [23,34,43])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 287,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "2"
      ]
     },
     "execution_count": 287,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "var.count(1)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 289,
   "metadata": {
    "scrolled": true
   },
   "outputs": [
    {
     "data": {
      "text/plain": [
       "5"
      ]
     },
     "execution_count": 289,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "var.index(5)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 290,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "a, b = 10, 20"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 293,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "a = 10, 20"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 294,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(10, 20)"
      ]
     },
     "execution_count": 294,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "| 元组变量 | 字符串变量 | 列表变量 | \n",
    "| --- | --- | -- |\n",
    "| t_1 = [1,2,3,4,5] | s_1 = 'ni hao' | l_1 = [1,2,3,4,5] |\n",
    "| t_2 = [5,6,7,8,9] | s_2 = 'how are you' | l_2 = [6,7,8,9,10] |\n",
    "\n",
    "| 函数 | 元组 | 实例 | 字符串 | 实例 | 列表 | 实例 |\n",
    "| :--- | :---: | :--- | :---: | :--- | :---: | :-- | :--- |\n",
    "| + | ✅ | t_1 + t_2 | ✅ | s_1 + s_2 | ✅ | l_1 + l_2 |\n",
    "| * | ✅ | t_1 * 2 | ✅ | s_1 * 2 | ✅ | l_1 * 2 |\n",
    "| > < | ✅ | t_1 > t_2 | ✅ | s_1 > s_2 | ✅ | l_1 > l2 |\n",
    "| [index] | ✅ | t_1[0] | ✅ | s_1[0] | ✅ | l_1[0] | 列表可以索引赋值，字符串、元组不可以 |\n",
    "| [::] | ✅ | t_1[::] | ✅ | s_1[0:10:1] | ✅ | l_1[0:10:2] | 列表可以切片赋值，字符串、元组不可以 |\n",
    "| len | ✅ | len(t_1) |✅ | len(s_1) | ✅ | len(l_1) |\n",
    "| bool | ✅ | bool(t_1) |✅ | bool(s_1) | ✅ | bool(l_1) | 空字符串、空列表、空元组转换为布尔型为False |\n",
    "| count | ✅ | t_1.count(1) | ✅ | s_1.count('n') | ✅ | l_1.count(1) |\n",
    "| index | ✅ | t_1.index(3) | ✅ | s_1.index('n') | ✅ | l_1.index(1) | \n",
    "| replace | | | ✅ | s_1.replace('n', 'N') | | | 字符串replace函数返回一个新字符串，原来的变量不变 |\n",
    "| sort | | | | | ✅ | l_1.sort() |\n",
    "| reverse | | |  |  | ✅ | l_1.reverse() | 字符串不可更改，只能通过生成一个新的字符串来翻转 | \n",
    "| append | | |  | | ✅ | l_1.append(100) |\n",
    "| extend | | | | | ✅ | l_1.extend(l_2) |\n",
    "| remove | | | | | ✅ | l_1.remove(1) |\n",
    "| pop | | | | | ✅ | l_1.pop() |"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 字典类型"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 296,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "dict"
      ]
     },
     "execution_count": 296,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "var = {}\n",
    "var = dict()\n",
    "type(var)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 298,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "var = {\n",
    "    '中': 100,\n",
    "    '左': 200\n",
    "}"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 299,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "100"
      ]
     },
     "execution_count": 299,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "var['中']"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 300,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "100"
      ]
     },
     "execution_count": 300,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "words = ['中', '左']\n",
    "location = [100, 200]\n",
    "\n",
    "location[words.index('中')]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 拉锁函数"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 303,
   "metadata": {},
   "outputs": [],
   "source": [
    "new_var = list(zip(words, location))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 311,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[('中', 100), ('左', 200)]"
      ]
     },
     "execution_count": 311,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "new_var"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 304,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{'中': 100, '左': 200}"
      ]
     },
     "execution_count": 304,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "dict(new_var)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 310,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[(1, 3, 4), (2, 4, 5)]"
      ]
     },
     "execution_count": 310,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "list(zip([1,2], [3,4, 5], [4,5,5]))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 313,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "students = ['wong', 'li', 'sun', 'zhao', 'qian']"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 315,
   "metadata": {},
   "outputs": [],
   "source": [
    "money = dict.fromkeys(students, 10)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 访问字典中的值"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 318,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "10"
      ]
     },
     "execution_count": 318,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "money['wong']"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 324,
   "metadata": {},
   "outputs": [],
   "source": [
    "a = money.get('ww', '100')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 325,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "100\n"
     ]
    }
   ],
   "source": [
    "print(a)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 326,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "dict_keys(['wong', 'sun', 'qian', 'li', 'zhao'])"
      ]
     },
     "execution_count": 326,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "money.keys()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 327,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "dict_values([10, 10, 10, 10, 10])"
      ]
     },
     "execution_count": 327,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "money.values()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 328,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "dict_items([('wong', 10), ('sun', 10), ('qian', 10), ('li', 10), ('zhao', 10)])"
      ]
     },
     "execution_count": 328,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "money.items()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 331,
   "metadata": {},
   "outputs": [
    {
     "ename": "KeyError",
     "evalue": "'wong'",
     "output_type": "error",
     "traceback": [
      "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[0;31mKeyError\u001b[0m                                  Traceback (most recent call last)",
      "\u001b[0;32m<ipython-input-331-288dcedd1b7e>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[0;31m# 删除操作\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 2\u001b[0;31m \u001b[0mmoney\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mpop\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m'wong'\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m",
      "\u001b[0;31mKeyError\u001b[0m: 'wong'"
     ]
    }
   ],
   "source": [
    "# 删除操作\n",
    "money.pop('wong')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 332,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{'li': 10, 'qian': 10, 'sun': 10, 'zhao': 10}"
      ]
     },
     "execution_count": 332,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "money"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 340,
   "metadata": {},
   "outputs": [],
   "source": [
    "money['nihao'] = 100"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 341,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{'guli': 100,\n",
       " 'li': 10,\n",
       " 'nihao': 100,\n",
       " 'qian': 10,\n",
       " 'sun': 10,\n",
       " 'wong': 100,\n",
       " 'zhao': 10}"
      ]
     },
     "execution_count": 341,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "money"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 343,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "1000"
      ]
     },
     "execution_count": 343,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "money.setdefault('haha', 1000)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 344,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{'guli': 100,\n",
       " 'haha': 1000,\n",
       " 'li': 10,\n",
       " 'nihao': 100,\n",
       " 'qian': 10,\n",
       " 'sun': 10,\n",
       " 'wong': 100,\n",
       " 'zhao': 10}"
      ]
     },
     "execution_count": 344,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "money"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.5.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}

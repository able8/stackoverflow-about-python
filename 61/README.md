| rank | ▲ | ✰ | vote | url |
|:-:|:-:|:-:|:-:|:-:|
|  61 | 374 | 45 | 700 | [url](http://stackoverflow.com/questions/930397/how-to-get-the-last-element-of-a-list) |

***

## 获取列表最后一个元素

在Python里,如何获取一个列表的最后一个元素?

***

`some_list[-1]`最短最Pythonic的方法.

事实上你可以用这个语法做好多事.`some_list[-n]`语法获取倒数第n个元素.所以`some_list[-1]`获取最后一个元素,`some_list[-2]`获取倒数第二个,等等.最后`some_list[-len(some_list)]`可以获取第一个元素~~

你也可以用这种方法获取列表元素,例如:

```python
>>> some_list = [1, 2, 3]
>>> some_list[-1] = 5 # Set the last element
>>> some_list[-2] = 3 # Set the second to last element
>>> some_list
[1, 3, 5]
```

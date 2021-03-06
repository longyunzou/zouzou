# task工程说明



## 整体说明

该工程有三块内容：

- 数据备份

- 报文搬运

- ES索引删除

| 数据备份 | 报文搬运 | ES索引删除 |
| :------: | :------: | :--------: |
| 数据备份 | 报文搬运 | ES索引删除 |
| 数据备份 | 报文搬运 | ES索引删除 |
| 数据备份 | 报文搬运 | ES索引删除 |

### 详细描述

1. 数据备份

   因为当前表中存入数据过多影响程序使用效率，所以将当前表中一部分数据转移至历史表中。

2. 报文搬运

   这里的报文是指程序解析完的报文，将解析完的报文搬运至ES中

3. ES索引删除

   ES中的索引不能够存放太久，会占用磁盘空间，因此也要清理。

#### 标题：

> 1~6级标题：文本大小依次减小，以#号开头，多少个#号就是多少级标题，#号和标题名称要并排写 
>
> ```
> #一级标题
> ##二级标题
> ###三级标题
> ####四级标题
> #####五级标题
> ######六级标题
> 注：在编辑器中这样写可以正常展示标题，但在GitHub中发现#和标题之间需要一个空格才能正常展示
> ```

##### 圆点符号：

> 插入圆点符号：编辑的时候使用的是星号 *，星号后面要有一个空格，否则为普通星号
>
> ```
> * 列表一
> * 列表二
> * 列表三
> ```

##### 示例：

* 列表一
* 列表二
* 列表三

##### 二级三级圆点符号示例：

> 二级圆点、三级圆点：多加一个Tab，即第二行一个Tab，第三行两个Tab
>
> ```一
> * 列表一
>     * 列表二
>         *列表三
> ```
>
> 
>
> * 一级圆点
>    * 二级圆点
>       * 三级圆点

#### 缩进：

> 缩进
>
> > 再次缩进
> >
> > > 再缩
> > >
> > > > 继续缩
> > > >
> > > > > 再缩

##### 缩进写法：

```
>缩进
>>缩进
>>>缩进
以此类推
```

#### 插入连接方式：

##### 写法：

​	[文本文字]（http://链接地址）

##### 示例：

[readme.md编写教程](https://blog.csdn.net/qq_31796651/article/details/80803599)

​	[百度](http://baidu.com)



#### 文本框显示：

> ```
> 输入  ```   这样的符号可以出现一个文本框，文本框里的符号不会被编译。
> 输入 > ```   这样的符号可以出现一个文本框，并在文本框前出现一个缩进。
> ```
>



#### 代码块高亮：  

下面示例是让java代码块高亮显示：

```java
@Override
protected void onDestroy() {
    EventBus.getDefault().unregister(this);
    super.onDestroy();
}

```

让java代码高亮的写法是：

```
​```java；注：这里的`是Tab按键上边的那个键
```



下面示例是让javascript代码块高亮显示：

```javascript
function validateForm()
{
  var x=document.forms["myForm"]["fname"].value;
  if (x==null || x=="")
  {
    alert("姓必须填写");
    return false;
  }
}
```

让javascript代码高亮的写法是：

```
​```javascript；注：这里的`是Tab按键上边的那个键
```

高亮显示支持多种变成语言：

![](C:\Users\Public\Pictures\Sample Pictures\1.png)

![2](C:\Users\Public\Pictures\Sample Pictures\2.png)

![3](C:\Users\Public\Pictures\Sample Pictures\3.png)

#### 图片展示：

##### 写法：

```
![图片名称](链接地址)
```

##### 示例：

```
![百度](https://www.baidu.com/img/bd_logo1.png)
```

##### 效果：

​	 ![图片名称](https://www.baidu.com/img/bd_logo1.png) 



#### 字体：

```
<font face="STCAIYUN">我是华文彩云</font>
<font color=gray size=5>color=gray</font>
<font color=#0099ff size=5 face="黑体">color=#0099ff size=5 face="黑体"</font>
```

```diff
+ 你再伽马路口没打开
- 点十几分不打算交就
```

<font color=#FF0000>我是红色字体</font> 

<font color='#FF0000'>我是红色字体</font> 

<font color="#FF0000">我是红色字体</font> 



## 表情

Github的Markdown语法支持添加emoji表情，输入不同的符号码（两个冒号包围的字符）可以显示出不同的表情。

比如`:blush:`

:blush:

:happy:
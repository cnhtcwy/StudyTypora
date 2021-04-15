# Typora使用说明

## 1 基本操作

### 1.1 内容目录

* 语法

~~~markdown
[toc]
~~~

* 效果

[toc]

### 1.2 标题

+ 语法

  ~~~markdown
  #           一级标题
  ##          二级标题
  ###         三级标题
  ####        四级标题
  #####       五级标题
  ######      六级标题
  ~~~

### 1.3 引用

~~~markdown
> 引用内容1
>> 引用内容2
~~~

- 效果

> 引用内容1
>
> > 引用内容2

### 1.4 文本居中

* 语法

  ~~~markdown
  <center>居中文本</center>
  ~~~

  

* 效果

  <center>居中文本</center>



## 2 代码

### 2.1单行代码

* 语法

  ~~~
  `String str1 = “Hello Typora”`
  ~~~

  

- 效果

  `String str1 = “Hello Typora”;`

### 2.2 多行代码

语法



~~~go
```(~~~) language
```              ->普通文本
```c             ->c语言
```python        ->python 
```c++           ->c++
~~~

效果



```c
int a = 10;
int b = 20;
int c = a + b;
cout << c << endl;
```

## 3 列表

### 3.1 无序列表

------

- 语法

  

  ```undefined
  * 无序列表1
  + 无序列表2
  - 无序列表3
  ```

- 效果

  - 无序列表1

  - 无序列表2

  - 无序列表3

### 3.2  有序列表

------

- 语法



```undefined
1. 有序列表1
2. 有序列表2
3. 有序列表3
```

### 3.3 任务列表

------

- 语法

  

  ```css
  - [ ] 橘子
  - [x] 苹果
  - [ ] 香蕉
  ```

- 效果

  - [ ] 橘子
  - [x] 苹果
  - [ ] 香蕉

### 3.3 表格

------

- 语法1(*直接输入*)

  

  ```ruby
  |姓名|性别|年龄|手机号|
  |:---|:--:|:--:|:---:|
  |张三|男|21|18975346876|
  |李四|女|23|17789548964|
  |王五|男|25|15876513546|
  ```

- 效果1

  | 姓名 | 性别 | 年龄 |   手机号    |
  | :--- | :--: | :--: | :---------: |
  | 张三 |  男  |  21  | 18975346876 |
  | 李四 |  女  |  23  | 17789548964 |
  | 王五 |  男  |  25  | 15876513546 |

- 语法2(*使用快捷键*)

  

  ```css
  快捷键[ctrl + T], 设置行数和列数
  ```

- 效果2

  |      |      |      |
  | ---- | ---- | ---- |
  |      |      |      |
  |      |      |      |
  |      |      |      |

## 4 链接

### 4.1 图片

------

- 语法1(*本地图片*)

  

  ```undefined
  直接拖进来
  ```

- 语法2(*网络图片*)

  

  ```cpp
  ![typora.jpg](https://upload-images.jianshu.io/upload_images/1538862-d91e815790b81e4a.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
  ```

![img](https:////upload-images.jianshu.io/upload_images/1538862-d91e815790b81e4a.jpg?imageMogr2/auto-orient/strip|imageView2/2/w/539/format/webp)

typora.jpg

### 4.2 超链接

------

- 语法1(*不显示链接网址*)

  

  ```csharp
  [百度](https://www.baidu.com)
  ```

- 效果1

  [百度](https://links.jianshu.com/go?to=www.baidu.com)

- 语法2(只显示url链接地址)

  

  ```css
  <www.baidu.com>
  ```

- 效果2

  <[www.baidu.com](https://links.jianshu.com/go?to=http%3A%2F%2Fwww.baidu.com)>

## 5 其他

### 5.1 斜体

------

- 语法

  

  ```undefined
  *斜体*
  _斜体_
  ```

- 效果

  *斜体*

### 5.2 加粗

------

- 语法

  

  ```undefined
  **加粗**
  __加粗__
  ```

- 效果

  **加粗**

### 5.3 加粗斜体

------

- 语法

  

  ```undefined
  ***加粗斜体***
  ___加粗斜体___
  ```

- 效果

  ***加粗斜体\***

### 5.4 下划线

------

- 语法

  

  ```xml
  <u>下划线</u>
  ```

- 效果

  <u>下划线</u>

### 5.5 删除线

------

- 语法

  

  ```undefined
  ~~删除线~~
  ```

- 效果

  ~~删除线~~

### 5.6 分割线

------

- 语法

  

  ```undefined
  ***
  ---
  ___
  ```

- 效果

  ------

### 5.7 注释

------

- 语法

  

  ```css
  Typora[^1]
  ```

- 效果

  Typora[^1]

### 5.8 符号输入

------

- 语法

  

  ```bash
  \\   反斜线
  \`   反引号
  \*   星号
  \_   底线
  \{ \}  花括号
  \[ \]  方括号
  \( \)  括弧
  \#   井字号
  \+   加号
  \-   减号
  \.   英文句点
  \!   惊叹号
  ```

- 效果

  \  `

### 5.8 特殊字符

------

- 语法

  

  ```bash
  &copy;      版权      
  &reg;       注册商标
  &trade;     商标
  &nbsp;      空格
  &amp;       和号
  &quot;      引号
  &apos;      撇号
  &lt;        小于号
  &gt;        大于号
  &ne;        不等号
  &le;        小于等于
  &ge;        大于等于
  &cent;      分
  &pound;     磅
  &euro;      欧元
  &yen;       元
  &sect;      节
  &times;     乘号
  &divide;    除号
  &plusmn;    正负号
  ```

### 5.9 表情

------

- 语法

  

  ```css
  :smiley:
  ```

- 效果

  :smiley:

## 6 操作

### 6.1 换行与换段

- 语法

  

  ```csharp
  [down]                  不换行继续写
  [enter]                 换行
  [shift + tab]           缩进
  ```

### 6. 2 快捷键操作

|     快捷键      |        作用        |      快捷键      |    作用    |
| :-------------: | :----------------: | :--------------: | :--------: |
|    Ctrl + 1     |     一级 标题      |     Ctrl + B     |  字体加粗  |
|    Ctrl + 2     |      二级标题      |     Ctrl + I     |  字体倾斜  |
|    Ctrl + 3     |      三级标题      |     Ctrl + U     |   下划线   |
|    Ctrl + 4     |      四级标题      |   Ctrl + Home    |  返回顶部  |
|    Ctrl + 5     |      五级标题      |    Ctrl + End    |  返回底部  |
|    Ctrl + 6     |      六级标题      |     Ctrl + T     |  创建表格  |
|    Ctrl + L     |      选中一行      |     Ctrl + K     | 创造超链接 |
|    Ctrl + D     |    选择一个单词    |     Ctrl + F     |    搜索    |
|    Ctrl + E     | 选中相同格式的文字 |     Ctrl + H     | 搜索并替换 |
| Alt + Shift + 5 |       删除线       | Ctrl + Shift + I |  插入图片  |



24人点赞



[工具类]()





作者：buddyhs
链接：https://www.jianshu.com/p/2f40341df631
来源：简书
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。



~~~
Ctrl+1  一阶标题    Ctrl+B  字体加粗
Ctrl+2  二阶标题    Ctrl+I  字体倾斜
Ctrl+3  三阶标题    Ctrl+U  下划线
Ctrl+4  四阶标题    Ctrl+Home   返回Typora顶部
Ctrl+5  五阶标题    Ctrl+End    返回Typora底部
Ctrl+6  六阶标题    Ctrl+T  创建表格
Ctrl+L  选中某句话   Ctrl+K  创建超链接
Ctrl+D  选中某个单词  Ctrl+F  搜索
Ctrl+E  选中相同格式的文字   Ctrl+H  搜索并替换
Alt+Shift+5 删除线 Ctrl+Shift+I    插入图片
Ctrl+Shift+M    公式块 Ctrl+Shift+Q    引用
~~~

$$
X^2
$$

> 常用快捷鍵

- 加粗： `Ctrl + B`
- 标题： `Ctrl + H`
- 插入链接： `Ctrl + K`
- 插入代码： `Ctrl + Shift + C` -- 无法执行
- 行内代码： `Ctrl + Shift + K`
- 插入图片： `Ctrl + Shift + I`
- 无序列表：`Ctrl + Shift + L` -- 无法执行
- 撤销： `Ctrl + Z`
- 一级标题： `Ctrl + 1` -- 以此类推




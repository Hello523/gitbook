# Markdown 语法

# 一级标题
```
# 一级标题
```

## 二级标题
```
## 二级标题
```

### 三级标题
```
### 三级标题
```

#### 四级标题
```
#### 四级标题
```

##### 五级标题
```
##### 五级标题
```
###### 六级标题
```
###### 六级标题
```

#### 插入链接

```
[链接名称](链接地址)
```

#### 插入图片

```
![图片标题](图片链接地址)
```

###### 段落引用

>Markdown是一个 Web 上使用的文本到HTML的转换工具，可以通过简单、易读易写的文本格式生成结构化的HTML文档。

```
>Markdown是一个 Web 上使用的文本到HTML的转换工具，可以通过简单、易读易写的文本格式生成结构化的HTML文档。
```

###### 段落嵌套

>Markdown是一个 Web 上使用的文本到HTML的转换工具，可以通过简单、易读易写的文本格式生成结构化的HTML文档。
>>锤子科技15年8月发布会上，老罗宣布锤子便签支持Markdown语法。我们可大胆预测，使用Markdown语法在移动端编辑会逐渐成为趋势。

```
>Markdown是一个 Web 上使用的文本到HTML的转换工具，可以通过简单、易读易写的文本格式生成结构化的HTML文档。
>>锤子科技15年8月发布会上，老罗宣布锤子便签支持Markdown语法。我们可大胆预测，使用Markdown语法在移动端编辑会逐渐成为趋势。
```


##### 强调语法
*斜体*

Markdown 使用星号（*）和底线（_）作为标记强调字词的符号

```
*斜体*
```

**加粗**

```
**加粗**
```

~~删除线~~

```
~~删除线~~
```

##### 行内标记

行内标记用反引号把它包起来''，例如：
这是一个`金色`的秋天
```
这是一个`金色`的秋天
```
#####自动邮箱链接

<*****@163.com>

```
<*****@163.com>
```

#####加强代码块

```javascript
for (var i = 0; i < 5; i++) {
  setTimeout(function() {
    console.log(i);
  }, 1000 * i);
}


```

#####列表

* 无序列表使用星号、加号或是减号作为列表标记，效果一样：

* 星号
+ 加号
- 减号

```
* 星号
+ 加号
- 减号
```

* 有序列表则使用数字接着一个英文句点：

1.你好
2.我好
3.他好

```
1.你好
2.我好
3.他好
```

#####代码区块

* 要在 Markdown 中建立代码区块很简单，只要简单地缩进 4 个空格或是 1 个制表符就可以，例如，下面的输入

    holle world

```
    holle world
```
#####加强代码块
* 使用“```”+“语言名称”进行标记

```javascript
for (var i = 0; i < 5; i++) {
  setTimeout(function() {
    console.log(i);
  }, 1000 * i);
}

```
![效果代码](http://images2015.cnblogs.com/blog/891444/201705/891444-20170505150326320-694885915.png)



#####分隔线
* 你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：


---

```
***
---
* * *
```

#####脚注（footnote）

效果：


hello[^1]   
[^1]: hi
```
hello[^1]   
[^1]: hi
```

#####表格

|项目|类型|框架|
|-----|:-----:|-----:|
|kr-admin|pc|react|
|左对齐|居中|右对齐|

```
|项目|类型|框架|
|-----|:-----:|-----:|
|kr-admin|pc|react|
|左对齐|居中|右对齐|
```
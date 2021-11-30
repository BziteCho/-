# Markdown语法的学习

## 标题

#➕空格就是H1

##➕空格就是H2以此类推到H6

## 区块引用

> 着就是引用符号>

## 列表

* Red
* Green
* Blue

+ Red
+ Green
+ Blue

- Red
- Green
- Blue

1. bird
2. McHale
3. parish

列表中的输出不会影响HTML中的显示，在HTML中，显示如下

```html
<ol>
<li>Bird</li>
<li>McHale</li>
<li>Parish</li>
</ol>
```

## 代码区块

```shell
这是一个代码块
```

## 分隔符

---

----

****

## 区段元素

### 链接

this is [an example](http://www.baidu.com "title")

[foo]: http://www.baidu.com
[google]: http://google.com "google"

### 强调

*这是一个强调的句子*
**这个是一个强调的句子**

_这是一个强调_

__这个也是强调__

### 代码

```hello workd```

符号在table键的上方

```java
```➕上语言的名称
    public static void main(String[] args){
    
}
```





## 图片

![美女](https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fpic1.win4000.com%2Fm00%2F97%2F17%2Fed95cf41b0b69084e46221c4a51afd18.jpg&refer=http%3A%2F%2Fpic1.win4000.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1640863750&t=bc2d415d2d3d1d83d56b48cade07ee80 美女)

## 

### 表格

| 姓名 | 性别 | 生日 |
| ---- | ---- | ---- |
|      |      |      |

我还是推荐右键

|姓名|性别|
|--|--|
|张三|23|


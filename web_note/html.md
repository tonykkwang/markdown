
# HTML

## 1.HTML描述  
HyperText Markup Language

标签(Markup Tag)：用< >包裹的具有一定含义的内容，如：<strong>  </storng>

HTML不是编程语言，没有逻辑。只是一种标记语言。

## 2.HTML结构
```
<!DOCTYPE html>  //html5解析
<html>
<head>
<meta charset="utf-8"> <!--编码方式-->
<title>标题</title>

</head> <!头部，网页相关设置，不显示>
<body>
<p>段落</p>
<!脚本>
<script> 


</script>


</body>
</html>
```
+ meta 元 主要用来完成对应设置
+ div 布局 占据一行
`<div></div>`
+ span 布局 不会占据一行
`<span></span>`
+ h1~h6 标题
`<hx></hx>`
+ p 段落
`<p></p>`
+ br 换行
`<br/>`
+ hr 横线
`<hr/>`
+ a 链接<br/>
属性：title=”“ 描述 <br/>
属性：target=”_blank“ 新页面打开 <br/>
属性：title=”_self“ 本页面打开 <br/>
`<a href="http://www.google.com" title="google" target="_blank">google</a>`
+ img 图片 <br/>
属性： src=”“   源 <br/>
属性： title=”“ 描述 <br/>
属性： alt=”“   无法打开时的提示 <br/>
`<img src="A1.jpg" alt="无法打开时的提示" title="提示"/>`
+ webstrom 注释 crtl+shift+/
+ ul 无须列表
```
    <ul>
        <li>1</li>
        <li>2</li>
        <li>3</li>
    </ul>
```
+ ol 有序列表
```
    <ol>
        <li>1</li>
        <li>2</li>
        <li>3</li>
    </ol>
```
+ q 双引号 `<q>引用文本</q>`
+ address 地址信息
```
    <address>
        <p>电话：1111111</p>
        <p>地址：aaaaaaa</p>
    </address>
```
## 3.标签属性
标签属性分为 通用属性 自有属性和自定义属性。</br>
+ 通用属性:所有标签都具有的属性。</br>
  id:  标签的id 唯一的</br>
  ```
    <p id="p1">段落1</p>
    <p id="p2">段落2</p>
  ```  
  class:类名  </br>
  ```
  
  
  ```
  style:样式  </br>
  ```
  <p style="color: red;height: 300px;">样式</p>
  ```
  title:鼠标移动到标签显示内容</br>
  ```
  <p title="你好">hello</p>
  ```
  + 自定义标签属性：data-xxx<br/>
    作用：通常用于传值或用于图片懒加载等方面。
    
属性名 = “属性值”
```
    <p title="段落" class="content" id="content">段落段落段落段落段落,<br/>
        段落段落段落段落段落段落</p>
 ```
## 4.单双标签
### 单标签：<br/>
+ 换行`<br/>`<br/>
+ 水平线`<hr/>`<br/>
+ 图片`<img />`<br/>
### 双标签：<br/>
```
<p></p>
<h1></h1>
```
## 5.文本格式化标签
+ 强调:主要作用为SEO搜索引擎，便于提取对应关键字
+ 浏览器最小字号12px
+ b strong 加粗 strong强调作用 行级标签
```
    <b>加粗</b>
    <strong>加粗且强调</strong>
```
+ i em  em 斜体 em强调作用 行级标签
```
    <i>斜体</i>
    <em>斜体且强调</em>
```
+ small big 字号加减 html5淘汰了big标签 行级标签
```
    <p>正常字号</p>
    <small>小一号</small>
    <big>大一号</big>   
```
+ sub sup 上标 下标 调整文字显示基线，字号小一号
```
    <p>上标：X<sup>2</sup>+Y <sup>2</sup> = Z </p>
    <p>下标：X<sub>1</sub>+X <sub>2</sub> = Y </p>
```
+ pre  预格式化文本 保留文本换行空格及宽度 块级标签
## 6.HTML实体转义
+ 以&开始，;结束
+ 空格 `&nbsp;`
+ 乘号 `&times;`

## 7.块级元素 行级元素
### 块级元素 display:block
+ 独占一行 宽度高度可控，如未设置其宽度，默认铺满整行<br/>
  可包含块级行级元素
```
 <p style="width: 300px;height: 50px;background: gray;">line</p>
```
### 行级元素 内联元素 display:inline
+ 非独占一行，和相邻的行级元素占同一行，自动换行。，<br/>
  宽度高度不可控<br/>
  只能包含行级元素
### 块级元素-->行级元素
+ display:inline
```
    <p style="width: 300px;height: 50px;background: gray;display: inline">line</p>
    <!--转换为行级元素后width height失效-->
```
### 行级元素-->块级元素
+ display:block

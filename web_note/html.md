
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

## 3.标签属性
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
+ 行级标签：不会自动换行，不识别宽高
+ 块级标签：自动换行，支持宽高
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

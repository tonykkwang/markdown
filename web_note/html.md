
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
```
<meta> 元，主要用来完成对应设置
<div></div> 用来布局的，无含义
<!占据一行>
<span></span> 用来布局的，无含义
<!不会占据一行,行内布局>
<hx></hx>  标题
<p></p> 段落 =回车
<br/>   换行
<hr/>   横线
<a>  超级链接

<a href="http://www.google.com" title="google" target="_blank">google</a>
<!title link描述文字>
<!target="_blank" 新页面打开 >
<!target="_self" 本页面打开 >

<img src="A1.jpg" alt="无法打开时的提示" title="提示"/>
<!img src 图片源>
<!title 提示>

    <!--快捷键 ctrl+shift+/ webstorm-->
    <!--ul无须列表-->
    <ul>
        <li>1</li>
        <li>2</li>
        <li>3</li>
    </ul>
    <!-ol有序列表-->
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
单标签：
***
1.换行`<br/>`<br/>
2.水平线`<hr/>`<br/>
3.图片`<img />`<br/>
***
双标签：
***
```
<p></p>
<h1></h1>
```
## 5.文本格式化标签
```
    <!--文本格式化标签-->
    <!--强调主要作用为SEO搜索引擎，便于提取对应关键字-->
    <!--行级标签：不会自动换行，不识别宽高-->
    <!--块级标签：自动换行，支持宽高-->
    <!--浏览器最小字号12px-->
    <!--b strong 加粗 strong强调作用-->
    <!--strong具有强调作用-->
    <!--b strong 都是行级标签 不自动换行-->
    <b>加粗</b>
    <strong>加粗且强调</strong>
    <!--i em 斜体-->
    <!--em 其强调作用-->
    <!--i em 行级标签 -->
    <i>斜体</i>
    <em>斜体且强调</em>
    <!--pre 预格式化文本 保留文本换行空格及宽度-->
    <!--pre 块级标签-->
    <pre>预格式化文本
            保留文本换行空格及宽度</pre>
    <!--small big 字号加减 html5淘汰了big标签-->
    <!--small big 行级标签-->
    <p>正常字号</p>
    <small>小一号</small>
    <big>大一号</big>
    <!--sub sup 上标 下标-->
    <!--调整文字显示基线，字号小一号-->
    <p>上标：X<sup>2</sup>+Y <sup>2</sup> = Z </p>
    <p>下标：X<sub>1</sub>+X <sub>2</sub> = Y </p>

```

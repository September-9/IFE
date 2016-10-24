### figure  用作文档中插图的图像：
```
<figure>
  <figcaption>插图的标题</figcaption>
  <img src="xxx.jpg" />
</figure>
```
### 一些相对陌生的H5新加的语义话标签
<ul>
  <li>artical</li>
  <li>aside</li>
</ul>

### 问题
1、文章作者有什么特定的标签吗?<br />
2、input标签前面空出来的一点点是什么？<br />
本质应该是html页面上存在的空白字符
```
解决方案:
1、设置父元素的font-size:0;
2、设置父元素的display:table;
3、设置负的margin值;
4、删除label和input之间换行符，也就是写到一行
```

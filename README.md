## Hello World

You can use the [editor on GitHub](https://github.com/xiaobai2233/xiaobai.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown
###Bootstrap常用
.container-fluid   总框 然后row这是一个bootstrap行测试背景大小well
.btn 按钮样式
.btn-block 块级按钮
required input必须输入内容
image-responsive 自适应图片
btn-primary主要按钮样式 蓝色
btn-default按钮默认样式
btn-info 用户点击浅蓝色
btn-danger 警告按钮
用含row的div包住col
	.col-md-*中等
	.col-xs-*特别小
<link rel="stylesheet" href="//cdn.bootcss.com/font-awesome/4.2.0/css/font-awesome.min.css"/>图标库
赞<i class="fa fa-thumbs-up"><i>
踩<i class="fa fa-thumbs-down"><i>    标签 内不填充内容
提示<i class="fa fa-info-circle"></i>
删除<i class="fa fa-trash"></i>
提交按钮（纸飞机）<i class="fa fa-paper-plane"></i>
表单输入框input 加类form-control
https://cdn.bootcss.com/animate.css/3.5.2/animate.css   动画库
按钮不可选
$("button").prop("disabled",true);

###Jquery常用
$(document).ready(function( ){      });  加载完页面后执行
$("demo").css("color"," red");   改变样式选择类 .demo  ID #demo
$("demo").clone( );  克隆
 $("demo").clone( ).appendTo("#demo");   克隆并移动到某ID后；
$("demo").parent( );  选中父级元素
$("demo").text(  );获取元素文本内容
$("demo").text("    ");改变内容
$("demo").html(  )；获取元素所有内容（包括标签）
$("demo").html("<div>hello world</div>");改变元素所有内容
$("button").prop("disabled",true);使按钮不可选中
$("demo").remove( );删除该元素
$("demo").removeClass( );删除该元素某CSS
$("demo").appendTo("#demo");  将选中元素移动到某元素中（剪切粘贴）
$("demo").children( );  选中子元素


# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/xiaobai2233/xiaobai.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

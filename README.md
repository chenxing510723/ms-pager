# ms-pager
avalon2的分页插件

拥有两个模板,一个是使用fontawesome,另一个则可以让你定义文本的

如果你使用fontawesome，需要在head中单独添加如下三个链接

```html
<link href="//netdna.bootstrapcdn.com/twitter-bootstrap/2.3.2/css/bootstrap-combined.no-icons.min.css" rel="stylesheet">
        <link href="//netdna.bootstrapcdn.com/font-awesome/3.2.1/css/font-awesome.css" rel="stylesheet">
        <!--[if IE 7]>
          <link rel="stylesheet" href="//netdna.bootstrapcdn.com/font-awesome/3.2.1/css/font-awesome-ie7.min.css">
        <![endif]-->

```
使用[兼容性极好的3.2.1](http://fontawesome.io/3.2.1/icons/)

## 配置说明
* index.js 中**is_ie** 为IE8开启监听，查看location变化，从而支持浏览器后退功能;
* index.js 中**is_more** 为支持单页应用，具体使用可参考源码片段;

http://caibaojian.com/fontawesome/get-started.html
http://stackoverflow.com/questions/9809351/ie8-css-font-face-fonts-only-working-for-before-content-on-over-and-sometimes
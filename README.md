peento-blog-comment-disqus
===========================

给peento-blog的文章页面增加 [Disqus评论框](http://disqus.com/)


使用方法
========

```JavaScript
app.use('blog');

// 在blog插件后执行
app.use('blog-comment-disqus');
```


配置
====

```JavaScript
config.disqus = {
  name: '在Disqus网站上注册的short_name'
};
```


授权协议
========

**The MIT License**

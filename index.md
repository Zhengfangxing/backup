---
layout: page
title: Hello 欢迎来到郑方行的博客!
tagline: 微信:475164744
---
{% include JB/setup %}

CSDN: [郑方行](https://blog.csdn.net/weixin_41388729)

Spring Boot Complete usage and documentation available at: [图文并茂之Spring Boot从入门到精通](https://blog.csdn.net/weixin_41388729/article/details/87997531)

## 座右铭

### **但行好事,莫问前程**
    
## 博客列表 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 联系我们

有任何建议或者意见,请联系我boyisxuxu@gmail.com
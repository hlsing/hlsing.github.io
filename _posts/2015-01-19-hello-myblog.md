---
layout: post
title: hello myblog
description: "say hello to my blog"
category: sample-post
tags: [示例文章, 高亮]
imagefeature: 
comments: true
share: true
---
### hello myblog,I coming!

### Pygments高亮代码块

#### C

{% highlight c %}
#include <stdio.h>
int main(void)
{
    printf("Hello World\n");
    return 0;
}
{% endhighlight %}

#### Java

{% highlight java linenos %}
class helloworld
{
    public static void main(String args[])
    {
        System.out.println("Hello World");
    }
}
{% endhighlight %}

### 标准代码块

#### Python

~~~ python
#!/usr/bin/python
printf("Hello World")
~~~

### 行内代码

#### Bash

`echo "Hello World"`

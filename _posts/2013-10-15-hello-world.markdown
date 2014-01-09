---
layout: post 
title: Hello World! 世界泥嚎！
author: Hy
category: a
---

<p>Jekyll+Github环境初步搭建完成~~~</p>
{% highlight c %}
/* hello world demo */
#include <stdio.h>
int main(int argc, char **argv)
{
    printf("Hello, World!\n");
    return 0;
}
{% endhighlight %}
<p>{{ page.date | date_to_string }}</p>

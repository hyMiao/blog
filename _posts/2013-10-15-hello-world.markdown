---
layout: post 
title: Hello World! 世界泥嚎！
author: Hy
---

<p>Hello world</p>
{% highlight c %}
/* hello world demo */
#include <stdio.h>
int main(int argc, char **argv)
{
    printf("Hello, World!\n");
    return 0;
}
{% endhighlight %}

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
<p>{{ page.date | date_to_string }}</p>

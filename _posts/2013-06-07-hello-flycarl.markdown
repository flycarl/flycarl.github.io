---
layout: post
title:  "flycarl is coming back"
date:   2013-06-07 17:04:32
categories: jekyll update
---

hi everybody, I am back, last time use otcpress and lose all my post, this time 
I decide to use jekyll to rebuild the blog again.

thanks for visiting~

and now I test the highlighting code snippets as follow

{% highlight ruby linenos %}
def show
  @widget = Widget(params[:id])
    respond_to do |format|
        format.html # show.html.erb
        format.json { render json: @widget }
    end
end
{% endhighlight %}

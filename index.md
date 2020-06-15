---
#
# 蚁点工作室，欢迎合作， 合作电话：18668927276
#
layout: default
title: 蚁点工作室官方网站 - 让所有传统企业完成上云信息化服务 - AndotStudio WebSite - studio.andot.org
time: 2011-09
---

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

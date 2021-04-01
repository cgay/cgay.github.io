---
layout: post
title:  "New Blog"
date:   2021-04-01 13:51:18 +0000
categories: news
---

This is my new blogospace, using GitHub Pages and Jekyll to generate a simple
static site. I have a few posts still at [my old Wordpress
blog](http://carlgay.wordpress.com) which I'm still not sure if I'll migrate
over here. We'll see how it goes.

Meanwhile, let's see if Jekyll knows how to highlight Dylan code...

{% highlight dylan %}

define method fib ()
  let a = 0;
  let b = 1;
  method ()
    let r = a + b;
    a := b;
    b := r;
    a
  end
end;

let f = fib();
for (i from 1 to 20) format-out("%= ", f()) end

{% endhighlight %}


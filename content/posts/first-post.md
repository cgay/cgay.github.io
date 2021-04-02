---
title: "First Post"
date: 2021-04-02T13:35:01Z
draft: false
---

This is my new blogospace, using GitHub Pages and [Hugo](https://gohugo.io/) to
generate a simple static site. I have a few posts still at [my old Wordpress
blog](http://carlgay.wordpress.com) which I'm still not sure if I'll migrate
over here. We'll see how it goes.

Meanwhile, since I'll be mostly writing about geeky Dylan stuff, let's see if
Hugo knows how to highlight Dylan code...

```dylan
define method factorial (n == 0) 1 end;  // called when n = 0
define method factorial (n == 1) 1 end;  // called when n = 1
define method factorial (n)              // called for any other n
  n * factorial(n - 1)
end;
```

Nope, so let's fix that! I'll be working on a Dylan lexer for the [Chroma
syntax highlighter](https://github.com/alecthomas/chroma) next.

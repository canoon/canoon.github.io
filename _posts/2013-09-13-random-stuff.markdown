---
layout: post
title:  "Random Stuff"
date:   2013-09-13 16:01:19
---

## Perl

All are true:

{% highlight perl %}
"" == "asdf";
"asdf" == "asdf";
"" != "infant";
"infant" == "infant";
"" != "nanna";
"nanna" != "nanna";
{% endhighlight %}

PS: Turning on warnings is cheating.

## A hashbang to improve the syntax of python

{% highlight ruby %}
#!/usr/bin/python -cimport sys; import subprocess; subprocess.call('ruby ' + ' '.join(sys.argv[1:]), shell=True);

5.times {
    puts "Hello World"
}
{% endhighlight %}

## Security whats that?

> Nobody knows how much space should be reserved for name.  So, calling
> openpty() or forkpty() with non-NULL name may not be secure. 

[http://man7.org/linux/man-pages/man3/openpty.3.html](http://man7.org/linux/man-pages/man3/openpty.3.html)


  

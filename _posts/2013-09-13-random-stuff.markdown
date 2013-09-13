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

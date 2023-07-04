---
layout: post
title:  "The most basic program!"
date:   2023-07-04 10:38:10 +0530
categories: java
---

So this is how you can command your computer through java to print out a partciular string for you.

{% highlight java %}
public class Printing {
    public static void main(String[] args) {
System.out.println("ENTER YOUR STRING HERE");
    }
}
{% endhighlight %}

A handy shortcut for System.out.println is sout

A line break can be introduced in the program as well.

{% highlight java %}
public class Printing {
    public static void main(String[] args) {
System.out.println("ENTER YOUR\n" + "STRING HERE");
    }
}
{% endhighlight %}

NOTE :

{% highlight java %}
public class Printing {
    public static void main(String[] args) {
System.out.println("ENTER YOUR STRING HERE");
    }
}
{% endhighlight %}

and 

{% highlight java %}
public class Printing {
    public static void main(String[] args) {
System.out.println("ENTER YOUR " + "STRING HERE");
    }
}
{% endhighlight %}

will produce the same output i.e. ENTER YOUR STRING HERE

Numbers may be used outside " " for the purpose of calculations. Otherwise like letters they must be place in " ".






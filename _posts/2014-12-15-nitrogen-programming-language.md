---
layout: post
title:  "Nitrogen Programming Language"
author: "Lee Keitel"
date:   2014-12-15 21:08:00
categories: nitrogen
---
The past two days I thought I'd take a break from my normal projects (especially with school just about over) and attempt to learn how exactly a programming language works in the first place. I've always wondered this and even pondered creating one myself. Well now I have. It's not perfect, it's not even finished yet, but it's mine. And I'm so happy with it. I've named the language Nitrogen. Why you ask? Because my projects have typically taken a garden/plant theme when it comes to names. My primary project is named [Dandelion](https://github.com/onesimus-systems/dandelion), two other projects (that never really made it off the ground at all) were named Rose Petal and Garden. So I thought since Nitrogen is a vital element to healthy plant production, what better name to give that which gives a coding project life, that being the language it's written in. Hence the Nitrogen programming language.

Nitrogen is a Lisp-based language that uses S-expressions and Q-expressions (quoted expressions) to represent both code and data. In Nitrogen, like all Lisp dialects, everything is a list. For me it took a bit to get used to this stange way of doing things. I was so used to "normal" languages like Go, PHP, Python, C, etc. that don't have near the number of () and {} and have the operators between that which they operate on. But after playing with it, I find it quite logical. I doubt I'll ever start using Nitrogen for any significant project. But hopefully someday it will have enough functionality that I can use it as a scripting language or something like that.

For more information on Nitrogen, including documentation that will eventually be posted, go to the [Nitrogen Page](/nitrogen).

Here's a quick sample of a simple printing function (I'm still working on a concat function for strings):

{% highlight lisp %}
(fun {printHi s} {
    print s
})
(printHi "Hi, Tom")
#=> prints "Hi, Tom" to STDOUT
{% endhighlight %}

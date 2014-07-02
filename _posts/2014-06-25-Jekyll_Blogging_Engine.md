---
layout: post
title: The Jekyll Blogging Engine
intro: Jekyll is a clever, powerful Blog Engine. In this Post, I'll show you the advantages of Jekyll, it's customization and a lot more...
coverlink: /assets/images/jekyll_cover.png
---

Hi! This is my first Test Post, which I created with Jekyll. Let's explore the Power of Jekyll (Blog Engine) its themes and Markdown (Text Formatting Syntax)

I downloaded <a href="http://jekyllrb.com/">Jekyll</a> today (it's quite costly under windows) and I'm just fascinatet, how Jekyll works. The **simplicity on the surface** and the **cleverness at the inside**.
The fact that Jekyll works with Ruby makes it also very interessant. I'm not expirienced, not even familiar with Ruby, but I know, that it's a very powerful language.

> Jekyll transform your plain text into static websites and blogs.

## Install Jekyll


Here are some links for install Jekyll on Windows:

- <a href="http://jekyllrb.com/docs/windows/"><cite>Official Jekyll Windows Installation Guide</cite></a>
- <a href="http://www.madhur.co.in/blog/2011/09/01/runningjekyllwindows.html">Running Jekyll on Windows by Madhur Ahuja</a>
- <a href="http://flatshaded.com/2013/05/installing-jekyll-on-windows/">Install Jekyll on Windows. Good if you become errors.</a>

These are the one I used, and they're really helpful!

## Themes for Jekyll

###Cool Themes
The default theme of jekyll isn't very stylish, so I searched some cool Themes. I didn't want to make one at my own, I'd rather take an existing one and modify it. That's because then, I don't have to read thousands of docs, I just can learn from examples. Maybe I'll make my own Theme, but that could wait.

These are my favourite themes:

<dl>
    <dt><a href="http://andhyde.com/">Hyde</a></dt>
    <dd>Jep, that's the one right here.</dd>

    <dt><a href="http://jekyllthemes.org/themes/vanilla-bean-creme/">Vanilla Bean Cream</a></dt>
    <dd>I think, this theme could be styled very nice!</dd>

    <dt><a href="http://m3xm.github.io/hikari-for-Jekyll/">Hikari</a></dt>
    <dd>Nice, simple and clean theme. Very colorful. Like it.</dd>
</dl>

###Install Themes
The Installation of Themes, is **very easy**. You just have to replace the auto-generated content with the theme content ((which you mostly can download on GitHub).
As example here is the GitHub Repository of the Hyde Theme: <a href="https://github.com/mdo/hyde">https://github.com/mdo/hyde</a>


##Gist Integration

A very interesting feature is the possibility to display Gists very easy. So at first, here's a Gist I created for <a href="http://140byt.es">140 Bytes</a>. A working Phone Number Validator in just 97 Bytes of code.

{%gist 8849169 index.js%}

So, what do you think, how much I had to write, to display this gist? An AJAX Request, a complicated API-Call or even a Third-Party Script Inclusion?

Here you are (whitout the backslash at the start):

{% highlight js %}
{\%gist 8849169 README.md %}
{% endhighlight %}

##Code Highlighting
Code Highlighting is very easy in Jekyll. And also It looks very nice.

Just Type (again without backslashes): 
{%highlight js%}
{\% highlight language %} 
Code to display
{\%endhighlight%}
{% endhighlight %}

####HTML
{% highlight html %}
<body>
    <h1 class="heading" onclick="clickTrigger();">Hello World</h1>
</body>
{% endhighlight %}

####CSS
{% highlight css %}
.heading{
    color: #c0392b;
    font-size: 28px;
    text-align: center;
}
{% endhighlight %}

####JS
{% highlight js %}
function clickTrigger(){
    alert("Clicked Me!");
}
{% endhighlight %}

Looks very nice, I guess :)

### Images

Of course, you can also insert images and downloadable files. If you have trouble with it visit <a href="http://jekyllrb.com/docs/posts/">this official Guide</a>.

![Jekyll Logo](http://{{site.url}}/assets/images/jekyll.png "Jekyll Logo")
[Example PDF File](http://{{site.url}}/assets/docs/example.pdf "Example PDF File")

### Conclusion

Jekyll is a very nice Blog Engine for Devs, but for people who never interact with code it's too complicated.
I personally like Jekyll Very much and I'll use it as my Blog Engine because it's so adaptable and nerdy :)

<hr />

Thanks for Reading and a nice Day

*Tobi*

-----
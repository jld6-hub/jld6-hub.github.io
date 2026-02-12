---
layout: post
title: Everything You Need to Know About Justine Dunaway
subtitle: I'm very awesome!
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test, post, beautiful]
comments: true
mathjax: true
author: Justine Dunaway
---

{: .box-success}
I am a very cool person with absolutely no computer science knowledge.  If you're reading this it's actually a miracle, because it means I was somehow able to figire out how to make a blog post! Despite my lack of computuer knowledge, I pride myself on my creativity, and I hope to use that in a way I never have before in this class. Join me in my journey in becoming a computer science genius, or at least in becoming a little better at using my laptop.

**If you would like to learn more...**

## Here is more info about me!



My name is Justine, I am a junior. I am a comparative literature major and I play softball at Williams College.
![Softball](https://jld6-hub.github.io/assets/DSC_5157_Original.jpeg)

I also sing in an acapella group and do improv, I love to perform, or at least try to!

![Theatre](https://jld6-hub.github.io/assets/DSC_2941.jpeg)

I have very minimal sewing experience. I did a sewing camp when I was in the third grade where I learned to make my own skirt, but I have since lost that knowledge. I can fix my ripped clothes and small things like that, but I'm excited to learn how to embroider. 

I have no programming experience except when I had to use R in a class last year. I don't know if that counts but it was horrifying. 

Something boring about me is that I hate pickles. I think that's boring because there are some people who don't like pickles and some people who do, so I don't feel like that opinion is very special.

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})

<details markdown="1">
<summary>Click here!</summary>
Here you can see an **expandable** section
</details>

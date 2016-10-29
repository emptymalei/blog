---
layout: post
title:  "Welcome to Neuron Sketch!"
date:   2016-10-22
author: ErbB4
category: 
- category 1
- category 2
- category 3
comments: true
tags:
- tag 1
- tag 2
- tag 3
---

* ToC
{:toc}

## Introduction

Jekyll is a static site generator written in Ruby. It turns markdown files into web pages. In principle it would be a painful process to write blog in this way. However, we are so lucky that GitHub Pages can automatically generate the website. All you need to do is to write in markdown.


## Configuration




## Writing

There are three different kinds of article, post, page, and collection.

### Post

All posts are placed under `_posts` folder. All the file names should start with a date in order for jekyll to parse them.


### Page

Just like HTML, create a page anywhere and you get the web page. All pages should start with the meta data.

### Collection

Checkout our `neuronstar.github.io/_spiking-neuron-models`



## Typography

Basically the typography follows [kramdown](http://kramdown.gettalong.org/) syntax. Here are some extras to Jekyll.

The basics are

1. **Emphasis**
2. *Italic*

This is also an example of ordered list.

An unordered list is a list with `*`

* **Emphasis**
* *Italic*
	* Nested


And math

\begin{equation}
\alpha = \beta + \gamma
\end{equation}


### Footnotes

Footnotes are particularly useful for writing.[^1]


### Table of Contents

To generate table of contents, insert 

```
* ToC
{:toc}
```

in the beginning of the post.


### Code Blocks

For example, Code Blocks is written as (please check out the source file)

{% highlight python %}
Here is your code
{% endhighlight %}

or even simpler

```
simple code blocks
```

Sometime we can design more complicated styles and codes, for example I have [this page](http://openmetric.org/typography/).

### Images


Images are inserted in figure environment.


<figure markdown="1">
![]({{ site.baseurl }}/assets/posts/welcome-to-neuron-sketch/a-test-images.jpg)
<figcaption>Image caption is here</figcaption>
</figure>

with `markdown="1"`, you are allowed to use markdown inside this tag.

Images without captions:

![]({{ site.baseurl }}/assets/posts/welcome-to-neuron-sketch/a-test-images.jpg)

Please note the images are placed in the path `/assets/posts/some-name/image-name`, the `some-name` is usually the name of the posts for easy file management.



[^1]: This is a footnote.
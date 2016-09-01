---
layout: post
title:  "First Post"
date:   2016-08-31
categories: update
---

Welcome to my programming/hardware development blog! To begin I have to apologize for my writing and formatting, both of which are works in progress. As this blog develops I hope to document some interesting projects and research, but for now this is all I have got.

My interests are primarily in computer hardware and low-level system programming, hence setting up this blog was an exercise I probably wasn't prepared for. Anyone brave enough to look at the HTML and CSS code behind this page would probably gasp in horror, but I would be lying if I told you I was an expert.

This page was made using [Github Pages][gh-pages-link] and [Jekyll][jekyll-link], which was a much larger undertaking than I originally thought. I fell in love with the theme from one of the Github page templates, but quickly realized that it didn't have anything to do with Jekyll and its blogging support, it was just a single page that looked pretty.

Jekyll on the other hand had a very easy way to create a blog using only a single command (`bundle exec jekyll new`), with numerous other online templates that you could download for free. None of them really appealed to me however, so I wound up merging the Github generated stylesheets with the Jekyll default template. It's not perfect by any means, but I think it looks kind of cool and I encourage anyone to download the Github repository for this page and use it themselves.

{% highlight c %}

#include <stdio.h>

int main() {
	printf("Hello Blog!\n");
	return 0;
}

{% endhighlight %}

[jekyll-link]: http://jekyllrb.com
[gh-pages-link]:   https://pages.github.com/

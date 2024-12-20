---
title: "Tag Plugins"
date: "2014-03-16 10:17:16"
tags: plugins
categories: Docs
description: "Introduce tag plugins in freemind."
feature: https://dvesti.github.io/blox/images/tag-plugins/plugins.jpg
cover: https://dvesti.github.io/blox/images/tag-plugins/plugins.jpg
toc: true
---

The freemind theme offers several new tag plugins, so as to fully take advantages of Bootstrap.

To use these tag plugins, you need to install [hexo-tag-bootstrap](https://github.com/wzpan/hexo-tag-bootstrap) first. In your blog root folder, execute the following command:

```
$ npm install hexo-tag-bootstrap --save
```

Then you can use these tag plugins in your blog, as easily as you normally do using hexo tag plugins. 

<!-- more -->

## Text Color ##

Convey meaning through color with a handful of emphasis utility classes. These may also be applied to links and will darken on hover just like our default link styles.

### Syntax ###

```
{% textcolor [style] %}
  text string
{% endtextcolor %}
```

### Examples ###

```
{% textcolor muted %}
Fusce dapibus, tellus ac cursus commodo, tortor mauris nibh.
{% endtextcolor %}

{% textcolor primary %}
Nullam id dolor id nibh ultricies vehicula ut id elit.
{% endtextcolor %}

{% textcolor success %}
Duis mollis, est non commodo luctus, nisi erat porttitor ligula.
{% endtextcolor %}

{% textcolor info %}
Maecenas sed diam eget risus varius blandit sit amet non magna.
{% endtextcolor %}

{% textcolor warning %}
Etiam porta sem malesuada magna mollis euismod.
{% endtextcolor %}

{% textcolor danger %}
Donec ullamcorper nulla non metus auctor fringilla.
{% endtextcolor %}
```

### Results ###

{% textcolor muted %}Fusce dapibus, tellus ac cursus commodo, tortor mauris nibh.{% endtextcolor %}

{% textcolor primary %}Nullam id dolor id nibh ultricies vehicula ut id elit.{% endtextcolor %}

{% textcolor success %}Duis mollis, est non commodo luctus, nisi erat porttitor ligula.{% endtextcolor %}

{% textcolor info %}Maecenas sed diam eget risus varius blandit sit amet non magna.{% endtextcolor %}

{% textcolor warning %}Etiam porta sem malesuada magna mollis euismod.{% endtextcolor %}

{% textcolor danger %}Donec ullamcorper nulla non metus auctor fringilla.{% endtextcolor %}

## Buttons ##

Inserts a button with target links, text and specified color.

### Syntax ###

```
{% btn url text [style] %}
```

### Examples ###

```
{% btn http://hahack.com hahack %}

{% btn http://hahack.com hahack primary %}

{% btn http://hahack.com hahack success %}

{% btn http://hahack.com hahack warning %}

{% btn http://hahack.com hahack danger %}

{% btn http://hahack.com hahack info %}
```

### Results ###

{% btn http://hahack.com hahack %}

{% btn http://hahack.com hahack primary %}

{% btn http://hahack.com hahack success %}

{% btn http://hahack.com hahack warning %}

{% btn http://hahack.com hahack danger %}

{% btn http://hahack.com hahack info %}

## Labels ##

Inserts a label with text and specified color.

### Syntax ###

```
{% label text [style] %}
```

### Examples ###

```
{% label default %}

{% label warinng warning %}

{% label success success %}

{% label danger danger %}

{% label primary primary %}

{% label info info %}
```

### Results ###

{% label default %}

{% label warinng warning %}

{% label success success %}

{% label danger danger %}

{% label primary primary %}

{% label info info %}

## Badges ##

Inserts a badge with text.


### Syntax ###

```
{% badge text %}
```

### Examples ###

```
{% badge 42 %}
```

### Results ###

{% badge 42 %}

## Alerts ##

Inserts alert messages with text and specified color.

### Syntax ###

```
{% alert [style] %}
   Alert string
{% endalert %}
```

### Examples ###

```
{% alert warning %}
Best check yo self, you're not looking too good.
{% endalert %}

{% alert danger %}
Change a few things up and try submitting again.
{% endalert %}

{% alert success %}
You successfully read this important alert message.
{% endalert %}

{% alert info %}
This alert needs your attention, but it's not super important.
{% endalert %}
```

### Results ###

{% alert warning %}
Best check yo self, you're not looking too good.
{% endalert %}

{% alert danger %}
Change a few things up and try submitting again.
{% endalert %}

{% alert success %}
You successfully read this important alert message.
{% endalert %}

{% alert info %}
This alert needs your attention, but it's not super important.
{% endalert %}


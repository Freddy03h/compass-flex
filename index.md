---
layout: default
---

A Compass module to provide the "new" CSS3 Flexbox because Compass use the "old" one

Mixins writes the 2009, 2011 and 2012 (final) syntaxes


## Getting Started

### Install

Download `lib/_flex.scss`

### Install with bower

{% highlight bash %}
bower install https://github.com/Freddy03h/compass-flex.git --save
{% endhighlight %}

(Note: Use the github repo link because it not registred)


## How to use

Don't forget to import the file

### display: flex

#### scss

{% highlight css %}
@include display-flex;
{% endhighlight %}

#### css

{% highlight css %}
display: -webkit-box;
display: -moz-box;
display: -ms-flexbox;
display: -webkit-flex;
display: flex;
{% endhighlight %}

### flex-direction

#### scss

{% highlight css %}
@include flex-direction(column-reverse);
{% endhighlight %}

#### css

{% highlight css %}
-webkit-box-orient: vertical;
-moz-box-orient: vertical;
-webkit-box-direction: reverse;
-moz-box-direction: reverse;
-ms-flex-direction: column-reverse;
-webkit-flex-direction: column-reverse;
flex-direction: column-reverse;
{% endhighlight %}

### flex-wrap

#### scss

{% highlight css %}
@include flex-wrap(wrap);
{% endhighlight %}

#### css

{% highlight css %}
-ms-flex-wrap: wrap;
-webkit-flex-wrap: wrap;
flex-wrap: wrap;
{% endhighlight %}

flex-wrap doesn't have 2009 equivalent syntaxe

### justify-content

#### scss

{% highlight css %}
@include justify-content(flex-start);
{% endhighlight %}

#### css

{% highlight css %}
-webkit-box-pack: start;
-moz-box-pack: start;
-ms-flex-pack: start;
-webkit-justify-content: flex-start;
justify-content: flex-start;
{% endhighlight %}

### align-items

#### scss

{% highlight css %}
@include align-items(flex-end);
{% endhighlight %}

#### css

{% highlight css %}
-webkit-box-align: end;
-moz-box-align: end;
-ms-flex-align: end;
-webkit-align-items: flex-end;
align-items: flex-end;
{% endhighlight %}

### flex

#### scss

{% highlight css %}
@include flex(1);
{% endhighlight %}

#### css

{% highlight css %}
-webkit-box-flex: 1;
-moz-box-flex: 1;
-ms-flex: 1;
-webkit-flex: 1;
flex: 1;
{% endhighlight %}

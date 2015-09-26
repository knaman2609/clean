---
layout: post
title:  "A Clean Jekyll theme"
date:   2015-09-26 18:51:59
categories: jekyll update
---
##Subheading
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec at mauris ante. Cras sit amet porta quam. Donec eu gravida elit. Sed a diam eget sem lacinia maximus vel et elit. Nullam id egestas nulla. Duis dapibus at quam eu dapibus. Maecenas ullamcorper placerat eros, eu posuere enim bibendum eget. Phasellus mollis enim molestie tortor aliquam, nec auctor ligula `fringilla`.


##Sample Code
{% highlight go %}
package main

import (
    "net/http"
)

func response(rw http.ResponseWriter, request *http.Request) {
    rw.Write([]byte("Hello world."))
}

func main() {
    http.HandleFunc("/", response)
    http.ListenAndServe(":3000", nil)
}
{% endhighlight %}

##List 
- Do this
- Do that
- Bla Bla Bla
- Go to Sleep

##Links
[This link](http://example.net/) has no title attribute.

















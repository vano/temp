---
---
# _config.yml

    markdown: kramdown
    pygments: true
    
    kramdown:
      enable_coderay: true
      use_coderay: true


#example 1
~~~ js
function test(args) {
    console.log(args);
};
~~~

#example 2
``` js
function test(args) {
    console.log(args);
};
```

#example 3
{% highlight js %}
function test(args) {
    console.log(args);
};
{% endhighlight %}

# Playing audio and video in HTML

The `a` tag is a fundamental HTML element responsible for much of the linking goodn ess that makes HTML great!

## What is a HTML5 Video?
In past, We used plug-in tool such as Flash to play video in website.
But Flash is history now,
Today we use HTML5 <audio> and <video> element to embed a video in a web page.
 

The example is like this code here.

``` html
<video width="320" height="240" controls>
  <source src="width="854" height="480" src="https://www.youtube.com/embed/LSxElWwWVFE"" type="video">
</video>
```

As in any tag, there's a basic structure of ```<tag attr="value">content</tag>```. The fantastic, amazing attribute in the `a` tag is `href` -- short for "hypertext reference". The `href` attribute identifies a target URL; when this HTML snippet is displayed in a browser, the browser will direct you to the URL in the href attribute. Let's try it out:

``` html
<a href="https://google.com">Google Owns All Your Data</a>
```

<a href="https://google.com">Google Owns All Your Data</a>

``` html
<iframe width="854" height="480" src="https://www.youtube.com/embed/LSxElWwWVFE" frameborder="0" allowfullscreen></iframe>
```

## Try it yourself

You can clone this repository and load a local copy of [the tutorial page](./a-tag-tutorial.html) in your browser to see the tag in action. Then make some changes to the file to learn this yourself!

## Learn More

The [Mozilla Developer Network](https://developer.mozilla.org/en/docs/Web/HTML/Element/a) has lots more detail about this and every HTML tag!

# Adding audio and video in HTML

Using the `video` and `audio` tag is a fundamental HTML element responsible for much of the linking goodn ess that makes HTML great!

## What is a HTML5 Video?

<a href="https://en.wikipedia.org/wiki/HTML5_video">What is a HTML5 Video</a>

In past, We used plug-in tool such as <a href="https://en.wikipedia.org/wiki/Adobe_Flash_Player">Adobe Flash Player</a> to play video in website.
But Flash is history now,
Today we use HTML5 <audio> and <video> element to embed a video in a web page.
 
The code for input a <video> or <audio> is like this code here.

``` html
  <video width="320" height="240" controls>
  <source src="http://techslides.com/demos/sample-videos/small.mp4" type="video/mp4">
</video> 
```

As in any code, there's a basic structure to build this code. Tags `width="" height=''`  adjust the side of containers of video.

``` html
<video width="320" height="240" controls>
```

The tag `autoplay` allows video to play automatically once the website opened

``` html
<video width="320" height="240" autoplay>
```

The `source` tag tell the browser to find the video from the link address you provided. 

``` html
<source src="http://techslides.com/demos/sample-videos/small.mp4" type="video/mp4">>
```
The `type` identifies the format of the video. 

``` html
<source src="http://techslides.com/demos/sample-videos/small.mp4" type="video/mp4">
```



## Youtube Video

In most situations, you would add youtube videos to your website. It is diffcult to add a youtube video by using <video> code.There is more simple way to add a youtube video.
 
Right click to select the "copy the embed code" option.You get codes with tag <iframe>. The <iframe> tag is used to embed another document within the current HTML document.

``` html
<iframe width="854" height="480" src="https://www.youtube.com/embed/LSxElWwWVFE" frameborder="0" allowfullscreen></iframe>
```

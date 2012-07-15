---
layout: default
title:
description:
---

<link href='http://fonts.googleapis.com/css?family=Crimson+Text' rel='stylesheet' type='text/css'>

<style>
p, ul:not(.nav) > li {
  font-family: 'Crimson Text';
  font-size: 17px;
  line-height: 28px;
}

</style>

<div class = 'subnav subnav-fixed-top'>
<ul class="nav nav-pills">
  <li class="active"><a href="#">Regular link</a></li>
  <li class="dropdown" id="menu1">
    <a class="dropdown-toggle" data-toggle="dropdown" href="#menu1">
      Dropdown
      <b class="caret"> </b>
    </a>
    <ul class="dropdown-menu">
      <li><a href="#">Action</a></li>
      <li><a href="#">Another action</a></li>
      <li><a href="#">Something else here</a></li>
      <li class="divider"></li>
      <li><a href="#">Separated link</a></li>
    </ul>
  </li>
</ul>
</div>


<div class = 'row'>
  
<div class = 'span3'>
<div class = 'well' markdown = '1'>  

* {: .nav-header}Course
* {: .active}[<i class="icon-home icon-white"> </i> Home](#)
* [<i class="icon-list"> </i> Outline](#)
* [<i class='icon-road'> </i> Roadmap](#)
* [<i class="icon-book"> </i> Syllabus](#)
* [<i class='icon-calendar'> </i> Calendar](#)
* {: .divider}  
* {: .nav-header}Assignments
* [<i class="icon-home"> </i> Assignment 1](#scatterplots)
* [<i class="icon-book"> </i> Assignment 2](#)
* [<i class="icon-book"> </i> Assignment 3](http://mgcr271.ianswer.me/) 
{: .nav .nav-list}
  
</div> <!-- well -->
</div> <!-- span3 -->

<div class = 'span9' markdown = '1'>
## Scatterplots
{: id = 'scatterplot'}

Let us construct a [scatterplot][scatterplot]{: #example} showing the relationship between the `weight` and `mileage` of a car. Here is the R code that you can use to construct the scatterplot.

[scatterplot]: # "A scatterplot displays the relationship between two numerical variables"

<script>
$('#example').tooltip()
</script>

~~~
require(ggplot2)
qplot(wt, mpg, data = mtcars)
~~~

## Carousel 

<div id="myCarousel" class="carousel slide">
  <!-- Carousel items -->
  <div class="carousel-inner">
    <div class="active item">
      <img src = 'http://placehold.it/700x300'>
      <div class="carousel-caption">
          <h4>Second Thumbnail label</h4>
          <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
      </div>
    </div>
    <div class="item"><img src = 'http://placekitten.com/700/300'></div>
    <div class="item"><img src = 'http://placehold.it/700x300'></div>
  </div>
  <!-- Carousel nav -->
  <a class="carousel-control left" href="#myCarousel" data-slide="prev">&lsaquo;</a>
  <a class="carousel-control right" href="#myCarousel" data-slide="next">&rsaquo;</a>
</div>

<div id = 'new' class = 'carousel slide'>
  <!-- Carousel Items -->
  <div class = 'carousel-inner'>
    <div class = 'active item'>
      <img src = 'http://placehold.it/700x300'>
      <div class = 'carousel-caption'>
        <p>item 1</p>
      </div>
    </div>
    <div class = ' item'>
      <img src = 'http://placekitten.com/700/300'>
      <div class = 'carousel-caption'>
         item 2
      </div>
    </div>
  </div>
  <!-- Carousel Nav -->
  <a class='carousel-control left' href='#new' data-slide='prev'>&lsaquo;</a>
  <a class='carousel-control right' href='#new' data-slide='next'>&rsaquo;</a>
</div>

<div id = 'new2' class = 'carousel slide'>
  <!-- Carousel Items -->
  <div class = 'carousel-inner'>
    <div class = 'active item'>
      <img src = 'http://media.merchantcircle.com/32841569/128809395XIrNxi_fs_full.jpeg'>
      <div class = 'carousel-caption'>
        <p><strong>Sampling</strong> distributions are the conceptual key to statistical inference. Many 
        approaches to   
        understanding sampling distributions use examples of drawing marbles or gumballs from a large jar 
        to illustrate the inﬂuences of randomness on sampling. Using the list of U.S. states illustrates how 
        a non-normal distribution nonetheless has a normal sampling distribution of means.</p>
      </div>
    </div>
    <div class = ' item'>
      <img src = 'http://media.merchantcircle.com/32841569/128809395XIrNxi_fs_full.jpeg'>
      <div class = 'carousel-caption'>
        <p>item 2</p>
      </div>
    </div>
  </div>
  <!-- Carousel Nav -->
  <a class='carousel-control left' href='#new2' data-slide='prev'>&lsaquo;</a>
  <a class='carousel-control right' href='#new2' data-slide='next'>&rsaquo;</a>
</div>

<script>$(.carousel).carousel()</script>

While interpreting a scatterplot, it is important to focus on four aspects.

- **Direction**
- **Form**
- **Strength**

Let me try some math

$$
\begin{aligned}
\alpha & = \beta \\
\beta & = \gamma
\end{aligned}
$$

Let check out an image

![placehold](http://placekitten.com/700/300)

<form enctype="multipart/form-data" action="http://beta1.opencpu.org/R/call/base/identity/png" method="POST"> 

<textarea name="x" rows="12" cols="160">

x <- rnorm(1000)
print(hist(x))


</textarea>
<br />
<br />

<input type="submit" value="Run code" />
</form>


</div> <!-- span9 -->

</div> <!-- row -->


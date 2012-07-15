<div class = 'subnav'>
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


~~~
#' Embed local images using base64
#'
#' @keywords internal
#' @param html_in path to input html file
#' @param html_out path to output html file
#' @return 
embed_images <- function(html_in, html_out){
  html <- paste(readLines(html_in), collapse = "\n")
  html <- markdown:::.b64EncodeImages(html)
  writeLines(html, html_out)
}
~~~


<iframe allowFullScreen width = '940px' height = '700px' scrolling = 'no'
  src = 'http://ramnathv.github.com/slidify/examples/'>
</iframe>

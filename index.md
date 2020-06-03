<link rel="stylesheet" type="text/css" href="mystyle.css" />

# Images and how to Style them

> How to style your images   
> ver 0.9 uses mystyle.css - .infoXXX
> ver 0.91 adds a href


### Normal image

Markdown is a convenient HTML-focused shorthand syntax for formatting content such as documentation and blog articles, but it lacks basic features for image formatting, such as alignment and sizing. This post presents a variety of ways to format images with Markdown, from brute force to proprietary syntax extensions, unwise hacks, and everything in between.

### original Image

![Alfred E Neumann](alfredeneuman.jpg "Alfred E Neumann")


###  Use Standard HTML

Markdown was originally designed for HTML authoring, and permits raw HTML anywhere, anytime. As such, the most straightforward solution is simply to use HTML with the desired attributes:

<img src="alfredeneuman.jpg" alt="alfred"
    title="Alfred E Neuman" width="150" height="100" />

The above used /<img/> html code.

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Itaque hic adipisci pariatur enim corporis laborum ab, alias ut laboriosam, unde a! Perspiciatis, ipsam, magni. Modi nam reprehenderit sunt fugit, explicabo.

![Alfred](alfredeneuman.jpg#thumbnail)

This is a thumbnail version using a stylesheet, the code is shown as below

```html
![Alfred](alfredeneuman.jpg#thumbnail)
```

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae omnis odio eos, consequuntur enim ab minus dolorem optio, corporis quisquam eligendi nobis, delectus, tempora sunt! Illum eligendi quaerat debitis atque.

This uses a \<section\> and \<figure\>, however, you cannot indent your code and have only 1 space between tags.  Somehow the github processor does not process the /<a href.../> which you can examine by looking at the source code.  This works nicely when it works.

<section class="info" markdown="1" >
 <figure class="infoimg">
  <img class="w320" src="alfredeneuman.jpg" alt="ThingSpeak Output" />
 <figcaption>
  Alfred E Neumann of MAD
 </figcaption>
 </figure>
<div  class="infotext">
 <p><b>Instructions</b></p>
 <ul>
 <li>Item 1</li>
 <li>Item 2</li>
 <li>Item 3</li>
 <li>Item 4</li>
 <li>Item 5</li>
 </ul>
 </div>
 <div class="infoclr"></div>
</section> <!--End of Section.info-->

The tag **markdown=1** tries to tell the processor that there is markdown code in the HTML.  Well, sometimes it works.

```html
<section class="info" markdown="1" >
 <figure class="infoimg">
  <img class="w320" src="alfredeneuman.jpg" alt="ThingSpeak Output" />
 <figcaption>
  Alfred E Neumann of MAD
 </figcaption>
 </figure>
<div  class="infotext">
 <p><b>Instructions</b></p>
 <ul>
 <li>Item 1</li>
 <li>Item 2</li>
 <li>Item 3</li>
 <li>Item 4</li>
 <li>Item 5</li>
 </ul>
 </div>
 <div class="infoclr"></div>
</section> <!--End of Section.info-->
```

&nbsp;

Ver: 0.7, using a href

Let's try this again with the \<a href=...\> included so that we can get the links working correctly.

<section class="info" markdown="1" ><a href="alredenueman.jpg">figure class="infoimg"> <img class="w320" src="alfredeneuman.jpg" alt="ThingSpeak Output" /><figcaption>Alfred E Neumann of MAD<</figcaption></figure></a>
<div  class="infotext">
 <p><b>Instructions</b></p>
 <ul>
 <li>Item 1</li>
 <li>Item 2</li>
 <li>Item 3</li>
 <li>Item 4</li>
 <li>Item 5</li>
 </ul>
 </div>
 <div class="infoclr"></div>
</section> <!--End of Section.info-->




**June 2020**
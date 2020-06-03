<link rel="stylesheet" type="text/css" href="mystyle.css" />

# Images and how to Style them

> How to style your images   
> ver 0.0005 using ~= and *=*


### Normal image

Markdown is a convenient HTML-focused shorthand syntax for formatting content such as documentation and blog articles, but it lacks basic features for image formatting, such as alignment and sizing. This post presents a variety of ways to format images with Markdown, from brute force to proprietary syntax extensions, unwise hacks, and everything in between.

![Alfred E Neumann](alfredeneuman.jpg "Alfred E Neumann")


###  Use Standard HTML

Markdown was originally designed for HTML authoring, and permits raw HTML anywhere, anytime. As such, the most straightforward solution is simply to use HTML with the desired attributes:

<img src="alfredeneuman.jpg" alt="alfred"
    title="Alfred E Neuman" width="150" height="100" />

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Itaque hic adipisci pariatur enim corporis laborum ab, alias ut laboriosam, unde a! Perspiciatis, ipsam, magni. Modi nam reprehenderit sunt fugit, explicabo.

![Alfred](alfredeneuman.jpg#thumbnail)

This is a thumbnail version using a stylesheet

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur error tempore, quasi, accusamus earum totam laudantium beatae voluptas porro odit adipisci quis officiis molestiae, nemo repellendus nulla magnam aperiam accusantium.

<section class="info">
    <a href="alfredeneuman.jpg" target="_blank"
        <figure class="infoimg">
            <img class="w320" src="alfredeneuman.jpg" alt="Option A Closed Box" />
            <figcaption>Option A Closed Box</figcaption>
        </figure>
    </a>
    <a href="alfredeneuman.jpg" target="_blank"
        <figure class="infoimg">
            <img class="w320" src="alfredeneuman.jpg" alt="Option B Closed Box" />
            <figcaption>Option B Open Enclosure</figcaption>
        </figure>
    </a>
    <div class="infoclr"></div>
</section> <!--End of Section.info-->

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Possimus id sint vel, perspiciatis, aut quas voluptatum saepe fugiat quasi alias laudantium sapiente expedita harum corrupti at ducimus repellendus tempora animi.

<section class="info">
    <a href="alfredeneuman.jpg" target="_blank"
        <figure class="infoimg">
            <img class="w200" src="alfredeneuman.jpg" alt="ThingSpeak Output" />
            <figcaption>
                ThingSpeak Output of Data1 and Data2
            </figcaption>
        </figure>
    </a>
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

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam aliquid, atque voluptatum placeat ut nostrum soluta illum sequi esse vero, doloribus officiis eius exercitationem, hic nam, dicta beatae praesentium ratione?

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae omnis odio eos, consequuntur enim ab minus dolorem optio, corporis quisquam eligendi nobis, delectus, tempora sunt! Illum eligendi quaerat debitis atque.

<section class="info">
    <a href="alfredeneuman.jpg" target="_blank"
        <figure class="infoimg">
            <img class="w320" src="alfredeneuman.jpg" alt="ThingSpeak Output" />
            <figcaption>
                ThingSpeak Output of Data1 and Data2
            </figcaption>
        </figure>
    </a>
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

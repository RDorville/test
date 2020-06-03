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

![image alt >](alfredeneuman.jpg)

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quam labore officia expedita dolorum animi reiciendis possimus, suscipit, vel aut consequatur a. Labore excepturi, quae tempora sunt deleniti voluptatibus voluptas accusamus!

![image alt <](alfredeneuman.jpg)

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quam optio quas, mollitia magnam a nostrum dolores accusantium molestiae voluptatibus, nemo veniam impedit iure provident illo ex corporis fugit perspiciatis vero.

![image alt ><](alfredeneuman.jpg)

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum adipisci quam, facilis debitis quo quos. Reprehenderit modi optio architecto odit maxime autem alias, doloribus veniam hic illo et minus numquam.
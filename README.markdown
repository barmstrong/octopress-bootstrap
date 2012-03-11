This is a theme for the blogging framework [Octopress](https://github.com/imathis/octopress) that is based on [Twitter Bootstrap](http://twitter.github.com/bootstrap/).

### Here is an example

<a href="http://brianarmstrong.org"><img src="https://github.com/barmstrong/octopress-bootstrap/raw/master/source/assets/screenshot.png"  alt="Octopress Bootstrap"/></a>

Since it just regular bootstrap you can of course modify the theme by using any bootstrap theme such as those from at [bootswatch.com](http://bootswatch.com/) or [wrapbootstrap.com](http://wrapbootstrap.com/).

### To Do

* It's still a bit rough around the edges, could use some cleanup (there may be some stuff that is specific to my site in there)
* Unfortunately Bootstrap uses Less and Octopress uses Sass, so for right now I've just included plain CSS from bootstrap.  This works fine but ideally down the road it would use a forked Sass version of bootstrap or modify Octopress to include Less support.  One caveat is that it should ideally still work with the free bootstrap themes such as [bootswatch.com](http://bootswatch.com/).  So there may be some happy combination here.
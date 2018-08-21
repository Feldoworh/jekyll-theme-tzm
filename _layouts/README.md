# _layouts is a Jekyll folder
This folder is the second importance content after index.md for Github Pages to work, as it contains HTML markup of the page.

 * /index.md file is pointing to _layouts/home.html that wraps it
 * later, _layouts/home.html wraps around default.html


To tell Jekyll that you want <code>.md</code> or <code>.html</code>  file to be wrapped around with one of the _layouts you need to specify [Front Matter][1] at the top, inside of it:
<pre><code>
---
layout: randomLayoutNameExample
title: Blogging Like a Hacker
---
</code></pre>
 

[1]:https://jekyllrb.com/docs/frontmatter/

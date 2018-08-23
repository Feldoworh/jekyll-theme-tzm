# assets is a general purpose folder
The files stored in this folder can be directly accessed in any .html file of Jekyll project.
<br>For example:
 * /_layouts/
 * /_includes/
 * /index.md


## Primary folder for SASS:Syntactically Awesome Style Sheets
This folder also contains **main.scss** file that **imports** .scss stylesheets from [/_includes/_sass/](/_includes/_sass) folder.
<br><code><br>assets/main.**scss**</code> is a file that is processed by Jekyll and from which <code>/assets/main.**css**</code> is generated,
for use in:
 * /_layouts/
 * /_includes/
 * /index.md
 
 [/_includes/**_sass/**](/_includes/_sass) is mainly a folder that integrates with Jekyll. 
<br>Files placed inside this folder are possible to access inside other .scss files using Sass <code>@import</code> statements.
<br>**More about that:** https://jekyllrb.com/docs/assets/#sassscss

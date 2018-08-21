# jekyll-theme-tzm<code>.github/README.md</code>
The Project has been started as a research project for Github Jekyll hosted static websites. <br>
Primarly focused to guide The Zeitgeist Movement Chapters into hosting main websites openly and publicly.

## Getting started

Every directory of this repository contains its README.md for notes and context explanation, this README.md that you are reading right now is concerned to give a quick overview of the project.

### Main project files <code>index.md ← _layouts ← _includes ← _assets ← _ssas</code>


| Content  | Description                                                                                   |
|----------|-----------------------------------------------------------------------------------------------|
| _layouts | The directory that contains Jekyll layouts used by index.md                                   |
| index.md | [Primary Github Pages publishing file][1] <br> <code>Contains link to a Jekyll _layout</code> |

[1]:https://blog.github.com/2016-12-09-publishing-with-github-pages-now-as-easy-as-1-2-3/


#### How index.md works
index.md is just a html file, just renamed into .md file, as it can utilize Jekyll Front Matter.<br>
Jekyll Front Matter works even if renamed to index.html

#### How Layouts works
index.md is inserted into ./_layouts/home.html (in the place of {{ content }} variable )<br>
./_layouts/home.html is inserted into ./_layouts/default.html (in the place of {{ content }} variable )

#### How Includes works
Includes are just html snippets accesible by files in ./_layouts/ and other files processed by Jekyll.<br> 
These snippets can be utilized using Liquid tags: 

#### How Assets works 
Assets are just simple non-html files that are not processed. They are served directly.<br>

#### How SASS/CSS files works

#### How Javascript Comments works







<hr>

This Jekyll Project
* Jekyll project has been generated using <code>jekyll new-theme jekyll-theme-awesome</code> https://jekyllrb.com/docs/themes/#creating-a-gem-based-theme
* Jekyll Theme is based off https://github.com/jekyll/minima

This README.md
* Tables of the Github Flavored Markdown has been generated using https://www.tablesgenerator.com/markdown_tables
* <code>README.md</code> file is based off https://gist.github.com/PurpleBooth/109311bb0361f32d87a2

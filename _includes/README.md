# _includes is a Jekyll folder
https://jekyllrb.com/docs/includes/

This is third importance directory as it stores reusable HTML parts for Jekyll _layouts.

Without _includes html, layouts in _layouts would feel bloated.

We store everything in the _includes, so that layouts in the _layouts directory would be more readable.

When you will open any of _layouts, you will see that there is lots of include Liquid tags that are pointing to files in this directory.

liquid include tag example: <code>{% include example.html %}</code>

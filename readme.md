# Teaching Kit Experiments

Some experiment into lowering the barrier to webmaker.org/teach kit creation

## Markdown Content
**Idea:** allow users to write the bulk of the content in [markdown](http://daringfireball.net/projects/markdown/)... this is then parsed into html using [showdown.js](https://github.com/coreyti/showdown).

Markdown is typically easier for people to learn than HTML mostly due to its stripped down syntax. The nice thing about this is that markdown is a HTML preprocessor, so it can be used to start introducing some of the concepts of strcutured language that may make life easier moving to HTML and other langauges beyond.

## Lighter on the code
**Idea:** minimise the amount HTML needed to create a Teaching Kit, thus reducing the time it takes to create.

There is an inherent overhead (time wise) to creating a document by writing raw HTML over using a wysiwyg style editor. For some mentors creating kits may simply be too much of a time drain using Thimble. By reducing the amount of HTML being used to structure the document / layout and moving this into the CSS we can lower the time overhead.

This method is a quicker win, no having to build in new features/functionality, etc..

This lesson ...

> 
Provide an introduction to the lesson.  Let the student know what they are about to experience.  Then provide an outline of headings for the body of the lesson.


Try to have at least 2 headings to break out the lesson into smaller bits.  Remember that the name of the lesson is already a part of the page, so do not repeat it in the 1st heading.





The rest of this template provides examples of several markdown features, especially those useful in our context.  You can find a more complete list on multiple sites.

*   [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
*   [GitHub.com: Basic writing and formatting syntax](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)

This is a paragraph.  It has some **bold** and *italic* text.  Any text meant to be displayed as code or in a terminal should be put in `single tick marks`, not 'quote marks'.  This would include `filenames.zip`, `variables`, and `function_calls()`.

*   Here is a list of items; notice that it is indented 3 spaces after the star.  That is a markdown best practice.
*   This is the 2nd item
    -   It has a sub-item using a dash instead of a star

[A link](https://www.alfresco.com) is pretty easy.  If you just provide the URL, it acts like a link too: https://www.alfresco.com.  Avoid <a href="https://www.alfresco.com">HTML links</a>, although they will work.

> Here is a blockquote, which is great when you are quoting from somewhere else.

1.  Here is an ordered list
2.  This is the 2nd item

    Despite the extra line and because I am still indented, we are still part of the ordered list

3.  Here is a 3rd item

![This shows when the image is loading or does not exist](name-of-image-in-lesson-folder.png "This shows when hovering the mouse over the image")

<img src="avoid-html-img.png" alt="although it will work">

![Alfresco Logo](https://company-154305.frontify.com/api/screen/download/eyJpZCI6MzE4ODI3OSwidmVyc2lvbiI6IjIwMTktMDQtMjYgMTg6MjQ6MDYifQ:frontify:9838D-_nX0Rjy97c908OowHUeGrbdbi-7PWEgVA2U_A "Alfresco")

| Table Heading | Column 2 | Column 3 |
| ------------- | -------- | -------- |
| row 1         | row 1    | row 1    |
| row 2         | two column span    ||

```
Preformatted text is great for showing text files, snippets, or source code.  See the example-source lesson for more examples.
```

???+ info "Collapsible Box Heading"
This is some collapsible text using the [Admonition Extension for flexmark](https://github.com/vsch/flexmark-java/wiki/Admonition-Extension).
> Notice that it does not work in IDEs, but only through the SkillJar preview.

??? faq "Collapsed By Default"
This is hidden unless expanded.

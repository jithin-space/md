# README

MD file called markdown file. It is a text file created using one of several possible dialects of the Markdown language. It is saved in plain text format but includes inline text symbols that define how to format text. MD files are designed for authoring plain text documentation that can be easily converted to HTML


Here we explore how we can write an md5 file from scratch. The original text file used to render the current page you are reading is given as readme.md.orig


# Section 1 - HEADINGS
# This is an H1
## This is an H2
###### This is an H6

This is also an H1
===================

This is also an H2
-------------------

# Section 2 - Paragraphs

paragraphs are separted by empty lines. Within a paragraph it is simply press <return> for a new line.

for example, this is another paragraph,but
it belongs to previous line in the paragraph

# Section 3 - Character styles

*Italic*

_Italic_

**bold**

__bold__

~~strikethrough~~


# Section 4 - Unordered List

* Item 1
* Item 2
* Item 3
    * item 3a
    * item 3b
* Item 4

# Section 5 - Ordered List

1. Step1
2. Step2
3. Step3
    1. Step 3.1
    2. Step 3.2
4. Step4

# Section 6 - List in List

1. Step 1
2. Step 2
    * ul 1
    * ul 2

# Section 7 - Quotes or citations

Following is an example of a quote

> Everybody Continues to be in its state of rest
> or state of motion unless
> it is acted upon by an external unbalanced force

# Section 8 - Inline code characters.

use the backtick to refer to a `function()`.

There is a literal ``backtick `(`)``  here.

# Section 9 - Code blocks

Indent every line of the block by at least 4 spaces.

This is a normal paragraph but

    This is a code block.
    With multiple lines.

Alternatively , you can use 3 backtick quote marks before and after.

```
This is a code block
```

To add syntax highlighting to a code block, add the name after the backticks:

```javascript
document.getElementById("test");
window.onbeforeunload = function() {
    saveCoverage();
};
```

# Section 10 - Links

This is an [example](http://www.example.com/) inline link

[This link](http://example.com/ "Title") has a title attribute.

links are auto-detected in text: http://example.com

# Section 11 - Images

![Alt text](md.png)


[imageid]: https:://images.com

![Reference Image][imageid]

# Section 12 - Tables

| Day   | Meal  | Price |
| ------|-------|-------|
| Monday| pasta | $5    |
| Tuesday| chicken | $8 |



# Reference

This is only an attempt to learn md inspired from [this](https://confluence.atlassian.com/bitbucketserver/markdown-syntax-guide-776639995.html) link.

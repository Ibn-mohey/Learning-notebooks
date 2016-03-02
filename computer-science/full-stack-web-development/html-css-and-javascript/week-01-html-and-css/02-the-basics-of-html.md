<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
Table of Contents

-   [The Basics of HTML](#the-basics-of-html)
-   \[\`: Level 1 heading
-   \`\`: paragraph

-   Code in the `* Anything in the` is information *about* the web page.
    This is generally not shown.
    -   Style as well. `...` or \`\`
    -   Meta informmation. \`\`
    -   Scripts: \`\`
    -   Location of the main file.
-   Attributes
    -   Attributes help define elements further.
    -   Like parameters of a function in other languages.
    -   Must use quotes (can be single or double).
        -   e.g. `<head lang="en">` -- `lang="en"` is the attribute

Some Common HTML Elements
-------------------------

-   Headings
    -   `<h1>` ... `<h6>` are the headings.
    -   Browser show them by default as bigger to smaller.
    -   They were originally designed to denote sections.
-   Sections
    -   `<section>` is used to indicate a section now.
    -   Does nothing visual - just for code structure.
-   Lists
    -   `<ul>`: unordered list
    -   `<ol>`: ordered list
        -   Attributes
            -   `start="number"`
            -   `reversed`: reverses the list ordering (e.g. 3, 2, 1)
    -   `<li>`: List item
    -   Attributes
        -   `type="A"` - will order A, B, C
-   Comments
    -   Comments denoted like: `<!-- comment -->`
    -   May be added anywhere
    -   Hidden from the browser

Formatting HTML Text
--------------------

-   *Italic*
    -   `<i>` or `<em>`: <i>Italicizes</i> text.
    -   `<em>` is for *emphasis*. Does the same thing as `<i>`, but for
        readability indicates emphasis on the text.
-   **Bold**
    -   `<b>` or `<strong>`: Makes text <b>bold</b>.
    -   `<strong>` has the same story as `<em>`.
-   Underline
    -   Try not to use if possible. It causes confusion with links.
    -   `<u>`: <u>Underlines text</u>
-   Big & Small
    -   `<big>`: Makes text <big>big</big>.
        -   Not part of HTML5 anymore.
    -   `<small>`: Makes text <small>small</small>.
-   Highlighting text
    -   `<mark>`: <mark>Marks the text</mark>
-   Subscript & Superscript
    -   `<sub>`: Moves text <sub>down</sub>
    -   `<sup>`: Moves text <sup>up</sup>
-   Inserted and Deleted text
    -   `<ins>`: Shows something has been <ins>inserted</ins>
    -   `<del>`: Shows something has been <del>deleted</del>.
    -   Usually only for an editing visual. Not often
        used. \](\#-level-1-heading%0A--paragraph%0A%0A-code-in-the-%0A-----anything-in-the--is-information-about-the-web-page-this-is-generally-not-shown%0A-----style-as-well--or-%0A-----meta-informmation-%0A-----scripts-%0A-----location-of-the-main-file%0A%0A-attributes%0A-----attributes-help-define-elements-further%0A-----like-parameters-of-a-function-in-other-languages%0A-----must-use-quotes-can-be-single-or-double%0A---------eg-head-langen----langen-is-the-attribute%0A%0A-some-common-html-elements%0A%0A-headings%0A-----h1--h6-are-the-headings%0A-----browser-show-them-by-default-as-bigger-to-smaller%0A-----they-were-originally-designed-to-denote-sections%0A-sections%0A-----section-is-used-to-indicate-a-section-now%0A-----does-nothing-visual---just-for-code-structure%0A-lists%0A-----ul-unordered-list%0A-----ol-ordered-list%0A---------attributes%0A-------------startnumber%0A-------------reversed-reverses-the-list-ordering-eg-3-2-1%0A-----li-list-item%0A-----attributes%0A---------typea---will-order-a-b-c%0A-comments%0A-----comments-denoted-like----comment---%0A-----may-be-added-anywhere%0A-----hidden-from-the-browser%0A%0A-formatting-html-text%0A%0A-italic%0A-----i-or-em-iitalicizesi-text%0A-----em-is-for-emphasis-does-the-same-thing-as-i-but-for-readability-indicates-emphasis-on-the-text%0A-bold%0A-----b-or-strong-makes-text-bboldb%0A-----strong-has-the-same-story-as-em%0A-underline%0A-----try-not-to-use-if-possible-it-causes-confusion-with-links%0A-----u-uunderlines-textu%0A-big-&-small%0A-----big-makes-text-bigbigbig%0A---------not-part-of-html5-anymore%0A-----small-makes-text-smallsmallsmall%0A-highlighting-text%0A-----mark-markmarks-the-textmark%0A-subscript-&-superscript%0A-----sub-moves-text-subdownsub%0A-----sup-moves-text-supupsup%0A-inserted-and-deleted-text%0A-----ins-shows-something-has-been-insinsertedins%0A-----del-shows-something-has-been-deldeleteddel%0A-----usually-only-for-an-editing-visual-not-often-used)
-   [About HTML](#about-html)
-   [Getting to Know HTML](#getting-to-know-html)
-   [Some Common HTML Elements](#some-common-html-elements)
-   [Formatting HTML Text](#formatting-html-text)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
The Basics of HTML
==================

About HTML
----------

-   Main language for building web-pages.
-   Around since the 1990's.

The workflow for HTML.

1.  The browser sends a request to the server, asking for a web page.
2.  The server sends the web page back to the browser.
3.  The browser displays the web page.

The worfklow for a single page application.

1.  The browser sends a request to the server asking for a small piece
    of data.
2.  The server sends the small piece of data.
3.  The browser displays the data.
4.  The page repeats.

HTML compared to SVG.

-   SVG - graphics approach, but very few libraries.
-   HTML - text approach, a lot of libraries.

Getting to Know HTML
--------------------

-   HTML is defined by the World Wide Web Consortium (W3C).

-   HTML commands are called **elements**.
-   Elements usually have a start and end tag.

The general structure of an HTML page is as follows:

``` {.html}
<!DOCTYPE html>
<html>
    <head>
        ...
    </head>
    <body>
        ...
    </body>
</html>
```

-   `<body>` is usually what we see.

-   `<h1>`: Level 1 heading
-   `<p>`: paragraph

-   Code in the `<head>`
    -   Anything in the `<head>` is information *about* the web page.
        This is generally not shown.
    -   Style as well. `<style>...</style>` or `<link ... />`
    -   Meta informmation. `<meta ... />`
    -   Scripts: `<script ... />`
    -   Location of the main file.
-   Attributes
    -   Attributes help define elements further.
    -   Like parameters of a function in other languages.
    -   Must use quotes (can be single or double).
        -   e.g. `<head lang="en">` -- `lang="en"` is the attribute

Some Common HTML Elements
-------------------------

-   Headings
    -   `<h1>` ... `<h6>` are the headings.
    -   Browser show them by default as bigger to smaller.
    -   They were originally designed to denote sections.
-   Sections
    -   `<section>` is used to indicate a section now.
    -   Does nothing visual - just for code structure.
-   Lists
    -   `<ul>`: unordered list
    -   `<ol>`: ordered list
        -   Attributes
            -   `start="number"`
            -   `reversed`: reverses the list ordering (e.g. 3, 2, 1)
    -   `<li>`: List item
    -   Attributes
        -   `type="A"` - will order A, B, C
-   Comments
    -   Comments denoted like: `<!-- comment -->`
    -   May be added anywhere
    -   Hidden from the browser

Formatting HTML Text
--------------------

-   *Italic*
    -   `<i>` or `<em>`: <i>Italicizes</i> text.
    -   `<em>` is for *emphasis*. Does the same thing as `<i>`, but for
        readability indicates emphasis on the text.
-   **Bold**
    -   `<b>` or `<strong>`: Makes text <b>bold</b>.
    -   `<strong>` has the same story as `<em>`.
-   Underline
    -   Try not to use if possible. It causes confusion with links.
    -   `<u>`: <u>Underlines text</u>
-   Big & Small
    -   `<big>`: Makes text <big>big</big>.
        -   Not part of HTML5 anymore.
    -   `<small>`: Makes text <small>small</small>.
-   Highlighting text
    -   `<mark>`: <mark>Marks the text</mark>
-   Subscript & Superscript
    -   `<sub>`: Moves text <sub>down</sub>
    -   `<sup>`: Moves text <sup>up</sup>
-   Inserted and Deleted text
    -   `<ins>`: Shows something has been <ins>inserted</ins>
    -   `<del>`: Shows something has been <del>deleted</del>.
    -   Usually only for an editing visual. Not often used.


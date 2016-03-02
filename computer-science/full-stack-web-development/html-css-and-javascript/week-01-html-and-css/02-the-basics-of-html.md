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


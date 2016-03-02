<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
Table of Contents

-   [Multimedia](#multimedia)
-   [Images](#images)
-   [Audio](#audio)
-   [Video](#video)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
Multimedia
==========

Images
------

``` {.html}
<img src="/path/img.png" />
```

-   Attributes:
    -   `width="number"`
    -   `height="number"`
-   If you specify `width`, the browser will automatically adjust the
    `height` to scale properly. This also works vice-versa.
-   You may also specify percentages instead of numbers.

Audio
-----

``` {.html}
<audio src="audio.mp3"></audio>
```

-   Attributes
    -   `autoplay`: automatically plays the sound
    -   `controls`: gives user controls for the audio
    -   `loop`: repeats the sound indefinitely
-   In general, it's wise to use the MP3 format.
    -   This is because it's supposed to work in all browsers.

**If older browsers cannot handle the newer tag (this is an HTML5
tag)**:

-   Note that older browsers don't know what to do with a new tag. So,
    you can specify:

``` {.html}
<audio src="audio.mp3">
    <p>Sorry, your browser is not supported for the <i>audio</i> tag</p>
</audio>
```

-   Newer browsers won't render the text. Older browsers will only
    display the text.

Video
-----

``` {.html}
<video src="video.mp4"></video>
```

-   Video attributes are the same as `<audio>`.
-   Use `alt="description"` for search engines and the blind.


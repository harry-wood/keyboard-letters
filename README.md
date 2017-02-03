# keyboard-letters
Game for babies. Whack the keyboard. See (and hear) colourful letters

**>>> [Play Keyboard Letters Game](https://harrywood.co.uk/kids/keyboard-letters/) <<<**

[Read the blog post about it](https://harrywood.co.uk/blog/2016/09/10/keyboard-letters-game/)

[![still image](https://harrywood.co.uk/blog/wp-content/uploads/2016/09/keyboard-letters-video.png)](https://www.youtube.com/watch?v=DXWnODG4VBg)

## Parameters

`voice` - specify which browser voice synthesis voice to use. Note: Some voice names seem to be web
standard, others not. e.g. this one will work on Chrome but not on safari:
https://harrywood.co.uk/kids/keyboard-letters/?voice=Google%20UK%20English%20Female

`maxlen` - specify a limit to the number of letters on screen. Hit the limit and they'll start
disappering in the background as you type

## Dev notes
Currently it's an all-in-one-file self contained thing (css and javascript inline in the HTML)
which I rather like actually, but if we want to make it more complicated, or if I want to share
logic across several similar "kids" things, then I might end up splitting out the javascript.

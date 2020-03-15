# keyboard-letters
Game for babies. Whack the keyboard. See (and hear) colourful letters

**>>> [Play Keyboard Letters Game](https://harrywood.co.uk/kids/keyboard-letters/) <<<**

[Read the blog post about it](https://harrywood.co.uk/blog/2016/09/10/keyboard-letters-game/)

[![still image](https://harrywood.co.uk/blog/wp-content/uploads/2016/09/keyboard-letters-video.png)](https://www.youtube.com/watch?v=DXWnODG4VBg)

## Not just letters!

Spell out some words to trigger something special. Which words? See if you can find them. ...or cheat
and look at the source code.

Also try **sums**! Type `1+2=`

## Options

`voice`: Specify which browser voice synthesis voice to use.

The list of voices comes from your chosen browser. Some voice names seem to be web standard, others
not, so it can be fun look in a different browser e.g. this one will work on Chrome but not on safari:
https://harrywood.co.uk/kids/keyboard-letters/?voice=Google%20UK%20English%20Female

In general Chrome's voice synthesis seems the best. We've also had fun with the "Portuguese" voice
(although keyboard letters is not internationalised when it comes to reading words)

`mode`:
  - `letters` (default) - Just showing letters.
  - `words` - Show and read out words beginning with that letter.
  - `letter-is-for-word` - Read out letter "is for" word e.g. "A is for Apple". 

Words and images for those words come from the
[WikiJunior Alphabet book](https://en.wikibooks.org/wiki/Wikijunior:Alphabet) (all open licensed)

`maxlen` - (Secret option only as a URL parameter) Specify a limit to the number of letters on
screen. Hit the limit and they'll start disappering in the background as you type

## Dev notes
Currently it's an all-in-one-file self contained thing (css and javascript inline in the HTML)
which I rather like actually, but if we want to make it more complicated, or if I want to share
logic across several similar "kids" things, then I might end up splitting out the javascript.

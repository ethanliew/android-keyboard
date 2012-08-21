Why
====

I'm thrifty, with an LG Optimus V in my hand. It's got a 3.2" screen which makes typing on the standard Android keyboard a frustrating process. So I'm modifying the SoftKeyboard sample project, and experimenting with ways to arrange the keys differently such that they can be made larger.

View screenshot.png for a preview.

Ideas
====

The stock keyboard contains as many as 10 keys on a row. This is too many for my fingers to handle, so this project has an 8 key maximum.

To do this, I've doubled up on some letters. For the top row, the letters "o" and "p" are coupled with "u" and "i". Double-tap either of those to get the secondary letter. I'd like to change this behavior to involve a long-press, once I learn how. The "l" from the second row is coupled with "k". The "^h" on the third row represents Backspace. The "#" switches to symbols, which I've yet to modify the layout of.

Another approach may be to initially hide the 3 or so right-most keys on all rows. They'd be off the right side of the screen and the view could be made to shift to the right by pressing a button near the shift key.

To Do
====

* Finish modifying layout of the symbols keys.
* Try the alternative method of accessing keys that are hidden by the right side of the screen.
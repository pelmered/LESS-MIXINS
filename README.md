LESS-MIXINS
===========

Built on and with Less CSS ( http://lesscss.org/ ) "The dynamic stylesheet language."


WHAT IS LESS?

LESS extends CSS with dynamic behavior such as variables, mixins, operations and functions. LESS runs on both the client-side (Chrome, Safari, Firefox) and server-side, with Node.js and Rhino.
Less enables you to write faster and better CSS and keeps your CSS code shorter and more maintainable.


WHAT IS LESS-MIXINS?

This is just a collection of LESS mixins (see http://lesscss.org/#-mixins for more information) that are free to use. 


HOW TO USE LESS-MIXINS?

1: Sett up Less. Either client-side or server-side(both works, the demo uses client-side on-the-fly compilation with Javascript. For instructions, see http://lesscss.org/#-client-side-usage

2: Create a less file for your project (file endning should be .less) or use style.less from the demo. The less file should import the less-mixin file (@import "less/mixins.less";)

3: Edit the default values in less/vars.less to fit your project or override them in your less style file.

4: Link the less style in your HTML like this: <link rel="stylesheet/less" type="text/css" href="./style.less">

5: Enjoy a brand new CSS experience!


TODO
 * More default values(and use them more)
 * Add a lot more mixins
 * Sort mixins in a logical order. Alphabetical or categorized/gouped(and separated into multiple files?)? - Give me feedback on this one
 * Better demopage and documentation

Please fork and/or make a pull request!



INCLUDED FEATURES AND MIXINS:

 * BASE SETTINGS / DEFAULT VALUES 
 * CLEARFIX
 * WRAP
 * PRE
 * HIDE-TEXT (CSS image replacement)
 * TEXT ALIGN SHORTCUTS
 * MARGIN SHORTCUTS
 * MARGIN - H / V
 * PADDING SHORTCUTS
 * PADDING - H / V
 * SIZING, BOXING and MASKING
 * MASKING
 * POSITIONING
 * BORDER-RADIUS
 * BOX-SHADOW
 * TEXT-SHADOW
 * GRADIENT
 * ROTATE
 * SPRITES
 * VERTICAL STATES SPRITE
 * HORIZONTAL STATES SPRITE
 * INLINE LIST
 * USER-SELECT
 * SCALE
 * TRANSLATE
 * SKEW
 * TEXT-COLUMNS
 * TRANSITIONS
 
 * A LOT MORE WILL BE ADDED CONTINUOUSLY. So check back regularly.



Based on LessMixin, https://github.com/movableapp/LessMixin
click-invaders
==============

DISCLAIMER: DOES NOT WORK IN FIREFOX*

## A CSS-only demo game

I had the idea 10 years a go to use the available CSS pseudo-classes for the form elements to make a game, and turned out it kind of worked!
Even though I had lots of improvements in mind I left it as is, and it became "unplayable".

## The revival - Sinden Lightgun 

I was reminded of this experimentation when I acquired a Sinden Lightgun, to use with rail-shooting games like Virtua Cop or The House Of The Dead among others. To work, the software for the Sinden Lightgun adds a (usually) white border so the camera inside the gun cam determine where you are pointing based on that white rectangle, and move the mouse pointer accordingly. A mouse click, eh? Then maybe it works with click-invaders!
Alas, no. The code as it was had several problems, some stuff were simply wrong and for some reason, I just couldn't shoot anything so it was time for some fixing.

What was added/changed/fixed:
- got rid of CSS less, went full static (granted, I should have used CSS variables but meh for now)
- added a native white border for the Sinden Lightgun
- scaled the game to 960px tall
- fixed and varied invaders trajectories
- added a Win screen
- added a link to Try Again
- reduced the play time to 12s

I would rewrite all of it to higher standards but it is not worth spending the time. It works, it's a quick tool for testing the Sinden Lightgun, but it's just an experiment, not a game.

_*Firefox is my current default browser, but the reason why I thought the game was broken and I couldn't shoot anything is due to a bug (presumably) on Firefox that makes it impossible to click on a label element while moving the mouse cursor above it. No problem with clicking a checkbox when moving, but a label, nope. I had no issue on Chrome, Edge, Opera._
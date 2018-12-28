# The Zenmacs keyboard

![image](https://user-images.githubusercontent.com/1162994/50515388-b0490300-0aa4-11e9-8b15-7cd02dbf2983.png)

## What

I find myself heavily using 3 modifiers (cmd+option+control) for daily editing, but no keyboard appears optimized for that.

* Currently I use the Apple Wireless Keyboard 1, with <kbd>Caps Lock</kbd> remapped to <kbd>Control</kbd>. For comfort I'd need some symmetry: another similarly-sized <kbd>Control</kbd> for my right hand.

* I also use home/end/pageup/pagedown heavily, having to prefix those with <kbd>Fn</kbd> sucks.

So I'm planning to build a custom keyboard.

## Key features

* Deeply symmetric. Both hands have:
  * arrow keys (in dark grey)
  * 3 modifiers (cmd+option+control) at a generous size. This is a game changer, you'll find yourself using the editor in a more modifier-heavy manner
  * a tabulator (great for not allocating just one hand to app switching, which can be overly repetitive)
  * delete key (working in either direction)
* A-Z keys are also (almost) symmetric: no hand is more dedicated than the other to entering prose
  * Normally the left one is much more dedicated, and the right one has to be angled
* Compact: only slightly wider than an Apple Wireless Keyboard
* Columnar/staggered hybrid
  * I've never tried columnar, I suspect it has some benefits but also I don't have problems with staggered
  * So, I mosly went for columnar for curiosity/symmetry, but also I don't mind falling back to staggered in the two bottom rows, which I had to do
* Emphasis on wideness for special keys
  * Experiment: Hit shift+return in an Apple keyboard, using your right-hand index and middle fingers. Isn't it the most pleasing thing in the world?
* Caps key! We all could use it from time to time.
* Qwerty layout not essential of course, and trivially swappable at a physical level.

## The build

* Mechanical
  * Never tried them, never felt the need either, but it's simpler and cheaper to build
* Low-profile keys
  * Kailh makes them. Should give the keyboard a reminiscence of my beloved Apple Wireless Keyboard.
* Needs a custom PCB, given the columnar/staggered hybrid
* Wired, non-split, with a LED for the caps key

## The plan

* Commission the PCB design and manufacturing at some point
  * No idea about pricing!
  * Hopefully the complexity would be low, in the end I just want the usual ingredients arranged in a different way
* If any individual or small group is also interested in my idea, we can split some costs to accelerate the process
* Also custom case/plates will be needed, given the unique size and arrangement
* I'll need a variety of keycaps: 1u, 1.25u, 1.5u, 2u, 4u
  * Might be hard for Kailh
  * 4u not very common, but they make them https://clueboard.co/parts/nantucket-selectric-blank-keys

## Suggestions, variations?

Copy the contents of the `raw_data` file, open http://www.keyboard-layout-editor.com , paste it into the `Raw data` tab.

# cxr.spectrum8

From the ashes of [Project Arthur](https://www.youtube.com/watch?v=fOqBq4ULkB0), and the namesake of my old cellular automata painter comes a simple sandbox for a temporally-aware CA. Rather than merely showing whether a cell is on or off, it uses a number of previous board states and a dot product to show more relativistic changes.

If you want to mess around with it yourself, all you need to do is tinker with the parameters in the `main` function of `__main__.py`.

* `color` is currently random, but you do you
* `l`, `w` specifies dimensions. I *think* it works better if it's odd
* `dot` defines the weight given to each previous frame
* `code` indicates the starting board
* `FPS` is...frames per second. Not sure what else to say there
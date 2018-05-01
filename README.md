Cross Section Of The Menger Sponge With OpenSCAD
------------------------------------------------
<!-- (Menger Sponge:= 3D Sierpinski Carpet) -->
A while back I found [this puzzle](https://www.theguardian.com/science/2017/apr/10/can-you-solve-it-the-incredible-sponge-puzzle) on what the cross section of a Menger Sponge would look like.
This repository contains a simple [OpenSCAD](openscad.org/) script that answers the question.
<p align="center">
	<img src="https://github.com/saeedghsh/Menger-Sponge-Cross-Section/blob/master/demo.gif">
</p>

This is my first OpenSCAD experience, and due to my lack of experience and short time, the currect version takes a brute-force approach rather than a recursive one.

To Do
-----
No [side-]project is complete without a never-to-be-fulfilled todo list:
- [ ] explain the "90-35.2643897" rotation angle of cross-section.
- [ ] solve this with recursion.
- [ ] instead of cross-section, as a flat slice, cut the cube in half.
- [ ] do it with Blender.

License
-------
Distributed with a GNU GENERAL PUBLIC LICENSE; see [LICENSE](https://github.com/saeedghsh/Menger-Sponge-Cross-Section/blob/master/LICENSE).
```
Copyright (C) Saeed Gholami Shahbandi
```

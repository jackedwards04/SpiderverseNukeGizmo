# Spiderverse Nuke Gizmo
A free non-commercial gizmo for Nuke that provides a stylized look, based off of Spiderman: Into The Spiderverse. The gizmo features color shift and dotting tools, all fully customizable!

This repo contains a sample render, a sample dots image, and the Non-Commercial ComicShift gizmo.

# Usage
The ComicShift gizmo can be imported into Nuke like any other gizmo. For more information, read:
https://learn.foundry.com/nuke/12.1/content/comp_environment/configuring_nuke/sourcing_gizmos.html

The settings are also straightforward. The Red, Green, and Blue Shift controls vary the level of Chromatic Aberration in the respective colors. The Dot Level affects the threshold for dotting bright areas of the image. This DotPattern is customizable and can use any image, but I have included a default image that worked well for me. The Dot Vertical and Dot Horizontal input varies the tiling level, and thus the size, of the dots.

# Notes
The channels of the DotPattern input are clamped to 0 or 1, so images may get distorted. It is recommended to use images similar to the sample provided in this repo.

# Credit
Sample Image: SpiderMan basemesh modified from work of Dynamic123

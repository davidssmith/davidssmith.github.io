---
layout: post
title:  Compressed Sensing Phantom for MRI
date:   2014-12-05
categories:
---

I have posted repository containing a [new MRI phantom](https://github.com/davidssmith/csphantom). My new phantom was designed to be difficult to reconstruct under compressed sensing MRI reconstruction frameworks. Rather than the traditional piecewise constant Shepp-Logan phantom or synthetic brain phantoms, this new one contains intensity gradients with different shapes and objects with a range of sizes. All of the features are designed to test the capabilities of a reconstruction to maintain the intensity slopes without adding staircase artifacts and to resolve objects at a range of spatial resolutions.

If you use it in your work, please let me know. Similarly, if you have suggestions or changes, you can post them as [issues](https://github.com/davidssmith/csphantom/issues) or [submit pull requests](https://github.com/davidssmith/csphantom/pulls).

Enjoy,

Dave

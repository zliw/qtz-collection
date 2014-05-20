qtz-collection
==============

A collection of my quartz composer patches

## Wobble pattern

This is a pattern rendered in a Core Image Kernel is based on the square function of the pixel position, modified by a sinus function for x and y direction. The color is chosen by a color range. It can be used as a background patch with slow wave generators and a small color range or be used as a screensaver with faster animations.

![Preview](preview/pattern_wobble.gif)

## Swirl

This is a spiral image rotated by 360 degrees with a combination of effects giving a slightly hypnotic effect.

* tilting of the image in x and y direction controlled by sine generators
* a core image kernel displacing pixels based on trigometric functions controlled by slow oscillators

![Preview](preview/swirl.gif)

## Rotating Circles

Toying around with the "Replicate in Space" to create translucent circles, which are then
processed by a gaussian blur and a dithering core image kernel.

![Preview](preview/rotating_circles.gif)

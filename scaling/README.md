## Scaling

Scaling your game to different browser window sizes.

### Stretch to fit

![stretch to fit example](/assets/stretch-to-fit.gif)

This will make your game canvas fill the entire available browser window (or iframe if embeded from another source).
In this scenario it's up to us to handle resizing and re-layout our game according to the new dimensions.

[Demo](stretch-to-fit.html) / [Source](https://github.com/DannyT/phaser3-my-examples/blob/master/scaling/stretch-to-fit.html)


### Scale to max

![scale to max example](/assets/scale-to-max.gif)

This will keep your game at a consistent aspect ratio and scale the contents.
We also optionally set a maximum size in order to prevent distortion on very high resolutions. Note we're using CSS to stretch our canvas and using the `object-fit:contain` property to maintain aspect ratio. This isn't supported for [IE/Edge yet](https://caniuse.com/#feat=object-fit).

[Demo](scale-to-max.html) / [Source](https://github.com/DannyT/phaser3-my-examples/blob/master/scaling/scale-to-max.html)
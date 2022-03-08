# Clmtrackr

[clmtrackr](https://github.com/auduno/clmtrackr) is a javascript library for fitting facial models to faces in videos or images.

It gives you points like this: 
![clmtrackr points on face](https://cdn.glitch.com/ef06bfdc-f2e0-4749-ab2e-7ff31c0128c1%2F68747470733a2f2f617564756e6f2e6769746875622e696f2f636c6d747261636b722f6578616d706c65732f6d656469612f666163656d6f64656c5f6e756d626572696e675f6e65775f736d616c6c2e706e67.png?1530015101965)


In this example, it's getting points from a video (using [MediaDevices getUserMedia()](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia) to access 
user's video). I get the left and right pupils which are at positions 27 and 32 and I draw a circle on those positions. You can use those points to control other variables (like size of a shape, music etc), you can even do emotion detection! With clmtrackr, my friends and I made a [face instrument](https://face-the-music.glitch.me/) (making music with your facial expressions)


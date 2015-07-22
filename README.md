# PluginColorExtract

PluginColorExtract is a [Rainmeter][] plugin that will process an image and output colors suitable
for meters in the same skin based on that image. It's intended to be an approximation of the
algorithm iTunes uses to color album views, and as such is oriented around square images. (In fact,
it will internally work off a copy of the image resized to 50 pixels square, so images that have a
different aspect ratio may lose some information in the processing.)

[Rainmeter]: http://rainmeter.net/

![Hey Ocean! - Big Blue Wave](http://i.imgur.com/iDNDoZf.png) ![C418 - Minecraft: Volume Alpha](http://i.imgur.com/9MhFhKf.png)

![Andrew Huang - You Are The Devil](http://i.imgur.com/2vh4Jmp.png) ![she - Orion](http://i.imgur.com/fHbVHAN.png)

To write a skin using this plugin, please consult [the documentation][] for available options. An
example skin is available in the repo.

[the documentation]: https://github.com/icesoldier/PluginColorExtract/blob/master/PluginColorExtract/Documentation/Usage.md
# Background Layer #

A sprite can be:

  1. Transparent, or
  1. opaque.

A transparent sprite is one created with a transparent background: it is a sprite with one layer, and that layer is transparent (see [TransparentLayer](TransparentLayer.md)). It's a sprite that can contain Alpha channel in the final composition.

An opaque sprite is when you specify a colored background. That background is a fixed layer that cannot be moved (as opposed to transparent layers). This layer has [Alpha](Alpha.md)=255 for all pixels, so cannot be transparent in any part.

Basically you can have only one Background layer in your sprite but multiples transparent layers. Also, you can convert the Background layer to a transparent layer using the [Layer from Background](LayerFromBackground.md) action, or convert any transparent layer to the background using [Background from Layer](BackgroundFromLayer.md) action (in this case the converted layer is arranged at the bottom of the [layer stack](LayerStack.md)).
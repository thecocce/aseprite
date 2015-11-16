# New File #

## Create a Sprite ##

![http://i.imgur.com/Gbw00.png](http://i.imgur.com/Gbw00.png)

To create a new sprite you can select `File > New` menu option or press `Ctrl+N` keyboard shortcut. In this dialog you select:

  * The `Width` and `Height` of the new sprite (in pixels). You can choose values from 1 to 65535 for each field.
  * The `Color Mode`, which basically says how many colors you will be able to put in the image.
> > Note: With [RGB](http://en.wikipedia.org/wiki/RGB_color_model) images you can have an independent color for each pixel, in this way each little pixel has its Red, Green, Blue and Alpha (opacity) values. With [Indexed](http://en.wikipedia.org/wiki/Indexed_color) sprites have a special element associated: a [palette](http://en.wikipedia.org/wiki/Palette_(computing)) (with a maximum of 256 colors), in this way each pixel has a palette entry associated, if you change the palette color, all pixels associated to that color will change their aspect. For pixel art, your selection should be _Indexed_.
  * The `Background` color to be used in the sprite.
> > Note: Aseprite's sprites have layers, when you create a new sprite, it is created with just one layer. There a two kind of sprites: 1) Sprites with a background layer, which is a layer at the bottom that cannot be moved, and 2) Sprites without a background layer, where all layers are just transparent. If you specified `Transparent` as background color, you will obtain a sprite with a layer that is completely transparent initially (you will see a checked-background indicating "no background here"). In the other side, if you specified a color as background, you will get a sprite with the background layer painted with that color.
> > There is a special option for this field: the `Background Color`, which is the one selected in the [color bar](ColorBar.md) for the right mouse button.
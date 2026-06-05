## 1. Install [NickelMenu](https://pgaskin.net/NickelMenu/#install) and [NickelSeries](https://pgaskin.net/kepubify/ns/)

NickelMenu enables the options to add your own options and run scripts dircetly from the kobo device, like reconnecting to the PC via USB after having ejected the device.  
NickelSeries adds support for series grouping when combined with Calibre.

#### Note

Last time I set up my Kobo, the `KoboRoot.tgz` file from NickelMenu installation vanished after installing, but the `NickelSeries_v5-bf2db08.zip` file from the NickelSeries installaion stayed. I just left it that way, it's working fine.

## 2. Copy `nm/` to `/Volumes/KOBOeReader/.adds/`

This will add my own options to nickel menu, like turning wallpaper mode on or off without having to connect to the PC first.

For wallpapers to work, this directory has to exist: `/Volumes/KOBOeReader/.kobo/screensaver/`. Put all your wallpapers there, it will automatically cycle through them, every time you lock your Kobo device.  
You can resize the pictures to the perfect size [here](https://www.ebookscreensaver.com/).

## 3. Copy your preferred font into `/Volumes/KOBOeReader/fonts/`

I recommend [Bookerly](https://developer.amazon.com/en-US/alexa/branding/echo-guidelines/identity-guidelines/typography) or [EB Garamond](http://www.georgduffner.at/ebgaramond/download.html)

By default, Kobo will switch Bookerly bold-italic and regular-italic to prevent this from happening, rename the fonts like so:  
Bookerly-Regular -> Bookerly-a.ttf  
Bookerly-Italic -> Bookerly-b.ttf  
Bookerly-Bold -> Bookerly-c.ttf  
Bookerly-BoldItalic -> Bookerly-d.ttf

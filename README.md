# RWD vs RD

## Flexible Grid

The grid is a common style element that has been around for years. With RWD, you have to do a complete redesign around your UX / UI using the Grid as the base to accomplish reflows and layouts. With RD, you overlay a grid on your content and then allow the grid to work for your specific device.

Ex. 1

Completely new HTML. (Complicated version of HTML silk screen layout)

Ex. 2

iPhone layout (SLT Home Page silk screen layout)

Ex. 3

iPad layout (SLT Home Page silk screen layout)

## Responsive Images

The main point behind responsive images is making them fill their container. However, somehow you need to use an image that is going to stretch all the way, from 320 all the way to 1080.

Marcotte cites various ways to do this, including loading separate images.

Ex.

Silk screen of an
- orientation change
- change of small all the way to large

Ex. 2

Creating a carousel
- Marcotte's example of doing it via JS.
- MW example of delivering a unique experience via

## CSS Media Queries

Great power to layer in your CSS. Put things all into a single file. Device support issues can really come into play here.

Value here is breaking apart your various CSS files.

Ex. 1

Show a file with everything in a single file.

Ex. 2

Show Moovweb approach of layering in based on device and then screen size.

## RWD Production Workflow

In Marcotte's book he talks about developing closely with designers. However what is lost is how much coupling you create through this method. Such that when it comes time to develop new features, fix bugs, etc... this is all coupled.

Ex. 1

Fix a bug on the RWD site.

Ex. 2

Fix a bug on the source site. Populates to all the various endpoints.

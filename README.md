iDevices-templates
==================

iPhone and iPad SVG templates for mockup.

## Content

The repository contains 6 empty templates ready to use for your mockups :

- iPhone 5 portrait and landscape
- iPad Retina portrait and landscape
- iPhone 4/4S portrait and landscape

![Template iPhone 5 landscape](http://apps.tribumeta.com/images/tmp/iphone5-landscape.png) ![Template iPhone 5 portrait](http://apps.tribumeta.com/images/tmp/iphone5-portrait.png) ![Template iPhone 5 landscape](http://apps.tribumeta.com/images/tmp/ipad-portrait.png) ![Template iPhone 5 portrait](http://apps.tribumeta.com/images/tmp/ipad-landscape.png) ![Template iPhone 5 landscape](http://apps.tribumeta.com/images/tmp/iphone4-portrait.png) ![Template iPhone 5 portrait](http://apps.tribumeta.com/images/tmp/iphone4-landscape.png)

## Layers

Each template is organized in layers and sublayers as following :

- **Grid layer** : helps calculating coordinates for your components (explained below)
- **Device layer** : contains the shape of the device
- **Basic UI Elements layer** : includes all elements which have an impact on the available space on the screen
 - Status bar layer
 - NavBar layer (for navigation bar)
 - Keyboard layer
 - TabBar layer
- **Your app background layer** : contains a simple rectangle ready to be customized following your needs

## Coordinates and Grid

To facilitate the placement of your components in the mockup and later in Xcode, the templates contain a grid.  

![Template iPhone 5 portrait](http://apps.tribumeta.com/images/tmp/iphone5-portrait-with-grid.png) ![Template iPhone 5 portrait](http://apps.tribumeta.com/images/tmp/ipad-landscape-with-grid.png)

As shown above, all the graphics representing the device are outside the drawing zone. So you can easily choose to export the entire drawing (with the device) or just the page (the app screen).

_**Important**_ Keyboard's height contained in the templates is approximate. Indeed keyboard's dimensions depend on the current locale. If you need to adapt your app content to the keyboard height, please refer to Apple's [Keyboard Notification User Info Keys](https://developer.apple.com/library/ios/#documentation/UIKit/Reference/UIWindow_Class/UIWindowClassReference/UIWindowClassReference.html) documentation.

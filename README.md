# Modern CSS for Leaflet-sidebar
Modern CSS for Leaflet sidebar v2

The [Leaflet sidebar v2 project](https://github.com/Turbo87/sidebar-v2) uses a SASS preprocessor to build the `leaflet-sidebar.css` file to be used with the sidebar plugin. Rather than using SASS, this project contains a modern CSS file which uses features such as CSS variables (aka `custom properties`) to make the sidebar CSS easily tweakable. There is also some optimization of media queries but the file size differences are minimal once both are minimized.

The target browser is Chrome 52. Almost all modern browsers now support CSS custom properties, but if you want to create a CSS file that supports a wide variety of browsers, use [CSS Next](http://cssnext.io) to transform this file to older CSS that will work in the browsers you wish to support.

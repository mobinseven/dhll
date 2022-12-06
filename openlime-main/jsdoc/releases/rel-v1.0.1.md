## OpenLIME Rel v1.0.1
**OpenLIME** (Open Layered IMage Explorer) is an open-source JavaScript library for the efficient display of scalable high-resolution relightable images.

**OpenLIME** natively supports BRDF and RTI datasets, and can be easily extended for other multi-channel raster datasets, such as hyper spectral imaging or other reflectance modeling. Input data can be combined in a multi-layer visualization system using opacity and blending modes, and interactive lenses.

All web image types (*jpg*, *png*, *gif*, etc...) are supported as well as the most common multi-resolution image formats (*deepzoom*, *zoomify*, *IIIF*, *google maps*), which are suitable for large images.

**OpenLIME** provides a set of ready-to-use layers that allows developers to quickly publish their datasets on the web
or make kiosk applications. Ready-to-use layers ranging from images, to multi-channel data (such as, for example, RTI or BRDF) or the combination of multiple layers or for visualization through lenses.

The **OpenLIME** library comes with a responsive user iterface that works well with both desktop monitors and multitouch systems. Additionally, it is designed to be highly configurable, so it will be easy for the experienced developer to build their own custom interface. 

The documentation (work in progress) is available here: https://cnr-isti-vclab.github.io/openlime/

A convenient set of examples can be used both to understand how the library works and as a starting point for programming with **OpenLIME** itself.

### What's new
#### Example of Annotation Editor (client + server). 
This relese adds a complete example of an Annotation Editor (examples/annotation-editor).
Two simple db servers are also provided (php and express) with their instructions.
#### Easing transitions
This release adds easing transitions to interpolate camera movements.
#### New Focus&Context Controller for LayerLens
A new lens controller (**ControllerFocusContext**) allows joint adjustments in camera and lens parameters to ensure a good placement and sizing of the lens within the view.
#### Migrating to Webpack 5.x
The development environment now uses Webpack 5.x in order to improve build time and reduce chunk sizes.
#### Bug fixing
This release fixes some bugs related to handling of click events on LayerSvgAnnotation and problems saving SVG objects on Gooogle Chrome browser.
